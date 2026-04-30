[![LinkedIn](https://img.shields.io/badge/LinkedIn-Kenneth%20Stillabower-blue?logo=linkedin)](https://www.linkedin.com/in/kjstillabower)
# KJ Stillabower

Infrastructure and security engineer building reliable, scalable SaaS platforms.

Infrastructure and security engineer building reliable, scalable SaaS platforms in multi-region, regulated environments where uptime, data integrity, and auditability are critical. I focus on making systems deterministic, observable, and recoverable through disciplined use of Terraform, CI/CD, and platform standards that eliminate drift and enable predictable operation at scale.

---

## Focus

- Terraform and GitOps-driven infrastructure
- Identity, access control, and Zero Trust patterns
- Multi-region, multi-cloud platform design (AWS, Azure)
- Observability, incident response, and SRE practices
- Security embedded into platform architecture (not layered after)

---

## Selected Work

> Representative personal work. Most production systems are built in private enterprise environments.
**[weather-alert-service](https://github.com/KJStillabower/weather-alert-service)**  
Event-driven weather alert system integrating external APIs with structured caching, failure handling, and user-facing notification workflows. Demonstrates API integration, data lifecycle management, and reliability patterns (TTL caching, graceful degradation, client-side resilience) in a lightweight PWA.

---

### Architecture Notes

- Multi-cloud identity boundary enforcement
- Zero Trust patterns for service-to-service communication
- Terraform state management and environment isolation
- Failure-mode driven design: recovery, rebuild, drift control

---

### Constraints

Most work is performed within private SaaS and regulated environments.  
Public repositories are limited, but reflect core approaches to:

- Platform standardization
- Infrastructure automation
- Security and reliability engineering

---

### Approach

Build systems that are:

- Deterministic (no hidden state)
- Observable (clear signals, actionable telemetry)
- Recoverable (tested, repeatable rebuild paths)
- Operable (engineers can use and extend without friction)
