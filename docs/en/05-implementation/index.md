![Developer guide logo](../../assets/images/dg_logo.png "OWASP Developer Guide"){ align=right width=180 }

The [Implementation][sammi] business function is described by the OWASP [Software Assurance Maturity Model][sammm] (SAMM).
Implementation is focused on the processes and activities related to how an organization
builds and deploys software components and its related defects.
Implementation activities have the most impact on the daily life of developers,
and an important goal of Implementation is to ship reliably working software with minimum defects.

Implementation should include security practices such as :

* [Secure Build][sammisb]
* [Secure Deployment][sammisd]
* [Defect Management][sammidm]

Implementation is where the application / system begins to take shape; source code is written and tests are created.
The implementation of the application follows a secure development lifecycle, with security built in from the start.

The implementation will use a secure method of source code control and storage to fulfill the design security requirements.
The development team will be referring to documentation advising them of best practices,
they will be using secure libraries wherever possible in addition to checking and tracking external dependencies.

----

The OWASP Developer Guide is a community effort; if there is something that needs changing
then [submit an issue][issue0700] or [edit on GitHub][edit0700].

[edit0700]: https://github.com/OWASP/DevGuide/blob/main/docs/es/05-implementation/index.md
[issue0700]: https://github.com/OWASP/DevGuide/issues/new?labels=enhancement&template=request.md&title=Update:%2005-implementation/index
[sammm]: https://owaspsamm.org/model/
[sammi]: https://owaspsamm.org/model/implementation/
[sammidm]: https://owaspsamm.org/model/implementation/defect-management/
[sammisb]: https://owaspsamm.org/model/implementation/secure-build/
[sammisd]: https://owaspsamm.org/model/implementation/secure-deployment/
