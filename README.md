# Kenneth J. Stillabower

Infrastructure and security engineer focused on building reliable, scalable SaaS platforms.

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

> Representative implementations and reference patterns

- **weather-alert-service**  
  Event-driven weather alert system integrating NWS and external data sources with structured caching, failure handling, and user-facing notification workflows. Designed to demonstrate real-world API integration, data lifecycle management, and reliability patterns (TTL caching, graceful degradation, client-side resilience).


---

### Architecture Notes

- Multi-cloud identity boundary enforcement
- Zero Trust patterns for service-to-service communication
- Terraform state management and environment isolation
- Designing for failure: recovery, rebuild, and drift control

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
