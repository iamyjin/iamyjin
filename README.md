<div align="center">

  <!-- Header Banner -->
  <img src="https://raw.githubusercontent.com/iamyjin/iamyjin/main/assets/banner.svg" width="100%" alt="Eugene Banner" />

  <br /><br />

  <!-- Live Status Badges -->
  <a href="https://github.com/iamyjin">
    <img src="https://img.shields.io/badge/STATUS-OPEN_TO_ROLES-00F2FE?style=for-the-badge&logo=target&logoColor=black" alt="Status" />
  </a>
  <a href="https://github.com/iamyjin">
    <img src="https://img.shields.io/badge/FOCUS-CLOUD_%2B_AUTOMATION-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" alt="Focus" />
  </a>
  <a href="https://github.com/iamyjin">
    <img src="https://img.shields.io/badge/LOCATION-REMOTE_%2F_HYBRID-10B981?style=for-the-badge&logo=azure&logoColor=white" alt="Location" />
  </a>

  <br /><br />

  <!-- Title & Headline -->
  <h1><samp>Yauheni (Eugene)</samp></h1>
  <h3><code>DevOps & Reliability Engineer</code></h3>

  <p><i>Building self-healing cloud infrastructure, zero-downtime pipelines, and high-precision observability.</i></p>

  <br />

  <!-- Code / Terminal Window Widget -->
  <a href="https://github.com/iamyjin">
    <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=600&size=15&duration=2000&pause=1000&color=A78BFA&background=0D1117&center=true&vCenter=true&multiline=true&width=620&height=140&lines=resource+%22sre_engineer%22+%22eugene%22+%7B;+++cloud_provider+=+%22azure%22;+++orchestrator+++=+%22kubernetes%22;+++iac_tooling+++++=+%5B%22terraform%22,+%22ansible%22%5D;+++observability++=+%5B%22grafana%22,+%22loki%22,+%22elk%22%5D;%7D" alt="Terraform HCL Typing SVG" />
  </a>

</div>

<br />

<!-- Gradient Wave Divider -->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%" />

<br />

## ⚡ Deployment Pipeline & Ecosystem

```mermaid
graph LR
    subgraph CODE [Code & Microservices]
        A[Java / Spring Boot] --> B[Python / Nginx]
    end

    subgraph CICD [CI/CD Automation]
        B --> C{GitLab CI / GitHub Actions}
    end

    subgraph IAC [Infrastructure as Code]
        C --> D[Terraform & Terragrunt]
        D --> E[Ansible Config]
    end

    subgraph CLOUD [Runtime & Platform]
        E --> F[Azure AKS / Docker]
        F --> G[Kafka & RabbitMQ]
    end

    subgraph OBS [Observability]
        F --> H[Grafana / Prometheus]
        F --> I[ELK Stack & Loki]
    end

    style CODE fill:#161b22,stroke:#7B42BC,stroke-width:2px,color:#fff
    style CICD fill:#161b22,stroke:#00F2FE,stroke-width:2px,color:#fff
    style IAC fill:#161b22,stroke:#7B42BC,stroke-width:2px,color:#fff
    style CLOUD fill:#161b22,stroke:#3B82F6,stroke-width:2px,color:#fff
    style OBS fill:#161b22,stroke:#F59E0B,stroke-width:2px,color:#fff
