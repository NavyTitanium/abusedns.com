---
date: 2016-04-09T16:50:16+02:00
title: Reconnaissance
weight: 2
---

Quickly mapping an organisations attack surface is an essential skill for network attackers (penetration testers, bug bounty hunters) as well as those who are defending the network (network security folks, system administrators, blue teams etc).

A detailed footprint of an organisations Internet facing systems is a tactical resource that can be used by both attackers and defenders. By developing an understanding of the attack surface skilled security analysts are able to quickly identify weak areas in the attack surface.

Finding visible hosts from the attackers perspective is an important part of the security assessment process.

DNS reconnaissance is part of the information gathering stage on a penetration test engagement.When a penetration tester is performing a DNS reconnaissance is trying to obtain as much as information as he can regarding the DNS servers and their records.The information that can be gathered it can disclose the network infrastructure of the company without alerting the IDS/IPS.

### Tools
Here is some general tools that can help fingerprinting a domain name.

* DNSdumpster.com is a free domain research tool that can discover hosts related to a domain
https://dnsdumpster.com/

* set of simple shell scripts for DNS troubleshooting
http://digdeepdns.net/install.shtml

* free comprehensive DNS test
https://ftp.isc.org/www/survey/reports/current/fpdns.txt

* http://leafdns.com/

* IntoDNS checks the health and configuration and provides DNS report and mail servers report.
https://intodns.com/

### References
http://cs3.calstatela.edu/~egean/cs581/lecture-notes/counterhack/Chapter%205%20Reconnaissance.pdf
https://github.com/fwaeytens/dnsenum
https://tools.kali.org/information-gathering/dnsmap
https://github.com/makefu/dnsmap
https://pentestlab.blog/tag/dns-enumeration/

{{%children style="h2" description="true" %}}
