---
title: BitSquatting

description : "Bitsquatting is a somewhat well-known technique for exploiting computer hardware errors"
---

**Bitsquatting refers to the registration of a domain names one bit different than a popular domain. The name comes from typosquatting: the act of registering domain names one key press different than a popular domain. Bitsquatting frequently resolved domain names makes it possible to exploit computer hardware errors via DNS.**

### Overview <a id="chapter-1"></a>

Computer hardware, especially RAM, can suffer from random errors that manifest as corruption of one or more bits. The causes of these errors range from manufacturing defects to environmental factors such as cosmic rays and overheating. While the probability of a single error is small, the total error amount in all RAM connected to the Internet is significant. Malicious attackers can exploit these random errors remotely. 

| 01100011 | 01101110 | 01101110 | 0101110 | 01100011 | 01101111 | 01101101 |
| -------- | -------- | -------- | ------- | -------- | -------- | -------- | 
|    c     |     n    |     n    |    .    |     c     |    o      |   m    |

| 01100011 | 0110111<span style="color:red;">1</span> | 01101110 | 0101110 | 01100011 | 01101111 | 01101101 |
| -------- | -------- | -------- | ------- | -------- | -------- | -------- | 
|    c     |     <span style="color:red;">o</span>    |     n    |    .    |     c     |    o      |   m    |

### Real case abuse<a id="chapter-2"></a>

### Tools <a id="chapter-3"></a>

### Research <a id="chapter-4"></a>

### Mitigation <a id="chapter-5"></a>

#### Pre-registration

#### Cyclic Redundancy Checks

#### ECC Memory

### References <a id="chapter-6"></a>

[Bitsquatting: DNS Hijacking without exploitation](http://dinaburg.org/bitsquatting.html)

[Blackhat - Bitsquatting - DNS Hijacking without Exploitation](https://media.blackhat.com/bh-us-11/Dinaburg/BH_US_11_Dinaburg_Bitsquatting_WP.pdf)

[DEF CON 19 - Bit-squatting: DNS Hijacking Without Exploitation](https://www.youtube.com/watch?v=9WcHsT97suU)

[DEF CON 21 - Examining the Bitsquatting Attack Surface](https://www.youtube.com/watch?v=j2FVFVHVvgg)

[Blackhat 2011 - Bit-squatting: DNS Hijacking without exploitation](https://www.youtube.com/watch?v=_si0FYl_IOA)
