---
title: Brute Forcing
description : "Nice buttons on your page."
---
**DNS records hold a surprising amount of host information. By brute forcing them we can reveal additional targets. Also, DNS entries often give away information, for example "mail" indicating that we are obviously dealing with the mail server, or Cloudflare's default DNS entry "direct" which most of the time will point to the IP that they are trying to protect.**

### Technique used
Most of those tools are based on a dictionary of common server names, and a DNS request for each entries 	as a sub-domain of the domain you're testing.

### Type of brute forcing
Populars open-source tools for each of those type of those attacks are given below
#### Domain name
It is possible to enumerate all records for a given domain name.

##### Tools

|<div class="fa fa-wrench" aria-hidden="true" style="color: #00CC01;"> </div> Name | Description | Language |
| ------ | ----------- | ------ |
| [DNSRecon ](https://github.com/darkoperator/dnsrecon) | Subdomain enumeration tool | Python |

#### Sub-domain
Tools will normally attempts to enumerate DNS hostnames by brute force guessing of common sub-domains using a dictionary.

##### Tools

|<div class="fa fa-wrench" aria-hidden="true" style="color: #00CC01;"> </div> Name | Description | Language |
| ------ | ----------- | ------ |
| [SubBrute](https://github.com/TheRook/subbrute)   | Subdomain enumeration tool | Python |
| [Sublist3r](https://github.com/aboul3la/Sublist3r) | Enumerate subdomains of websites using OSINT | Python |
| [DNS-Discovery](https://github.com/m0nad/DNS-Discovery) | A multithreaded subdomain bruteforcer | C |
| [dns-brute](https://nmap.org/nsedoc/scripts/dns-brute.html) | Attempts to enumerate DNS hostnames | Nmap Script |
| [Knockpy](https://github.com/guelfoweb/knock) | enumerate subdomains on a target domain | Python |
| [Anubis](https://github.com/jonluca/Anubis) | a subdomain enumerator and information gathering tool | Python |






### References

https://www.foo.be/papers/sdbf.pdf