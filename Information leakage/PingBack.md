---
title: PingBack
description : "DNS PingBack reveals internal services"
---

### Overview <a id="chapter-1"></a>
DNS pingback is a method that can be used to reveal IP address of different services. For example, some websites will process and resolve hostnames in certain HTTP headers. This allows the attacker to receive queries on their authoritative DNS server. Also, some web sites will issue HTTP requests back to Referer URLs logged from incoming traffic. Reasons for doing so could vary from marketing to threat analytics.

Some email gateways also process links or domain names inside emails for security purposes. By doing so, an attacker could be receiving DNS queries from that organization, revealing parts of their infrastructure. 

![](dns-referer-attack.png)

### Real case abuse<a id="chapter-2"></a>
This method has been used to decloak backend systems behind the Tor hidden service.

[Using Burp Suite’s Collaborator to Find the True IP Address for a .Onion Hidden Service](http://digitalforensicstips.com/2017/11/using-burp-suites-collaborator-to-find-the-true-ip-address-for-a-onion-hidden-service/)


### Tools <a id="chapter-3"></a>
In many cases, submitting a hostname that you own to the target system will be enough to trigger the PingBack if the service is configured to resolve it.

For example, PortSwigger is a Burp Suite Pro extension which augments your proxy traffic by injecting non-invasive headers designed to reveal backend systems by causing pingbacks to [Burp Collaborator]
(https://github.com/PortSwigger/collaborator-everywhere)


### References <a id="chapter-6"></a>
[BlackHat USA 2017 - Cracking the Lens: Targeting HTTP's Hidden Attack-Surface](https://www.youtube.com/watch?v=zP4b3pw94s0)

[Cracking the lens: targeting HTTP's hidden attack-surface](https://portswigger.net/blog/cracking-the-lens-targeting-https-hidden-attack-surface)