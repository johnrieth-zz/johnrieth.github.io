---
layout: post
title: Implement HTTPS for All California Government Websites
description: secure web for californians
category: policy
---

Not all publicly accessible California government websites use [Hypertext Transfer Protocol Secure (HTTPS)](https://developers.google.com/web/fundamentals/security/encrypt-in-transit/why-https) to deliver secure digital services for all Californains. The California Department of Technology (CDT) needs to increase the adoption of HTTPS to ensure that all government websites are secure.

To increase the adoption of HTTPS the CDT should make [Let's Encrypt](https://letsencrypt.org/) the default certificate authority and downgrade the current certificate authority, [Comodo](https://cdt.ca.gov/services/wp-content/uploads/sites/2/sites/2/2017/03/Secure-Certificate-Guideline.pdf) to be the secondary certificate authority.

Moving away from the current certificate system will simplify HTTPS adoption as [Let's Encrypt allows for automatic renewal](https://letsencrypt.org/about/) while the CDT [does not process renewals "until a week prior to the current certificate expiration date"](https://cdt.ca.gov/services/wp-content/uploads/sites/2/sites/2/2017/03/Secure-Certificate-Guideline.pdf). Making Let's Encrypt the state's certificate authority will also increase HTTPS adoption because the certificates are free while [certificates from the CDT cost money because the department uses a commercial certificate authority](https://cdt.ca.gov/services/wp-content/uploads/sites/2/sites/2/2017/03/Secure-Certificate-Guideline.pdf).

The CDT should use [Pulse](https://pulse.cio.gov/about/) to track HTTPS adoption by California government domains.

**References**

[American Government: The HTTPS-Only Standard](https://https.cio.gov/)

[Canadian Government: Implementing HTTPS for Secure Web Connections](https://www.canada.ca/en/treasury-board-secretariat/services/information-technology/policy-implementation-notices/implementing-https-secure-web-connections-itpin.html#toc8)

[California Department of Technology: Security Certificate](https://cdt.ca.gov/services/certificates/)