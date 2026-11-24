# SENSEI ASKIA'S TERMUX ACADEMY

A practical, beginner-friendly Linux, Termux, Python, networking and ethical cybersecurity learning log.

**Learner:** Sensei Askia  
**Repository:** https://github.com/Askiaasfar/termux-learning  
**Default branch:** main  
**Learning environment:** Android Termux; Python; Git/GitHub.  
**Safety rule:** Learn only on systems, networks and applications owned by the learner or where explicit permission has been granted.

## Start here
- [Learning journey and verified lesson log](docs/LEARNING_JOURNEY.md)
- [Curriculum and next lessons](docs/CURRICULUM.md)
- [Ethical hacking and lab safety](docs/ETHICAL_SECURITY_RULES.md)

## Current verified progress
- Python fundamentals: print, input, variables, integer conversion, arithmetic, if/else, comparisons and logical AND; tested simple age-based decisions.
- Git/GitHub workflow from Termux: SSH workflow and commit were reported completed on 2026-08-31; historical commit recorded as `1faa65b`.
- Networking lesson: package installation, local IP/interface inspection, default route, public IP lookup, ping, authorized Nmap use, temporary Cloudflared tunnels, and a Python HTTP server with request logging.
- On 2026-09-02, the learner reported successful HTTP 200 visits through a Cloudflared quick tunnel to a Termux Python server on port 8080. Logged client address appeared as 127.0.0.1 rather than the visitor's public IP; this was a reverse-proxy/header interpretation issue to investigate, not evidence of visitor identity.

## Honest status
Only record a lesson as completed when there is conversation or exercise evidence. Later topics such as SSH server hardening, deeper Nmap, web security, Linux administration, shell scripting, defensive monitoring and CTF labs are proposed curriculum, not completed lessons unless separately verified.

Never store passwords, API keys, private IPs from sensitive environments, tokens, personal records or unauthorized target data in this public learning repository.