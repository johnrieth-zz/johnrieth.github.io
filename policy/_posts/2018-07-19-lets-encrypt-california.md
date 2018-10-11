---
layout: post
title: Let's Encrypt California
description: secure web for californians https
category: policy
---

### Background

Not all publicly accessible California government websites protect visitors with [Hypertext Transfer Protocol Secure (HTTPS)](https://developers.google.com/web/fundamentals/security/encrypt-in-transit/why-https). HTTPS is necessary for California government websites because the protocol provides ["a fast, secure connection that offers the level of privacy and reliability that users should expect from government web services"](https://https.cio.gov/everything/). The [California Department of Technology (CDT)](https://cdt.ca.gov/) needs to increase the adoption of HTTPS to ensure that all government websites are secure.

### Policy

To increase the adoption of HTTPS the CDT should make [Let's Encrypt](https://letsencrypt.org/) the primary issuer of digital certificates and make the [current issuer](https://cdt.ca.gov/services/wp-content/uploads/sites/2/sites/2/2017/03/Secure-Certificate-Guideline.pdf), [Comodo](https://www.comodoca.com/en-us/solutions/tls-ssl-certificates/) a secondary issuer.

### Reasons to switch

- Let's Encrypt
    - Simplify adoption
        - [Let's Encrypt allows for automatic renewal](https://letsencrypt.org/about/)
    - Increase adoption
        -  [Certificates are free](https://letsencrypt.org/about/)
    - Better security
        - [Ninety-day lifetimes of certificates limit the "damage from key compromise and mis-issuance"](https://letsencrypt.org/2015/11/09/why-90-days.html)

- Comodo
    - [Renewals are not automatic](https://support.comodo.com/index.php?/comodo/Knowledgebase/List/Index/21)
    - [Costs money: $99.95 for 1 year](https://ssl.comodo.com/comodo-ssl-certificate.php?track=8172)
    - [Certificates are either for 1 or 2 years](https://ssl.comodo.com/comodo-ssl-certificate.php?track=8172)

### Why I am wrong

I do not know if the use of Let's Encrypt will simplify and increase HTTPS adoption in the California government. The administrative and development costs of switching certificate issuers could outweigh the benefits.  

### References

[American Government: The HTTPS-Only Standard](https://https.cio.gov/)

[Canadian Government: Implementing HTTPS for Secure Web Connections](https://www.canada.ca/en/treasury-board-secretariat/services/information-technology/policy-implementation-notices/implementing-https-secure-web-connections-itpin.html#toc8)

[California Department of Technology: Security Certificate](https://cdt.ca.gov/services/certificates/)