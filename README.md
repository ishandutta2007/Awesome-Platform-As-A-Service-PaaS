# Awesome-Platform-As-A-Service-PaaS

## Top Platform as a Service (PaaS) Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Application Deployment, Self-Hosted PaaS & Container Orchestration*  

**Last updated: October 2026**



This repository tracks notable **commercial PaaS platforms** and **open-source projects** that simplify application deployment, scaling, and management. These tools abstract away infrastructure so developers can focus on code — from git-push deployments to full Kubernetes orchestration.



**Examples** include Azure App Service, AWS Elastic Beanstalk, Google App Engine, Heroku, Render, Fly.io, Railway, DigitalOcean App Platform, Vercel, and Platform.sh (the category leaders).



**Open-source emphasis**: Self-hosted PaaS is a strong open-source domain. **Coolify** leads with 40,000+ GitHub stars as a Vercel/Heroku/Netlify alternative, while **Dokku** provides a lightweight Heroku-like experience in 100 lines of bash. **CapRover**, **Dokploy**, **Kamal**, and **Tsuru** round out a mature ecosystem. **OpenShift** and **Rancher** bring enterprise Kubernetes management. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Azure App Service](https://azure.microsoft.com/en-us/products/app-service/)**  

  Microsoft's fully managed platform for web apps, APIs, and mobile backends. **Native integration with Azure DevOps, GitHub, and Microsoft ecosystem** . Supports .NET, Java, Node.js, Python, PHP, and Ruby.



- **[AWS Elastic Beanstalk](https://aws.amazon.com/elasticbeanstalk/)**  

  AWS's PaaS for deploying web applications without managing infrastructure. **Automatically handles capacity provisioning, load balancing, and scaling** . Supports Java, .NET, PHP, Node.js, Python, Ruby, Go, and Docker.



- **[Google App Engine](https://cloud.google.com/appengine)**  

  Google's fully managed serverless platform with automatic scaling to zero. **The original PaaS** (launched 2008) — standard environment for rapid deployment, flexible environment for custom runtimes.



- **[Heroku](https://www.heroku.com/)**  

  **The PaaS pioneer** (launched 2007) — git-push deployments, add-ons marketplace, and excellent developer experience. **The reference point for modern PaaS** — now owned by Salesforce.



- **[Render](https://render.com/)**  

  **Modern Heroku alternative** — git-push deployments, managed databases, cron jobs, and background workers. **Free tier available** . **The best modern PaaS for startups** .



- **[Fly.io](https://fly.io/)**  

  **Edge-first PaaS** — deploy apps close to users with global distribution. **Free tier available** . **The best for latency-sensitive applications** .



- **[Railway](https://railway.app/)**  

  **Developer-first PaaS** with instant deployments, managed databases, and excellent DX. **Free tier available** . **The best for rapid prototyping** .



- **[DigitalOcean App Platform](https://www.digitalocean.com/products/app-platform)**  

  DigitalOcean's managed PaaS — simple, predictable pricing, and Git-based deployments. **Best for DigitalOcean ecosystem users** .



- **[Vercel](https://vercel.com/)**  

  **The frontend cloud** — built for Next.js and modern frontend frameworks with edge functions, preview deployments, and analytics. **Free tier generous** . **The standard for frontend deployments** .



- **[Platform.sh](https://platform.sh/)**  

  **Enterprise PaaS** with infrastructure-as-code, multi-cloud deployment, and strong DevOps workflows. **Best for enterprises** needing governance and compliance.



## Open-Source GitHub Projects



- **[Coolify](https://github.com/coollabsio/coolify)**  

  **The leading open-source self-hosted PaaS**, Apache-2.0 licensed with **40,000+ GitHub stars** . **A self-hostable alternative to Vercel, Heroku, Netlify, and Railway** — deploy any application to any server . **Supports Node.js, Python, PHP, Ruby, Go, Rust, and Dockerfiles** . Features **Git-based deployments, automatic SSL, databases (PostgreSQL, MySQL, MongoDB, Redis), and preview deployments** . **Runs on your own VPS** — $5/month server replaces $50/month PaaS bills . **The de facto open-source Vercel/Heroku alternative** — the most popular self-hosted PaaS .



- **[Dokku](https://github.com/dokku/dokku)**  

  **The smallest PaaS implementation** — a Docker-powered Heroku alternative in ~100 lines of bash . MIT licensed with **30,000+ GitHub stars** . **Git-push deployments** — `git push dokku main` deploys your app . **Buildpacks and Dockerfile support** . **Runs on any VPS** — minimal resource usage . **The classic lightweight self-hosted PaaS** — used by thousands of developers . **Best for developers wanting Heroku-like simplicity on their own server** .



- **[CapRover](https://github.com/caprover/caprover)**  

  **Easy-to-use app/database deployment platform**, Apache-2.0 licensed with **13,000+ GitHub stars** . **One-click apps for WordPress, MongoDB, MySQL, and 100+ others** . **Web GUI for management** — no command line required . **Runs on your VPS** — Docker Swarm-based . **The most user-friendly self-hosted PaaS** . **Best for users wanting a Heroku-like GUI experience** .



- **[Dokploy](https://github.com/Dokploy/dokploy)**  

  **Modern open-source PaaS** — "Vercel alternative, but open source" . Apache-2.0 licensed . **Supports Node.js, Python, PHP, Go, and Docker** with **Git-based deployments, preview deployments, and automatic SSL** . **Beautiful modern UI** — the most polished self-hosted PaaS interface . **Best for users wanting modern UX with self-hosting** .



- **[Kamal (formerly MRSK)](https://github.com/basecamp/kamal)**  

  **Deploy web apps anywhere from bare metal to cloud VMs**, MIT licensed with **12,000+ GitHub stars** . **No Kubernetes, no PaaS** — Docker containers over SSH . **Zero-downtime deployments, rolling restarts, and health checks** . **The simplest deployment tool** — used by Basecamp and HEY . **Best for teams wanting container deployments without orchestration complexity** .



- **[Tsuru](https://github.com/tsuru/tsuru)**  

  **Open-source, extensible PaaS** built on Docker and Kubernetes . Apache-2.0 licensed . **Supports multiple languages and frameworks** — Go, Python, Node.js, Ruby, PHP . **Self-hosted with strong multi-tenancy** . **Best for organizations needing enterprise-grade self-hosted PaaS** .



- **[OpenShift](https://github.com/openshift/origin)**  

  **Red Hat's Kubernetes distribution with developer-friendly PaaS features**, Apache-2.0 licensed . **Source-to-image builds, CI/CD pipelines, and integrated monitoring** . **The enterprise Kubernetes standard** — OpenShift Container Platform is the commercial version . **Best for enterprises needing Kubernetes with PaaS simplicity** .



- **[Rancher](https://github.com/rancher/rancher)**  

  **Complete Kubernetes management platform**, Apache-2.0 licensed with **24,000+ GitHub stars** . **Deploy and manage Kubernetes clusters anywhere** — on-premises, cloud, or edge . **The most widely adopted Kubernetes management platform** . **Best for organizations running multiple Kubernetes clusters** .



- **[Dokku](https://github.com/dokku/dokku)** — Already listed. **The smallest PaaS implementation** .



- **[Nanobox](https://github.com/nanobox-io/nanobox)**  

  **Micro PaaS for local development and production** (archived 2019) . **Historically significant** — the original "micro PaaS" concept . **Best for understanding PaaS architecture** .



- **[Flynn](https://github.com/flynn/flynn)**  

  **Open-source PaaS** (archived 2022) . **The most ambitious open-source PaaS** — built on Docker with Heroku-like workflows . **Historically significant** but no longer maintained . **Best for historical reference** .



- **[Deis Workflow](https://github.com/deis/workflow)**  

  **Open-source PaaS on Kubernetes** (archived 2018) . **Predecessor to Helm** — historically significant . **Best for historical reference** .



- **[Kubero](https://github.com/kubero-dev/kubero)**  

  **Free self-hosted PaaS on Kubernetes**, MIT licensed . **Heroku-like workflows with Git-based deployments** . **The simplest Kubernetes-based PaaS** . **Best for Kubernetes users wanting PaaS simplicity** .



- **[KubeVela](https://github.com/kubevela/kubevela)**  

  **Modern application delivery platform on Kubernetes**, Apache-2.0 licensed . **Application-centric abstraction over Kubernetes** . **Best for platform teams wanting Kubernetes abstraction** .



- **[Devtron](https://github.com/devtron-labs/devtron)**  

  **Open-source software delivery platform for Kubernetes**, Apache-2.0 licensed . **No-code CI/CD, GitOps, and security scanning** . **Best for teams wanting an integrated Kubernetes platform** .



### Additional Strong Open-Source Options



- **Piku** — Lightweight PaaS for your own server, ~200 lines of Python .

- **Empire** — Control plane for running Heroku-like containers on ECS .

- **Convox** — Open-source PaaS for AWS (commercial now) .

- **Deployer** — PHP deployment tool .

- **Mina** — Fast deployer for Ruby .

- **Capistrano** — Remote server automation and deployment .

- **Flightcontrol** — AWS-focused PaaS (commercial) .

- **Sturdy** — Open-source PaaS with on-premises option .

- **PaaS Cloud (various)** — Multiple lightweight PaaS implementations .



**Frameworks for building custom PaaS solutions**: Combine **Coolify** for the most feature-complete self-hosted PaaS with Git-based deployments and managed databases . Use **Dokku** for lightweight Heroku-like deployments in minimal bash . Choose **CapRover** for GUI-driven PaaS with one-click apps . Deploy **Dokploy** for modern UX with preview deployments . Use **Kamal** for Docker deployments over SSH without orchestration complexity . For Kubernetes-based PaaS, **Kubero** or **KubeVela** provide abstraction over Kubernetes . For enterprise Kubernetes management, **Rancher** or **OpenShift** provide comprehensive platforms . Note that true commercial PaaS with managed infrastructure, global CDNs, and vendor-supported SLAs (Vercel, Render, Heroku) remains primarily commercial territory; open-source stacks provide strong self-hosted deployment, scaling, and management foundations that require infrastructure responsibility.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- PaaS platforms handle application code, secrets, and user data. Self-hosted solutions require proper security hardening, access controls, backup procedures, and infrastructure management.

- **Self-hosted PaaS requires server administration** — patching, monitoring, backups, and scaling are your responsibility. Coolify and Dokku simplify deployment but not infrastructure management .

- **Some projects are archived** — Flynn, Deis Workflow, and Nanobox are no longer maintained . Verify activity before committing.

- **Kubernetes-based PaaS adds complexity** — Kubero and KubeVela require Kubernetes knowledge. For simpler needs, Dokku, CapRover, or Kamal are better choices .

- The open-source ecosystem provides strong self-hosted deployment, scaling, and management foundations, but **managed infrastructure, global CDNs, and vendor-supported SLAs** remain primarily commercial offerings.



---



**Made for developers, platform engineers, and organizations seeking PaaS sovereignty.**  

Let's make platform as a service more open, transparent, and accessible.
