# TryHackMe Writeups 📝

> Personal writeups for TryHackMe rooms — covering enumeration, exploitation, and privilege escalation techniques.

[![TryHackMe](https://img.shields.io/badge/TryHackMe-kalialucard-212C42?logo=tryhackme)](https://tryhackme.com/p/kalialucard)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## What This Is

A growing collection of step-by-step walkthroughs for TryHackMe rooms. Each writeup documents the full attack chain: recon → enumeration → exploitation → privilege escalation → flags.

> **Responsible Disclosure:** These writeups are for educational purposes only. All machines are intentionally vulnerable lab environments provided by TryHackMe.

## Rooms Covered

| Room | Key Techniques |
|------|---------------|
| [0day](0day.md) | Apache Shellshock, kernel exploit |
| [Agent Sudo](Agent%20Sudo.md) | User-agent enumeration, steganography, CVE sudo bypass |
| [Anonforce](Anonforce.md) | FTP anonymous login, PGP key cracking |
| [Anonymous](Anonymous.md) | SMB enumeration, SUID abuse |
| [Archangel](Archangel.md) | LFI, log poisoning, cron privesc |
| [Basic Pentesting](Basic%20Pentesting.md) | SMB, SSH brute force, weak credentials |
| [Crack the Hash](Crack%20the%20hash.md) | Hash identification, hashcat, john |
| [CyberLens](CyberLens.md) | Apache Tika RCE, Windows privesc |
| [Cyberheroes](Cyberheroes.md) | Source code review, credential exposure |
| [Dig Dug](Dig%20Dug.md) | DNS enumeration, zone transfers |
| [Ghostcat](Ghostcat.md) | CVE-2020-1938, AJP connector exploit |
| [Hack Smarter Security](Hack%20Smarter%20Security.md) | Windows AD, OSCP-style chain |
| [Ignite](Ignite.md) | Fuel CMS RCE, default credentials |
| [Library](Library.md) | Python library hijacking |
| [Mindgames](Mindgames.md) | Brainfuck decode, OpenSSL privesc |
| [Mr Robot CTF](Mr%20Robot%20CTF.md) | WordPress, hydra, nmap, SUID |
| [Mustacchio](Mustacchio.md) | XXE injection, SUID privesc |
| [Plotted-TMS](Plotted-TMS.md) | SQLi, cron job abuse |
| [Poster](Poster.md) | PostgreSQL RCE, SUID |
| _…and more_ | |

## Tools Used

`nmap` · `gobuster` · `hydra` · `john` / `hashcat` · `netcat` · `burpsuite` · `metasploit` · `linpeas` · `pwncat`

## Screenshot

<!-- TODO: add a sample terminal output screenshot here -->
![Sample writeup](docs/screenshot.png)

## License

[MIT](LICENSE) © kalialucard
