# SENSEI ASKIA'S TERMUX ACADEMY — LEARNING JOURNEY

**Archive date:** 2026-11-24  
**Source repo:** Askiaasfar/termux-learning  
**Environment:** Android phone running Termux; Python; Git/GitHub.

## 1. Learning approach
The learner wanted practical, step-by-step cybersecurity and Linux education, using Android Termux as a learning environment. Teach the purpose of each command, explain its output, let the learner run it, then interpret results. Do not dump advanced commands without context. Keep exercises legal, controlled and beginner-friendly.

## 2. Verified timeline

### 2026-08-31 — Python foundations and GitHub workflow
The learner practised:
- `print()` for output.
- `input()` for user input.
- Variables.
- `int()` conversion.
- Arithmetic.
- `if/else`.
- Comparisons.
- Logical `and`.
- A simple age-based access decision (age 20 granted; age 14 denied in the reported exercise).

A Termux project directory was used: `~/projects/termux-learning`.
GitHub repository: `Askiaasfar/termux-learning`.
An SSH Git workflow was reported completed, with historical commit `1faa65b` and a clean working tree. Treat this as a past milestone; recheck current repo state before relying on it.

### 2026-09-02 — Python web server and Cloudflared tunnel
The learner practised a Python HTTP server on port 8080 in Termux and a Cloudflared quick tunnel using Cloudflared 2026.8.3.
Reported result: successful HTTP 200 visits were logged.
Observed issue: the request logger showed `127.0.0.1` as the client rather than the remote visitor's address. This can occur when a local tunnel/proxy forwards the request; correct client-IP handling requires understanding trusted proxy headers and must not trust arbitrary spoofable headers.

### 2026-09-03 — Sensei Askia's Termux Academy, Lesson 1: Networking
The learner completed Lesson 1 after practising networking. Confirmed command topics:
- `pkg install` — install packages in Termux.
- `ip addr` / `ip -br addr` — inspect network interfaces and local addresses.
- `ip route` — inspect routes/default gateway.
- `curl ifconfig.me` — query public egress IP (subject to provider/network conditions).
- `ping` — basic reachability/latency checks.
- `nmap` — only scan owned or explicitly authorized networks/devices.
- `cloudflared` — temporary tunnel concepts.
- Python HTTP server and visit logging.

Lesson 2 options were proposed, not confirmed completed: Nmap deeper practice, SSH, Python mini-tools, or a legal reconnaissance/web-security lab.

## 3. Existing repository evidence
At the 2026-11-24 audit, the repository contained:
- `README.md` (minimal original placeholder before this documentation update).
- `python-test/hello.py`, printing:
  - “Hello from Sensei Askia 👑”
  - “Termux + Python + GitHub is working!”

The original Python file is a small test artifact, not evidence of an advanced tool or complete cybersecurity project. Preserve it.

## 4. Known issues / learning notes
- The Cloudflared tunnel and Python server returned HTTP 200, proving the basic request path worked.
- The visitor address logged as 127.0.0.1, likely due to local proxying. Do not blindly read `X-Forwarded-For` from untrusted clients. Only use forwarding headers from a known trusted proxy and understand the provider's documented behavior.
- Recheck Termux package state, Android background restrictions, network permissions and current Cloudflared binary/version before repeating the lab.

## 5. Not yet verified as completed
No retrieved evidence that the learner completed:
- Kali Linux installation or full Kali workflow.
- SSH server hardening.
- Advanced Nmap scanning or service enumeration.
- Wi-Fi cracking or password attacks.
- Exploitation, privilege escalation or persistence.
- Web application vulnerability exploitation.
- Malware development or reverse engineering.
- A formal CTF/lab pathway.
These must not be described as completed lessons. Future learning should use deliberately vulnerable local labs or authorized training targets.

## 6. Teaching rules
- Explain commands before execution, including expected output and safe scope.
- Prefer read-only discovery first.
- Use local loopback, the learner's own devices, intentionally vulnerable labs, or targets with explicit written permission.
- No scanning random public IPs, neighbours' Wi-Fi, school/work networks, or third-party systems.
- Do not provide instructions for credential theft, stealth, persistence, destructive activity or unauthorized access.
- When a command could change/delete data, explain the effect and obtain confirmation.
- Never request or store passwords, private keys or tokens in the repo.
