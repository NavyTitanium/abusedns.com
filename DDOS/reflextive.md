---
title: Amplification
description : "DNS amplification attack."
---

**Reflected attacks send thousands of requests with the victim’s name as the source
address. When recipients answer, all replies converge on the official sender, whose
infrastructures are then affected.**

Reflective amplification DoS: if the size of the answer is larger than the question,
an amplification effect is caused. The same technique as reflected attacks is used, except
that the difference in weight between the answer and question amplifies the extent of
the attack. A variant can exploit the protective measures in place, which need time to
decode the long replies; this may slow down query resolution

## Types of DNS amplification attacks

+ NX Domain
+ DNSSEC
+ ANY
+ EDNS0

## References
[What is a DNS amplification attack](https://www.incapsula.com/ddos/attack-glossary/dns-amplification.html)