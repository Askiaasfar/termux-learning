# TERMUX / LINUX / ETHICAL CYBERSECURITY CURRICULUM

This is a proposed learning plan. The verified lesson log in LEARNING_JOURNEY.md determines what has already been completed.

## Completed foundations (verified from prior lessons)
1. Python basics: output, input, variables, conversion, arithmetic, conditions, comparisons and logical AND.
2. Termux package installation and basic Linux/network commands.
3. IP/interface and route inspection.
4. Ping and public egress IP lookup.
5. Basic Python HTTP server on port 8080.
6. Cloudflared quick tunnel and HTTP 200 request logging.
7. Git/GitHub SSH workflow from Termux (historical completion reported).

## Suggested next modules — NOT YET COMPLETED
### Module 2 — Linux shell foundations
- Navigation: pwd, ls, cd.
- Files: touch, mkdir, cp, mv, cat, less, head, tail.
- Search: grep, find.
- Permissions: chmod, chown concepts, umask.
- Processes: ps, top, kill (safe process ownership only).
- Storage: df, du.
- Package management and repository updates.
- Paths, environment variables and shell quoting.

### Module 3 — Python mini-tools
- Loops, functions, lists, dictionaries and exceptions.
- Read/write files safely.
- Parse HTTP logs and summarize status codes.
- Build a local-only log analyzer and simple network information report.
- Use virtual environments and pip safely.
- Unit tests and Git commits.

### Module 4 — Networking fundamentals
- IPv4, subnet masks/CIDR, private/public addresses.
- DNS, DHCP, NAT, routing, TCP vs UDP.
- Ports, sockets, HTTP/HTTPS, TLS basics.
- Local interface and route interpretation.
- Packet capture concepts using a permitted lab environment.
- Understand reverse proxies and trusted forwarding headers.

### Module 5 — Nmap in an authorized lab
- Discover the learner's own lab hosts.
- Explain host discovery, TCP connect scans, port states and service detection.
- Scan only loopback, owned devices or a specifically authorized lab subnet.
- Interpret output and document scope.
- Do not use stealth/evasion or scan arbitrary internet hosts.

### Module 6 — SSH and secure administration
- SSH client basics.
- Key-based authentication for systems the learner owns.
- Host-key verification.
- Least privilege, updates, firewall basics and secure file transfer.
- Never expose SSH publicly without understanding hardening and access controls.

### Module 7 — Web security foundations
- HTTP requests/responses, headers, cookies, sessions and same-origin policy.
- OWASP Top 10 concepts.
- Safe local vulnerable applications or purpose-built labs.
- Input validation, authentication, authorization, CSRF, XSS and SQL injection concepts.
- Practice fixes and defensive verification, not attacking real sites.

### Module 8 — Defensive monitoring
- Log reading, timestamps, request IDs and status codes.
- Basic incident triage.
- File integrity and backups.
- Secure configuration and secret handling.
- Rate limits and audit trails.

### Module 9 — Legal CTF and lab practice
- Use intentionally vulnerable local containers or reputable training platforms with explicit authorization.
- Keep a lab notebook: objective, scope, commands, observations, fix, evidence.
- No real-world targets without written permission.

## Lesson format
For each lesson:
1. Learning objective.
2. Concept explanation.
3. Safe lab scope.
4. Commands and expected output.
5. Learner executes and shares results.
6. Troubleshoot.
7. Short challenge.
8. Record completion only after evidence.
