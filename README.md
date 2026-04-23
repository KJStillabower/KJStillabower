# Kenneth J. Stillabower

Infrastructure and security engineer building reliable, scalable SaaS platforms.

Most production work delivered in enterprise and regulated environments where systems and code are not publicly shareable. This profile contains representative projects and patterns that reflect how I design, build, and operate platforms.

---

## Focus

- Terraform and GitOps-driven infrastructure
- Identity, access control, and Zero Trust patterns
- Multi-region and multi-cloud platform design (AWS, Azure)
- Observability, incident response, and SRE practices
- Security embedded into platform architecture (not layered after)

---

## Selected Work

> Representative personal work. Most production systems are built in private enterprise environments.

**[weather-alert-service](https://github.com/KJStillabower/weather-alert-service)**  
Event-driven weather alert system integrating external APIs with structured caching, failure handling, and user-facing notification workflows. Demonstrates practical API integration, data lifecycle management, and reliability patterns including TTL-based caching, graceful degradation, and client-side resilience.

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
