# Footprinting & Reconnaissance Labs

**Hands-on cybersecurity practice with Kali Linux**

This repository documents a practical learning exercise exploring common footprinting and reconnaissance utilities. The captured exercise used `networkwalks.com` as the example domain.

> **Authorization note:** Only perform active checks against systems you own or have explicit permission to assess. If you do not have permission to publish findings about the example domain, replace the domain and remove identifying output before making this repository public.

## Objectives

- Understand domain registration and DNS information.
- Identify publicly observable web technologies.
- Inspect HTTP response headers.
- Learn how WAF fingerprinting tools report their findings.
- Record observations accurately and distinguish tool output from conclusions.

## Lab environment

- OS: Kali Linux
- Virtualization: Oracle VirtualBox
- Documentation: Markdown
- Evidence: terminal screenshots in `screenshots/`

## Tools explored

| Tool | Purpose | Lab |
|---|---|---|
| WHOIS | Domain registration lookup | [WHOIS](labs/01-whois.md) |
| WhatWeb | Website technology fingerprinting | [WhatWeb](labs/02-whatweb.md) |
| nslookup | DNS name resolution | [NSLookup](labs/03-nslookup.md) |
| cURL | HTTP response headers (`-I`) | [cURL](labs/04-curl.md) |
| WAFW00F | Web Application Firewall fingerprinting | [WAFW00F](labs/05-wafw00f.md) |
| DNSRecon | DNS record enumeration | [DNSRecon](labs/06-dnsrecon.md) |

## Repository structure

```text
footprinting-and-reconnaissance-labs/
├── README.md
├── labs/
│   ├── 01-whois.md
│   ├── 02-whatweb.md
│   ├── 03-nslookup.md
│   ├── 04-curl.md
│   ├── 05-wafw00f.md
│   └── 06-dnsrecon.md
└── screenshots/
    ├── whois.jpg
    ├── whatweb.jpg
    ├── nslookup.jpg
    ├── curl-headers.jpg
    ├── wafw00f.jpg
    └── dnsrecon.jpg
```

## Key learning

Reconnaissance tools expose different kinds of information. WHOIS focuses on registration data, DNS utilities reveal name-resolution and DNS records, WhatWeb identifies observable web technologies, cURL inspects HTTP responses, and WAFW00F attempts to identify a web application firewall.

## Progress

This is an ongoing learning repository. New labs will be added as I practice, verify results, and improve my documentation.

---
*Learning by doing. Documenting findings. Building practical cybersecurity skills.*
