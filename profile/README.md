## Brickell Technologies

Brickell Technologies, LLC is an offensive security firm based in Miami, Florida. We test networks, applications, APIs, mobile apps and cloud environments by hand, and the people who scope an engagement are the same people who do the testing. Clients get the attack path, the evidence behind it, and a retest once the fixes ship.

### What we do

- **Penetration testing.** Network, web application, API, mobile and internal testing, done manually.
- **Vulnerability assessments.** Full-estate scanning followed by a human review that removes false positives and ranks what's left by what an attacker would actually reach first.
- **Endpoint security.** CrowdStrike Falcon deployment, policy tuning and legacy antivirus migration. We're a CrowdStrike partner.
- **Cloud security.** AWS, Azure, GCP and Kubernetes reviews that follow IAM privilege-escalation paths instead of stopping at a benchmark score.
- **CI/CD and pipeline security.** Testing what a pull request can make your build system do, then hardening it.
- **AI and LLM security testing.** Prompt injection, tool abuse and cross-tenant retrieval leaks in LLM features, agents and RAG systems.
- **Compliance readiness.** Gap assessments and testing evidence for SOC 2, HIPAA, PCI DSS, CMMC and NIST 800-171. Readiness only; we don't audit our own work.

### Research

We look for vulnerabilities in widely used open-source software, report them privately to the maintainers, and publish a write-up once a fix is available.

| CVE | Project | Severity | Write-up |
|---|---|---|---|
| CVE-2026-110720 | HashiCorp consul-k8s | Critical | [A ServiceAccount name was enough to become Consul admin](https://brickell-tech.com/blog/consul-k8s-cross-namespace-acl-bypass-cve-2026-110720) |
| FZ-2026-008 (no CVE) | Firezone | Not scored | [Firezone Gateways trusted the proxy IPs Clients sent them](https://brickell-tech.com/blog/firezone-gateway-proxy-ip-bypass-fz-2026-008) |
| CVE-2026-114615 | Authlib | High | [Off by one newline: how Authlib's JWT algorithm confusion came back](https://brickell-tech.com/blog/authlib-algorithm-confusion-incomplete-fix-cve-2026-114615) |
| CVE-2026-105937 | Apache Pulsar | High | [Reading another tenant's messages through an Apache Pulsar shadow topic](https://brickell-tech.com/blog/apache-pulsar-shadow-topic-cross-tenant-cve-2026-105937) |
| CVE-2026-112947 | Vite | Medium | [Reading past Vite's server.fs boundary through a WebAssembly error](https://brickell-tech.com/blog/vite-wasm-instance-fs-bypass-cve-2026-112947) |
| CVE-2026-110779, CVE-2026-110780 | Netatalk | Medium | [Two memory-safety bugs in Netatalk's Spotlight RPC](https://brickell-tech.com/blog/netatalk-spotlight-cve-2026-110779-cve-2026-110780) |
| CVE-2026-96615 | NGINX Gateway Fabric | High | [Cross-namespace agent impersonation in NGINX Gateway Fabric](https://brickell-tech.com/blog/nginx-gateway-fabric-agent-impersonation-cve-2026-96615) |
| CVE-2026-85184 | @fastify/middie | Critical | [When your router and your middleware read different URLs](https://brickell-tech.com/blog/fastify-middie-auth-bypass-cve-2026-85184) |
| CVE-2026-41992 | GNU gzip | Medium | [The gzip patch that fixed the crash and left the bug](https://brickell-tech.com/blog/gzip-incomplete-patch-cve-2026-41992) |

We also write for the people buying security work:

- [Does SOC 2 require a penetration test?](https://brickell-tech.com/blog/does-soc-2-require-a-penetration-test)
- [How much does a penetration test cost?](https://brickell-tech.com/blog/how-much-does-a-penetration-test-cost)

Everything we publish is on the [Brickell Technologies blog](https://brickell-tech.com/blog).

### Certifications

GXPN, GMOB, CSAP, CySA+, Security+, CEH, eCPPT and eJPT.

### Get in touch

We work on site across Miami, Fort Lauderdale and West Palm Beach, and remotely worldwide.

- Website: [brickell-tech.com](https://brickell-tech.com)
- Email: [contact@brickell-tech.com](mailto:contact@brickell-tech.com)
- Start a conversation: [brickell-tech.com/contact](https://brickell-tech.com/contact)
