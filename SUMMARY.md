# Summary

* [About SOLID](src/content/1/about-solid.md)
  * [What is SOLID?](src/content/1/about-solid.md#what-is-solid)
  * [Why should I use SOLID principles?](src/content/1/about-solid.md#why-should-i-use-solid-principles)
  * [What does SOLID stands for?](src/content/1/about-solid.md#what-does-solid-stands-for)
* What every SOLID principle does?
  * [S - Single Responsibility Principle(SRP)](src/content/2/srp.md)
    * [Example](src/content/2/srp.md#example)
      * [Violation of the SRP 👎](src/content/2/srp.md#violation-of-the-srp-)
      * [Following the SRP Principle 👍](src/content/2/srp.md#following-the-srp-principle-)
  * [O - Open/Closed Principle(OCP)](src/content/2/ocp.md)
    * [Examples](src/content/2/ocp.md#examples)
      * [Third Party API Login - OCP Violation 👎](src/content/2/ocp.md#third-party-api-login---ocp-violation-)
      * [Login with third party API - Following OCP 👍](src/content/2/ocp.md#login-with-third-party-api---following-ocp-)
      * [Payments API implemented with a switch - OCP Violation 👎](src/content/2/ocp.md#payments-api-implemented-with-a-switch---ocp-violation-)
      * [Payments API implemented with a switch - Following OCP 👍](src/content/2/ocp.md#payments-api-implemented-with-a-switch---following-ocp-)
    * [Benefits of the Open / Closed Principle](src/content/2/ocp.md#benefits-of-the-open--closed-principle)
    * [Design patterns that we can find useful for OCP](src/content/2/ocp.md#design-patterns-that-we-can-find-useful-for-ocp)
  * [L - Liskov Substitution Principle(LSP)](src/content/2/lsp.md)
    * [Example](src/content/2/lsp.md#example)
        * [Shipping Calculation](src/content/2/lsp.md#shipping-calculation)
          * [Shipping calculation - LSP violation due to behavior change in daughter class 👎](src/content/2/lsp.md#shipping-calculation---lsp-violation-due-to-behavior-change-in-daughter-class-)
            * [Shipping calculation - LSP violation due to change of invariants from child class 👎](src/content/2/lsp.md#shipping-calculation---lsp-violation-due-to-change-of-invariants-from-child-class-)
            * [Shipping calculation - Following LSP by change of invariants from child class 👍](src/content/2/lsp.md#shipping-calculation---following-lsp-by-change-of-invariants-from-child-class-)
    * [Historical Restrictions](src/content/2/lsp.md#historical-restrictions)
    * [The easiest way not to break the LSP](src/content/2/lsp.md#the-easiest-way-not-to-break-the-lsp)
    * [Interfaces VS Abstract Classes](src/content/2/lsp.md#interfaces-vs-abstract-classes)
      * [Conclusion of Interfaces VS Abstract Classes](src/content/2/lsp.md#conclusion-of-interfaces-vs-abstract-classes)
    * [Design patterns that can be useful to us in the LSP](src/content/2/lsp.md#design-patterns-that-can-be-useful-to-us-in-the-lsp)
  * [I - Interface Segregation Principle(ISP)](src/content/2/isp.md)
    * [Header Interfaces](src/content/2/isp.md#header-interfaces)
    * [Role Interfaces](src/content/2/isp.md#role-interfaces)
    * [Examples](src/content/2/isp.md#examples)
      * [Simple Example](src/content/2/isp.md#simple-example)
      * [Example Developer | QA | PM - ISP violation due to excess responsibilities and poor abstraction 👎](src/content/2/isp.md#example-developer--qa--pm---isp-violation-due-to-excess-responsibilities-and-poor-abstraction-)
      * [Example Developer | QA | PM - Following ISP 👍](src/content/2/isp.md#example-developer--qa--pm---following-isp-)
    * [Design patterns that can be useful to us in the ISP](src/content/2/isp.md#design-patterns-that-can-be-useful-to-us-in-the-isp)
  * [D - Dependency Inversion Principle(DIP)](src/content/2/dip.md)
    * [Laravel controller example](src/content/2/dip.md#laravel-controller-example)
      * [Laravel controller - DIP Violation 👎](src/content/2/dip.md#laravel-controller---dip-violation-)
      * [Laravel controller - Following the DIP 👍](src/content/2/dip.md#laravel-controller---following-the-dip-)
  * [Conclusions](src/content/3/conclusions.md)
  * [Webgraphy](src/content/3/webgraphy.md)