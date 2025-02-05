---

title: Implementation with Secure Libraries
layout: col-document
tags: OWASP Developer Guide
contributors: Jon Gadsden
document: OWASP Developer Guide
order: 730
permalink: /draft/implementation/secure_libraries/

---

{% include breadcrumb.html %}

## 5.3 Secure libraries

The use of secure libraries is part of the technology management that helps to fulfil security requirements.
Standard libraries help with the adoption of common design patterns and security solutions,
and help standardize technologies and frameworks used throughout the different applications.

[Technology Management][sammdsatm] for the software applications is described by SAMM as an activity
within the SAMM [Security Architecture][sammdsa] security practice
which in turn is part of the [Design][sammd] business function.

Sections:

5.3.1 [Enterprise Security API library](01-esapi.md)  
5.3.2 [CSRFGuard library](02-csrf-guard.md)  
5.3.3 [OWASP Secure Headers Project](03-secure-headers.md)  

----

The OWASP Developer Guide is a community effort; if there is something that needs changing
then [submit an issue][issue0703] or [edit on GitHub][edit0703].

[edit0703]: https://github.com/OWASP/www-project-developer-guide/blob/main/draft/07-implementation/03-secure-libraries/toc.md
[issue0703]: https://github.com/OWASP/www-project-developer-guide/issues/new?labels=enhancement&template=request.md&title=Update:%2007-implementation/03-secure-libraries/00-toc
[sammd]: https://owaspsamm.org/model/design/
[sammdsa]: https://owaspsamm.org/model/design/security-architecture/
[sammdsatm]: https://owaspsamm.org/model/design/security-architecture/stream-b/
