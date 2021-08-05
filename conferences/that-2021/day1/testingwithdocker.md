### Quickly Extending into Testing with Docker
* Reference
 * [https://github.com/tomcudd/docker-tests](https://github.com/tomcudd/docker-tests)
 * [https://github.com/femtopixel/docker-google-lighthouse]()
 * [https://hub.docker.com/r/femtopixel/google-lighthouse]()
 * [https://hub.docker.com/r/sitespeedio/sitespeed.io]()
 * [https://hub.docker.com/r/owasp/zap2docker-stable]()
 * [https://hub.docker.com/r/stupchiy/checklink]()

* Containers as part of a CI/CD pipeline
  * Convenient for building infrastructure for testing a specific tool
    * "Why spin up EC2 instances for a test that happens once a month"
  * Performance quality
    * Use systems to spot differences in performance
  * Lighthouse (Google)
    * Whenever a test runs below a certain threshold, do something (send email, notification, etc)
  * Spend most of our time on the worst offenders
* Sitespeed.io
  * Detailed results on render time, asset loading, etc.
* Security
  * OWASP ZAP (Zed Attack Proxy)
    * Designed to be used by any engineer
* SEO
  * Link Checker (W3C)
* Accessibility
  * Pa11y
* Gotcha's
  * sudo everything or run as root!
  * Folder permissions
    * `chmod o+x docker-tests/`
    * `chmod o+x docker-tests/*`
* Takeaway
  * Low effort, high impact!
  * Build on momentum
  * **Look into selenium docker**
