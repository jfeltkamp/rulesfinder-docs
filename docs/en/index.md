# RulesFinder documentation (English)

## What is RulesFinder?

RulesFinder is a participation and argumentation software for collaboratively negotiating contracts. The software supports the participation of all stakeholders[^1] in contract negotiations. It uses proven heuristic methods to help find optimized regulations for each negotiated point and simplifies fair decision-making. Every rule or contractual clause can be individually negotiated and optimized without losing sight of the issues that need to be regulated.

Here, we refer to "contracts" as all texts that summarize practical norms into a closed set of rules. This includes:

* **Contracts** in the narrower sense, e.g., purchase, rental, or employment contracts
* **Regulations**, e.g., house rules, data protection regulations
* **Agreements**, e.g., statutes, programs
* and others, e.g., netiquette, game rules, swimming rules, rules of etiquette

[^1]: Here, "stakeholder" refers to a person or group with a legitimate interest in a contract. This could also be called "claimants" or "interested parties."

## Benefits

* Structured negotiation process
* Complete context for all contract clauses or regulations
* Transparent decisions at every single point
* Rating and voting tools
* Fully versioned history for all changes
* Multiple, individually votable change proposals for each rule

## Availability

_Should you host RuFi yourself—or opt for a Software-as-a-Service package[^2]?_ (Abbreviated: SaaS package) — This is a question you should consider at the beginning. While RuFi is free, open-source software, costs arise for providing a web server, and installation requires technical know-how from a web developer or system administrator. In other words, a SaaS offering[^2] can be significantly more cost-effective than installing the software yourself, creating regular backups, and applying security updates.

[^2]: SaaS stands for _Software-as-a-Service_.

You can find information about **SaaS offerings**[^2] on the website [rulesfinder.org](https://rulesfinder.org).

An **installation guide** for the software [can be found here](de/get-rufi/install-rufi).

## Technical Details

Technically, RuFi is a Drupal distribution. This means that RuFi is installed together with Drupal Core as a framework, a set of additional modules, and a predefined software configuration.

Drupal is a PHP-based content management system that meets high security standards while remaining flexible and easy to extend modularly. The extensibility and flexibility are inherited by RulesFinder, as it adopts Drupal's code and coding standards.

For the future, several extensions to the RuFi software are planned, such as enhanced event logging or workflow management, which can be installed as additional modules to expand functionality. We are optimistic that open-source developers will contribute their own ideas and enhancements, which will further increase the usefulness of this software.

Check out the [usage](usage) section for further information, including how to [install](usage#installation) the project.

!!! success

    This project is under active development.