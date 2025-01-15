Anything that can impact the confidentiality, integrity or availability of an asset. A formula to determine the level of the risk defines that: the risk level is equal to the possibility of an attack.

There are many factors that can affect the probability of a risk to an organization assets:

* **External Risk**: Anything outside of the organization that has the potential to damage organizational assets, like threat agents that can obtain access to private informations.
* **Internal Risks**: An employer, supplier or trusted partner, old or new, that represents a risk.
* **Legacy systems**: Legacy systems that can't or can be updated, but still can impact the assets, like old work stations or old mainframe systems.
* **Multi-part risk**: Third party workers can have access on intelectual property, such as comercial secrets, software projects and creations.
* **Accordance/software licensing**: Software that is not updated or in accordance, or even patches that are not installed just in time.

Risks also can be ranked as:

* **Low-risk asset**: Information that would not harm the organizations reputation or ongoing operations, and would not cause financial damage if compromised
* **Medium-risk asset**: Information that's not available to the public and may cause some damage to the organization's finances, reputation, or ongoing operations.
* **High-risk asset**: Information protected by regulations or laws, which if compromised would have a severe negative impact on an organization's finance, ongoing operations or reputation.

# Web Risks

The [OWASP](https://owasp.org/www-project-top-ten/) publish and lists the most critical risks to web applications. They have, also, trainings based on these types of risks, that emulates real life scenarios such as websites like [JuiceShop](https://owasp.org/www-project-juice-shop/).

They categorize the threats as:

1. **Broken-Access Control**
2. **Cryptographic Failures**
3. **Injection**
4. **Insecure Design**
5. **Security Misconfiguration**
6. **Vulnerable and Outdated Components**
7. **Identification and Authentication Failures**
8. **Software and Data Integrity Failures**
9. **Security Logging and Monitoring Failures**
10. **Server-Side Request Forgery (SSRF)**

# OWASP

This stands for Open Worldwide Application Security Project. The OWASP project has principles that aim to protect an application. They can be listed as:

* **Minimize attack surface area** -> Surface Area means all the vulnerabilities a threat actor can exploit.
* **Principle of least privilege** -> The users can only have the privileges that they use on a daily basis
* **Defense in Depth** -> There has to be many security controls that mitigate risks and threats.
* **Separation of duties** -> Critical tasks need to be executed by the bigger number of people as possible.
* **Keep security simple** -> The phrase speaks for itself.
* **Fix security issues correctly** -> When breaches occurs, identify the cause, contain the damage, identify the vulnerabilities and do tests that allow to measure if the correction was really well done.
* **Establish secure patterns** -> The ideal security state for an application is the ideal state for the users.
* **Fail with safety** -> When a control fails or is interrupted, it needs to do it with the safest option. For example, if a firewall fails, it must simply close all opened connections and block new ones.
* **Don't trust third parties** -> When dealing with another party, such as another company or a consultant, you always need to assume that the systems used by them are not safe.
* **Don't gatekeep** -> The security of a system must not be based on keeping details hidden.