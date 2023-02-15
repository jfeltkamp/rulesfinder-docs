# RulesFinder documentation

**"Was ist RulesFinder?"** RulesFinder [ru:ls|faɪnder] ist eine online-Software für das gemeinsame aushandeln von Verträgen. Die Software unterstützt die Teilnahme aller Stakeholder[^1] an Vertragsverhandlungen. Sie hilft mit bewährten heuristischen Methoden in jedem verhandelten Punkt optimierte Regelungen zu finden und vereinfacht faire Entscheidungen. Jede Regel oder Vertragsklausel kann einzeln verhandelt und optimiert werden, ohne dass die zu regelnden Problemlagen aus dem Blick geraten.

Als "Verträge" bezeichnen wir hier - im weitesten Sinne - alle Texte, welche praktische Normen zu einem geschlossenen Regelwerk zusammenfassen. Also:

* **Verträge** im engeren Sinne, z.B. Kauf-, Miet-, Arbeitsverträge, ...
* **Verordnungen**, z.B. Hausordnungen, Datenschutzverordnungen
* **Vereinbarungen**, z.B. Satzungen, Programme 
* und auch Anderes, z.B. Netiquette, Spielregeln, Baderegeln, Anstandsregeln.

[^1]: Als "Stakeholder" bezeichnen wir eine Person oder Gruppe, die ein berechtigtes Interesse an einem Vertrag hat. Man könnte diese zu Deutsch auch "Anspruchsberechtigte" nennen.

## Vorteile 

* Strukturierter Verhandlungsverlauf 
* Gesamter Kontext zu allen Vertragsklauseln oder Regelungen
* Transparente Entscheidungen in jedem einzelnen Punkt
* Rating- und Abstimmungstools
* Voll versionierte Historie für alle Änderungen
* Mehrere, einzeln abstimmbare Änderungsvorschläge für jede Regel

## Verfügbarkeit

_RuFi selbst hosten - oder ein SaaS-Paket[^2] buchen?_ - Diese Frage sollten Sie sich am Anfang stellen. RuFi ist zwar eine kostenlose Open-Source-Software; doch Kosten entstehen auch für die Bereitstellung eines Webservers und die Installation setzt technisches Know-How eines Webentwicklers oder Systemadministrators voraus. D.h. ein SaaS-Angebot[^2] kann deutlich günstiger sein, als die Software selbst zu installieren, regelmäßige Back-Ups zu erstellen und Sicherheitsupdates einzupflegen.

[^2]: SaaS ist eine Abkürzung für _Software-as-a-Service_.

Über **SaaS-Angebote**[^2]  können Sie sich auf der Website [rulesfinder.org](https://rulesfinder.org) informieren.

Eine **Installationsanleitung** für die Software [finden Sie hier](get-rufi/install-rufi). 

## Technische Angaben

Technisch gesehen ist RuFi eine Drupal-Distribution. Das heißt, dass RuFi zusammen mit dem Drupal Core als Framework, mit einem Set von Zusatzmodulen und mit einer vordefinierten Software-Konfiguration installiert wird.

Drupal ist ein PHP-basiertes Content-Management-System, welches hohe Sicherheitsstandards erfüllt und zugleich flexibel und leicht modular erweitert werden kann. Die Erweiterbarkeit und Flexibilität vererbt sich an den RulesFinder, weil dieser Code und Coding-Standards von Drupal übernimmt. 

Für die Zukunft sind einige Erweiterungen der RuFi-Software geplant, wie z.B. ein erweitertes Event-Logging, oder ein Workflow-Management, die als Zusatzmodule installiert werden können und den Funktionsumfang erweitern. Wir hoffen darauf, dass Open-Source-Entwickler eigene Ideen und Beiträge beisteuern, welche die Nützlichkeit dieser Software weiter erhöhen. 



Check out the [usage](usage) section for further information, including how to [install](usage#installation) the project.

!!! success

    This project is under active development.