# Free Hosting

Overview of free web hosting offers. A good collection can be found at https://free-for.dev/

## Table of Contents  
- [Free Hosting](#free-hosting)
  - [Table of Contents](#table-of-contents)
  - [Static Pages / JAMStack-Hosting](#static-pages--jamstack-hosting)
  - [Object Storage](#object-storage)
  - [PHP](#php)
  - [Ruby](#ruby)
  - [Kubernetes](#kubernetes)
  - [Databases (DBaaS)](#databases-dbaas)
  - [Serverless Functions](#serverless-functions)
  - [Misc](#misc)

## Static Pages / JAMStack-Hosting

|Service Name|Plan|Build Minutes|Concurrent Builds|Outbound Transfer|Storage*|Source Provider/Deployment|Number of Sites|Next pricing step/Month|Credit card required|
|---|---|---|---|---|---|---|---|---|---|
|[Netlify](https://www.netlify.com/)|Starter|300|1|100gb|Unlimited (?)|GitHub, GitLab, Bitbucket, CLI|Unlimited|19$, Pro, 3 concurrent builds, 1K build minutes|No credit card requirements|
|[Vercel](https://vercel.com/)|Hobby|6000|10 every 10 minutes|100gb|Unlimited (?)|GitHub, GitLab, Bitbucket and CLI|Unlimited|20$, Pro plan|No credit card requirements|
|[CloudFlare Pages](https://pages.cloudflare.com)|Free|500|1|Unlimited|Unlimited|GitHub ?|Unlimited|20$, 5 concurrent builds, 5K Build minutes|No credit card requirements|
|[Koyeb](https://www.koyeb.com/)|Free|Unlimited|1|Outbound bandwidth is not charged yet|2GB SSD|GitHub, pre-built Docker containers|1|1.61$, Starter Plan|No credit card requirements|
|[DigitalOcean App Platform](https://www.digitalocean.com/products/app-platform/)|Starter|100|?|1gb|?|GitHub, GitLab|3|5$, 400 build minutes, 40gb outbound transfer|Yes, a credit card is required.|
|[Render](https://render.com/)|Static Sites|Unlimited|Unlimited|100 GB|Unlimited|GitHub, GitLab|Unlimited|100 GB/month bandwidth included at no cost. Additional bandwidth just $0.10/GB per month.|No credit card requirements|
|[Surge](https://surge.sh)|Surge|None|None|Unlimited|Unlimited|CLI, CI/CD|1|Surge Professional at 30$ with unlimited projects|No credit card requirements|
|[Layer0](https://www.layer0.co/)|Community|None|None|100GB Bandwidth|unlimited?|Github, CLI|1 custom domain|3 Custom Domain, 250GB Bandwidth, 5 Environments, 31 Edge Locations, 99.95% Uptime SLA, Real-Time RUM Analytics|No credit card requirements|
|[AWS Amplify Hosting](https://aws.amazon.com/amplify/hosting/)|Free Tier **limited to 1 year**|1000|?|15GB|5GB|?|?|Pay as you go: Build & Deploy $0.01 per build minute, Hosting $0.023 per GB stored /month, $0.15 per GB served|Yes, a credit card is required.|
|[Firebase Hosting](https://firebase.google.com/docs/hosting)|Spark Plan|None|None|360 MB/day / ~10GB/month|10GB|CLI, CI/CD|Limited ~10|$0.026/GB storage, $0.15/GB outbound transfer|Yes, a credit card is required.|
|[GitHub Pages](https://pages.github.com/)|Free|2000 (via GitHub Actions)|20 (GitHub Actions limit) (10 per hour soft limit ?)|100gb soft limit|1gb|GitHub|Unlimited (for public repositories only)|$4, GitHub Pro plan|No credit card requirements|
|[GitLab Pages](https://docs.gitlab.com/ee/user/project/pages/)|Free|400|Unlimited|Unlimited|10gb|GitLab|Unlimited|19$, Premium, 10K build minutes|No credit card requirements|
|[Bitbucket](https://support.atlassian.com/bitbucket-cloud/docs/publishing-a-website-on-bitbucket-cloud/)|||||||||No credit card requirements|
|[Azure Blob](https://azure.microsoft.com/en-us/services/storage/blobs/)|||||||||Yes, a credit card is required.|
|[AWS S3](https://aws.amazon.com/s3/)|||||||||Yes, a credit card is required.|
|[GCP Cloud Storage](https://cloud.google.com/storage)|||||||||Yes, a credit card is required.|
|[Begin](https://begin.com/)||||||||||
|[Deno](https://deno.com/)||||||||||
|[Kinsta](https://kinsta.com/static-site-hosting/)|Free|600|1|100GB|1 GB build image size per site|GitHub, GitLab, Bitbucket|100||No|
|[Erath](https://erath.vercel.app)|Free|||Unknown Limited|Uses your local Storage||No Limits|Free as long you support|No credits card requirements| Free web page hosting through a storage-less webpage hosting model, embedding data directly into URLs for secure and immutable access. Utilizes AES-256 encryption for data protection and integrity, ensuring perpetual availability without traditional data storage.

*\*Note: Storage is influenced by the size limits of your source providers aswell.*

## Object Storage

- [Storj](https://www.storj.io/) (150GB storage & transfer in the "free plan")

## PHP

- http://www.free-webhosts.com/free-php-webhosting.php
- Google App Engine (PaaS that supports PHP)

## Ruby


## Kubernetes

- [Platform9](https://platform9.com/) (Freedom plan)
- [Civo](https://www.civo.com) (on #KUBE100 beta - $70 free credit every month, no credit card required)
- [KubeSail](https://kubesail.com/deployments) Signup using Github and get a free kubernetes cluster for learning kubernetes

## Databases (DBaaS)

- [DataStax Astra](https://astra.datastax.com/) - Cassandra-based, 5 GB free tier, no credit card required
- [MongoDB Atlas](https://cloud.mongodb.com/) - MongoDB-based, 500 MB - 5 GB free tier
- [Koyeb](https://www.koyeb.com/) - Postgres, 1GB memory, 1GB storage, and 0.25 CPU. Available in Frankfurt (Germany), Washington, D.C. (US), and Singapore.
- [Yugabyte Cloud<sup>BETA</sup>](https://cloud.yugabyte.com/) - YugabyteDB-based, 5 GB free tier, no credit card required
- [TiDB Cloud](https://en.pingcap.com/tidb-cloud/) — TiDB is an open source MySQL compatible distributed HTAP RDBMS. TiDB Serverless provides 5GB of row storage, and 5GB of column storage, and 50 million Request Units (RUs) available for free each month. no credit card required
- [InfluxDB Cloud](https://cloud2.influxdata.com/) - Free plan available
- [ElephantSQL](https://www.elephantsql.com/) - PostgreSQL-based, 20 MB 🙂 in free tier
- [MariaDB's SkySQL (cloud)](https://mariadb.com/products/skysql/get-started/) - offers a free $500 in credits for up to three databases of any size and any type (transactional, analytical or hybrid).

## Serverless Functions

| Product | Plan | Credit Card | Languages | Free Quota |
| --- | --- | --- |  --- | --- |
| [Netlify Functions](https://www.netlify.com/products/functions/) | Level 0 | not required | JavaScript, TypeScript, Go | 125K reqs/month, 100 hrs |
| [Vercel Serverless Functions](https://vercel.com/docs/serverless-functions/introduction) | Hobby (non-commercial) | not required | Node.js, Go, Python, Ruby | 12 functions |
| [Firebase Cloud Functions](https://firebase.google.com/products/functions) | Blaze Plan | required | Node.js, Python, Go, Java, .NET, Ruby, PHP | 2M reqs/month |
| [Cloudflare Workers](https://workers.cloudflare.com/) | Free | not required | JavaScript, Rust, C, C++ | 100K reqs/day, 30 functions |
| [AWS Lambda](https://aws.amazon.com/lambda/) | Free Tier limited to 1 year | required | Java, Go, PowerShell, Node.js, C#, Python, Ruby code | 1M reqs/month with the AWS Free Tier |
| Oracle Functions | - | - | - | - |

## Misc
- [fly.io](https://fly.io/) (free tier available)
- [pagecdn.com](https://pagecdn.com/) (free tier for public CDN)
- [cloudlayar.com](https://cloudlayar.com/) (free DDoS protection)
