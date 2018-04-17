---
title: Cache Snooping
description : "Nice buttons on your page."
---

### Overview <a id="chapter-1"></a>

**DNS cache snooping is when someone queries a DNS server in order to find out (snoop) if the DNS server has a specific DNS record cached, and thereby deduce if the DNS server's owner (or its users) have recently visited a specific site.**

This may reveal information about the DNS server's owner, such as what vendor, bank, service provider, etc. they use. Especially if this is confirmed (snooped) multiple times over a period.

This method could even be used to gather statistical information - for example at what time does the DNS server's owner typically access his net bank etc. The cached DNS record's remaining TTL value can provide very accurate data for this.

### Real case abuse<a id="chapter-2"></a>
Figure out which sites users on a network are accessing.
Create more targeted phishing/social engineering attacks.

### Tools <a id="chapter-3"></a>
|<div class="fa fa-wrench" aria-hidden="true" style="color: #00CC01;"> </div> Name | Description | Language |
| ------ | ----------- | ------ |
| [dns-cache-snoop ](https://nmap.org/nsedoc/scripts/dns-cache-snoop.html) | Performs DNS cache snooping against a DNS server | Nmap script |


### Research <a id="chapter-4"></a>

### Mitigation <a id="chapter-5"></a>
* DNS caches should only be allowed to be
access by local users or child caches.
* Non-authoritative requests to DNS caches
should not be allowed.
* Add entropy to DNS caches or DNS servers
when giving out the initial TTL for a given
record.


### References <a id="chapter-6"></a>

[What is "DNS cache snooping" and how do I prevent it - simpledns.com](http://simpledns.com/kb/152/what-is-dns-cache-snooping-and-how-do-i-prevent-it)

[Microsoft DNS Server vulnerability to DNS Server Cache snooping - support.microsoft.com](https://support.microsoft.com/en-sg/help/2678371/microsoft-dns-server-vulnerability-to-dns-server-cache-snooping-attack)

[DNS Cache Snooping paper - cs.unc.edu](http://cs.unc.edu/~fabian/course_papers/cache_snooping.pdf)