# NETWORKWALKS-B083-WEEK-2-
# Week 2 Project – Network Reconnaissance

This repository contains the screenshots from my Week 2 network reconnaissance project.

## Project Overview

The project documents basic network and web reconnaissance activities performed in a Kali Linux environment and a local Nmap scan.

## Tools Used

- `whois`
- `WhatWeb`
- `nslookup`
- `curl`
- `WAFW00F`
- `dnsrecon`
- Nmap / Zenmap

## Activities Documented

### 1. WHOIS
A WHOIS query was performed for `networkwalks.com`.

### 2. Web Technology Enumeration
`WhatWeb` was used to identify technologies and HTTP-related information associated with `networkwalks.com`.

### 3. DNS Lookup
`nslookup` was used with Google DNS (`8.8.8.8`) to resolve the domain.

### 4. HTTP Header Inspection
`curl -i` was used to inspect the HTTP response headers from the website.

### 5. WAF Detection
`wafw00f` was used to check whether the website was behind a Web Application Firewall. The screenshot reports ModSecurity (SpiderLabs).

### 6. DNS Enumeration
`dnsrecon -d networkwalks.com` was used to enumerate DNS records such as SOA, NS, MX, A and TXT records.

### 7. Local Network Discovery
Zenmap/Nmap was used to scan the local network `192.168.100.0/24` and identify active hosts.

## Screenshots

All screenshots are stored in the [`images`](./images) folder.

| Screenshot | Description |
|---|---|
| [Page 1](./images/page-01.png) | WHOIS output |
| [Page 2](./images/page-02.png) | WhatWeb output |
| [Page 3](./images/page-03.png) | nslookup output |
| [Page 4](./images/page-04.png) | curl HTTP header inspection |
| [Page 5](./images/page-05.png) | WAFW00F output |
| [Page 6](./images/page-06.png) | dnsrecon output |
| [Page 7](./images/page-07.png) | Zenmap host discovery |
| [Page 8](./images/page-08.png) | Zenmap topology view |

## Notes

- The screenshots are provided as project documentation.
- Network scanning should only be performed on systems and networks where you have permission to test.
- Results shown in the screenshots reflect the environment and time at which the scans were performed.
