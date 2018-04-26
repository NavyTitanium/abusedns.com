---
title: Amplification
description : "DNS amplification attack."
---

### Overview <a id="chapter-1"></a>

**Reflected attacks send thousands of requests with the victim’s name as the source
address. When recipients answer, all replies converge on the official sender, whose
infrastructures are then affected.**

Reflective amplification DoS: if the size of the answer is larger than the question,
an amplification effect is caused. The same technique as reflected attacks is used, except
that the difference in weight between the answer and question amplifies the extent of
the attack. A variant can exploit the protective measures in place, which need time to
decode the long replies; this may slow down query resolution
#### Types of DNS amplification attacks

+ NX Domain
+ DNSSEC
+ ANY
+ EDNS0

### Real case abuse<a id="chapter-2"></a>

### Tools <a id="chapter-3"></a>

### Research <a id="chapter-4"></a>

### Mitigation <a id="chapter-5"></a>

### References <a id="chapter-6"></a>
[What is a DNS amplification attack](https://www.incapsula.com/ddos/attack-glossary/dns-amplification.html)





