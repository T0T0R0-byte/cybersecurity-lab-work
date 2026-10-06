# Cyber Security Lab Work: offensive security practicals

![Focus: Offensive Security](https://img.shields.io/badge/Focus-Offensive%20Security-informationall)
![Platform: Ubuntu](https://img.shields.io/badge/Platform-Ubuntu-E95420)
![License: MIT](https://img.shields.io/badge/License-MIT-green)

Write-ups and evidence from practical cyber security coursework (Level 5, module COMP50003: I built a
deliberately vulnerable Ubuntu VM, then attacked it in phases and documented each step with
screenshots taken as I worked.

Everything here is against a box I configured myself, on a host-only lab network. No client systems,
no third-party targets.

## The phases

| Write-up | Covers | Screenshots |
|---|---|---|
| [Phase 1: Web Application Exploitation](docs/01-web-application-exploitation.md) | Vulnerable web app on the lab box, exploited with request/response evidence at each step | 77 |
| [Phase 2: Cryptography](docs/02-cryptography.md) | Cryptography challenges from the same exercise | 20 |
| [Phase 3: Privilege Escalation](docs/03-privilege-escalation.md) | Low-privileged `employee` account to root: sudo misconfiguration and an insecure SUID binary | 18 |
| [Phase 4 and 5: Network Exploitation and Forensics](docs/04-network-and-forensics.md) | Network-level exploitation, then the forensic examination of what the activity left behind | 20 |

Each phase write-up is markdown with the screenshots embedded inline, in the order they were captured.

## Two things to be straight about

1. **Phase 2 is screenshots only.** The text write-up for that phase is an empty document in my
   archive, so the page is a captioned sequence of evidence rather than prose. Nothing has been
   invented to fill it in.
2. **There is no separate CTF write-up.** My archive had a file named `CTF_CB012653.docx`, but it is
   byte-for-byte identical to the Phase 1 document (same MD5), so it is a duplicate copy, not a
   second piece of work. It is not reproduced here.

Flags and credentials visible in the screenshots belong to that lab VM, which no longer exists.

## How it was done

- Target: Ubuntu VM, host-only networking, vulnerabilities configured by hand (misconfigured sudo,
  SUID binaries, a deliberately vulnerable web app, service misconfigurations).
- Each phase: set up the weakness, exploit it, capture the evidence, write it up.
- Evidence: inline screenshots taken during the work, plus the commands and outputs in the text.

## Credits

Solo work: **Faraj Farook** (CB012653).

## License

MIT, see [LICENSE](LICENSE).
