# ETHICAL CYBERSECURITY AND LAB SAFETY

This repository supports lawful learning, defensive security and authorized testing only.

## Allowed learning scope
- The learner's own Android phone, Termux environment, laptop and home lab.
- Localhost/loopback services.
- Devices and networks owned by the learner.
- Training platforms and intentionally vulnerable labs whose rules explicitly permit testing.
- Third-party systems only with explicit authorization and defined scope.

## Never target without permission
- Random public IP addresses or websites.
- Neighbours' Wi-Fi or other people's routers.
- School, employer, government or public networks.
- Other people's accounts, devices or data.

## Safe operating principles
- Confirm target ownership and scope before a scan.
- Start with read-only inspection.
- Avoid destructive tests, denial-of-service, credential attacks, persistence, stealth or data exfiltration.
- Do not bypass authentication or access controls on real services.
- Do not store credentials, tokens, private keys or personal data in this repository.
- Stop if testing unexpectedly reaches a third-party system or exposes real user data.
- Record findings responsibly and privately.

## Proxy/client IP lesson
When a Python server sits behind Cloudflared or another proxy, the socket peer may appear as 127.0.0.1 or another local proxy address. Forwarding headers can describe the original client only when supplied by a trusted proxy. A client can forge ordinary headers if the application trusts them directly. Never use an untrusted header as proof of identity or for access control.

## Commands that can change the system
Explain effects before running commands such as rm, chmod recursively, package removal, firewall changes, service exposure or disk operations. Confirm backups and target paths.
