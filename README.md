# Victor T. Chevalier

Senior Manager, Software Engineering — Cybersecurity at Stratascale (SHI), leading engineering for Vector0, a Continuous Threat Exposure Management platform. Twenty years building enterprise software, security platforms, and developer infrastructure, across commercial, telecom, and classified systems. I lead engineering while remaining hands-on with architecture, code review, and prototyping.

Current open-source work focuses on local AI infrastructure, developer tooling, and engineering automation.

## Current work

Vector0 gives analysts a unified view of external and internal attack surface by combining discovery with third-party security tooling. I took ownership after the acquisition and led the rebuild of the data backend, replacing the previous design with a graph database over Postgres on Ent/Go that is easier to extend. The plugin framework that came out of it takes new vendor integrations from quarters to days.

Two earlier roles at Stratascale led here: Product Manager for the Attack Surface Validation platform, where I owned product direction and prototyped in code, and Automations Manager, where I owned the security automation function and shipped 30+ production workflows.

## Earlier

**AT&T — Principal Cybersecurity, 2010–2022.** Principal-level IC across U-verse, DirecTV, HBO/Time Warner, and the home networking portfolio — set-top boxes, media delivery, and Wi-Fi routers shipped to millions of subscribers. Co-authored the AT&T Security Policy and Requirements, the company-wide standard every business unit adhered to. Built custom fuzzers in Python to find defects in firmware, network protocols, and embedded devices before they reached customers.

**General Dynamics C4 Systems — Software Architect, 2007–2010; Software Engineer, 2004–2006.** Multi-Level Security products on Trusted Solaris for U.S. Intelligence Community customers under a TS/SCI clearance to DCID 6/3. Led the ground-up rebuild of GD's abstract MLS library, the multi-threaded foundation that let other teams write MLS-aware applications without deep Trusted Solaris expertise, and which became the backbone of both the Desktop Suite and the Web-Based MLS SOA Portal. Also built a PKI library in C++/OpenSSL handling encrypt/sign across classification levels.

## Engineering

These repositories are maintained end to end — architecture, implementation, tests, and packaging — and reflect the engineering practices I use day to day.

| Project | What it is |
|---|---|
| [ailocal](https://github.com/DevelopSolutionsLLC/ailocal) | Local model runtime for Apple Silicon. Python, standard library only, no runtime dependencies. Container lifecycle, an OpenAI- and Anthropic-compatible gateway, capability-based routing, hardware-derived configuration, and a regression gate that must pass before a release tag is cut. |
| [mycelium](https://github.com/DevelopSolutionsLLC/mycelium) | Go service mapping attack surface findings as a graph. Early. |
| [job-radar](https://github.com/DevelopSolutionsLLC/job-radar) | Pipeline that scans job portals and evaluates postings against a defined profile. |
| [monitorACL](https://github.com/DevelopSolutionsLLC/monitorACL) | C++ daemon fixing an Active Directory permission defect in QNAP shared groups. Signal handling, PID file, daemon mode. |
| [killswitch](https://github.com/DevelopSolutionsLLC/killswitch) | OpenVPN killswitch for Debian-family Linux, built on UFW and sysctl. |

## Technical

My current work is primarily Go and Python, building on earlier C, C++, and Java systems — containers, Postgres and graph databases, gRPC, and AWS underneath. Security work spans attack surface management, vulnerability research, MLS systems, and secure development practice. TS/SCI previously held, now inactive.

AI is one capability in that set. In `ailocal` it is the workload, not the engineering: the work is packaging, process supervision, container orchestration, and a test gate. On the team, it is tooling that speeds up architecture analysis, code generation, debugging, and operational automation.

## Contact

[vtchevalier.com](https://vtchevalier.com) · [LinkedIn](https://www.linkedin.com/in/vtchevalier/) · Austin / San Antonio, TX

Open to engineering leadership roles in cybersecurity, platform engineering, and developer infrastructure.
