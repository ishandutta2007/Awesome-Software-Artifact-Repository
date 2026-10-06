# Awesome-Software-Artifact-Repository

# Top Software Artifact Repository Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Package Registries, Artifact Management & Self-Hosted Repositories*  
**Last updated: October 2026**

This repository tracks notable **commercial artifact repository platforms** and **open-source projects** that store, version, and distribute software packages and build artifacts. These tools manage dependencies across languages and formats — from npm and PyPI to Docker images and Maven artifacts.

**Examples** include AWS CodeArtifact, JFrog Artifactory, Sonatype Nexus, Cloudsmith, GitHub Packages, Azure Artifacts, Google Artifact Registry, ProGet, GitLab Package Registry, and Packagecloud (the category leaders).

**Open-source emphasis**: Artifact repository management is a strong open-source domain. **Nexus Repository OSS** and **Artifactory OSS** lead as the veteran self-hosted options. **Artipie** brings a modern universal registry, while **Verdaccio**, **Devpi**, **BaGet**, and **Pulp** provide language-specific solutions. **Apache Archiva** handles Java artifacts, and **S3-backed repositories** enable serverless artifact hosting. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[JFrog Artifactory](https://jfrog.com/artifactory/)**  
  **The enterprise standard for artifact management** — universal repository supporting 30+ package types including Maven, npm, PyPI, Docker, NuGet, and Go . **Best for large enterprises** needing comprehensive artifact management with security scanning.

- **[Sonatype Nexus Repository](https://www.sonatype.com/products/nexus-repository)**  
  **The most widely deployed artifact repository** — supports Maven, npm, NuGet, PyPI, Docker, and more. **The reference for Java/JVM artifact management** .

- **[AWS CodeArtifact](https://aws.amazon.com/codeartifact/)**  
  **AWS's managed artifact repository** — supports npm, PyPI, Maven, NuGet, and Swift . **Best for AWS-native teams** .

- **[GitHub Packages](https://github.com/features/packages)**  
  **Package hosting integrated with GitHub** — npm, Docker, Maven, NuGet, RubyGems . **Free tier available** . **Best for GitHub-centric teams** .

- **[Azure Artifacts](https://azure.microsoft.com/en-us/products/devops/artifacts/)**  
  **Microsoft's artifact repository** — npm, NuGet, Maven, PyPI, and Universal Packages . **Best for Azure DevOps users** .

- **[Google Artifact Registry](https://cloud.google.com/artifact-registry)**  
  **Google's universal artifact repository** — Docker, Maven, npm, Python, Go, and apt/yum . **Best for Google Cloud users** .

- **[Cloudsmith](https://cloudsmith.com/)**  
  **Cloud-native artifact management** — 25+ package formats with global CDN . **Free tier available** . **Best for multi-format artifact hosting** .

- **[ProGet](https://inedo.com/proget)**  
  **Universal package manager for Windows** — NuGet, npm, PyPI, Maven, Docker, and more . **Best for Windows-centric .NET teams** .

- **[GitLab Package Registry](https://docs.gitlab.com/ee/user/packages/)**  
  **Package hosting integrated with GitLab** — npm, Maven, NuGet, PyPI, Composer, and more . **Best for GitLab users** .

- **[Packagecloud](https://packagecloud.io/)**  
  **Hosted package repository** — apt, yum, RubyGems, npm, and Python . **Best for Linux distribution packages** .

## Open-Source GitHub Projects

### Universal Artifact Repositories

- **[Nexus Repository OSS](https://github.com/sonatype/nexus-public)**  
  **The most widely deployed open-source artifact repository**, EPL-1.0 licensed . **Supports Maven, npm, NuGet, PyPI, Docker, RubyGems, Go, and more** . **The enterprise standard** — mature, feature-rich, and widely documented . **Best for enterprises needing a proven artifact repository** .

- **[JFrog Artifactory OSS](https://github.com/jfrog/artifactory-oss)**  
  **Open-source version of JFrog Artifactory** (limited to OSS languages), Apache-2.0 licensed . **Supports Maven, Gradle, npm, PyPI, NuGet, Docker, and more** . **Best for teams wanting a lighter Artifactory experience** .

- **[Artipie](https://github.com/artipie/artipie)**  
  **Open-source, self-hosted universal artifact registry**, MIT licensed . **Supports Maven, npm, PyPI, Docker, NuGet, RubyGems, Go, Helm, Debian, RPM, and more** — one binary for all package types . **The most comprehensive modern open-source artifact registry** — lightweight, fast, and container-friendly . **Best for organizations wanting a single self-hosted registry for all languages** .

- **[Pulp](https://github.com/pulp/pulp)**  
  **Open-source repository management platform**, GPL-2.0 licensed . **Supports RPM, Debian, Python, Ansible, and container content** . **The standard for Linux distribution package management** . **Best for Linux distribution maintainers** .

- **[Apache Archiva](https://github.com/apache/archiva)**  
  **Open-source repository management for Java artifacts**, Apache-2.0 licensed . **Maven, Gradle, and Ivy support** . **Best for Java-centric organizations** .

- **[Reposilite](https://github.com/dzikoysk/reposilite)**  
  **Lightweight and easy-to-use Maven repository**, Apache-2.0 licensed . **Self-hosted with minimal configuration** . **Best for simple Maven artifact hosting** .

- **[Strongbox](https://github.com/strongbox/strongbox)**  
  **Open-source artifact repository manager**, Apache-2.0 licensed . **Maven, npm, NuGet, PyPI, and Docker support** . **Best for Java-centric artifact management** .

### Language-Specific Repositories

- **[Verdaccio](https://github.com/verdaccio/verdaccio)**  
  **Lightweight private npm registry**, MIT licensed with **16,000+ GitHub stars** . **Self-hosted npm proxy and private registry** — cache public packages and host private ones . **The best open-source npm registry** — zero-config, Docker-friendly . **Best for Node.js teams wanting private npm** .

- **[Devpi](https://github.com/devpi/devpi)**  
  **Python package server and private PyPI**, MIT licensed . **Self-hosted PyPI proxy and private index** . **The standard for private Python packages** . **Best for Python teams wanting private PyPI** .

- **[BaGet](https://github.com/loic-sharma/BaGet)**  
  **Lightweight NuGet server**, MIT licensed with **1,500+ GitHub stars** . **Self-hosted NuGet registry** — simple, fast, and .NET-native . **The best open-source NuGet server** . **Best for .NET teams wanting private NuGet** .

- **[Sleet](https://github.com/emgarten/Sleet)**  
  **Static NuGet package feed generator**, MIT licensed . **Creates static NuGet feeds from packages** — no server required, host on S3/Azure . **Best for serverless NuGet hosting** .

- **[ProGet (Free Edition)](https://github.com/inedo/proget)**  
  **Universal package manager for Windows** (open-core), Apache-2.0 licensed . **Supports NuGet, npm, PyPI, Maven, Docker, and more** . **Best for Windows-centric .NET teams** .

- **[Docker Registry](https://github.com/distribution/distribution)**  
  **The reference implementation of the Docker Registry**, Apache-2.0 licensed . **Self-hosted Docker image registry** . **Best for container image hosting** .

- **[Harbor](https://github.com/goharbor/harbor)**  
  **Cloud-native container registry with security and governance**, Apache-2.0 licensed with **25,000+ GitHub stars** . **Vulnerability scanning, RBAC, and replication** . **Best for enterprise container registries** .

- **[Quay](https://github.com/quay/quay)**  
  **Red Hat's container registry**, Apache-2.0 licensed . **Security scanning and geo-replication** . **Best for enterprise container registries** .

### Cloud-Native & S3-Backed

- **[S3-backed Repositories (AWS)**](https://aws.amazon.com/)  
  **Serverless artifact hosting on S3** — no server required, pay only for storage . **Best for cost-effective artifact hosting** .

- **[GitHub Packages (Self-Hosted Alternatives)**](https://github.com/)  
  **Self-hosted alternatives to GitHub Packages** — including Gitea, Forgejo package registries . **Best for self-hosted Git with package hosting** .

### Additional Strong Open-Source Options

- **Ceph** — Distributed storage for artifact repositories at scale .
- **MinIO** — S3-compatible object storage for artifact backends .
- **SeaweedFS** — Distributed file system for artifact storage .
- **IPFS** — Decentralized artifact storage (experimental) .
- **ORAS** — OCI Registry as Storage for arbitrary artifacts .
- **zot** — OCI-native container registry .
- **Distribution** — Docker Registry reference implementation .

**Frameworks for building custom artifact repository solutions**: Combine **Nexus Repository OSS** for proven enterprise artifact management . Use **Artipie** for a modern universal registry supporting all major package types . Deploy **Verdaccio** for private npm, **Devpi** for private PyPI, or **BaGet** for private NuGet . Choose **Harbor** for enterprise container registries . Use **Pulp** for Linux distribution packages . Integrate **S3** or **MinIO** for serverless artifact storage . Note that true enterprise artifact management with high availability, security scanning, and vendor-supported SLAs (JFrog Artifactory Pro, Cloudsmith, Nexus Pro) remains primarily commercial territory; open-source stacks provide strong self-hosted registry, proxy, and caching foundations that require infrastructure responsibility.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Artifact repositories store and distribute software packages that may contain malicious code. **Supply chain attacks are a real threat** — verify package sources, use signed artifacts, and scan dependencies for vulnerabilities .
- **Public registries are not curated for security** — npm, PyPI, and NuGet have all experienced malicious package incidents. Use private registries with security scanning for production .
- **Self-hosted repositories require infrastructure** — storage, backup, high availability, and security are your responsibility. Nexus and Artifactory OSS are mature but require operational expertise .
- **License considerations**: Nexus Repository OSS uses EPL-1.0, Artifactory OSS uses Apache-2.0 with feature limitations, and Pulp uses GPL-2.0. Verify licensing against your use case .
- The open-source ecosystem provides strong self-hosted registry, proxy, and caching foundations, but **high availability, security scanning, and vendor-supported SLAs** remain primarily commercial offerings.

---

**Made for DevOps engineers, platform teams, and organizations seeking artifact repository sovereignty.**  
Let's make software artifact repositories more open, transparent, and secure.
