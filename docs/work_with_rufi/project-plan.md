# Projekt-Planung und Durchführung

Wenn Sie derjenige sind, der ein neues RuFi-Projekt angeregt hat, oder Ihnen die Verantwortung für die Durchführung übertragen wurde, dann sollten Sie sich mit den folgenden Themen auseinandersetzen. 

## Setup einer RuFi-Installation

Um ein neues RuFi-Projekt zu starten, benötigen Sie eine neue Installation der Software. Zurzeit ist es nicht möglich, mit einer Installation der Software mehrere Projekte gleichzeitig zu betreiben.

Über Angebote, die Software als Service (SaaS) auf einem unserer Server zu nutzen, können Sie sich auf der Seite [rulesfinder.org](https://rulesfinder.org) informieren. 

Als Entwickler können Sie die Software [kostenlos herunterladen](../get-rufi/install-rufi.md) und verwenden. Die Software steht unter einer Open-Source-Lizenz; nähere Angaben dazu finden Sie in den Licence.txt files, welche den Programmteilen angehängt sind.  

## RuFi ausprobieren mit dem Demo-Content

Um einen guten Anfang mit der Arbeit in RuFi zu finden, ist es immer eine gute Idee, sich zunächst mit den Demo-Inhalten auseinanderzusetzen. Jede RuFi-Installation bringt ein _RuFi-Demo_-Modul mit, das sie einfach installieren können. Nachdem das Modul installiert ist, finden Sie den Demo-Content in den Übersichten unter den Menü-Pfaden: _RuFi > Problems_ (```/sections?node_type=problem```) oder _RuFi > Rules_ (```/sections?node_type=rule```)

!!! info "Demo-Content installieren"
    
    Um den Demo-Content zu installieren benötigen Sie Administrator-Rechte. Gehen Sie in den Bereich "Manage" und wählen Sie im Untermenü den Punkt "Extend" (URL-Pfad: ```/admin/modules```). In der Liste der Module wählen Sie das Modul "RuFi Demo" aus und bestätigen Sie mit "Install" unterhalb der Liste.

Bevor Sie mit dem Projekt wirklich starten, können Sie mit denjenigen, die sich mit RuFi noch nicht auskennen, das Spiel "Wir wohnen zusammen in einer WG und erstellen uns eine WG-Ordnung" spielen.

## Einladung der Teilnehmenden

Laden Sie die Teilnehmenden ein, die an den Verhandlungen teilnehmen sollen. Unsere Empfehlung dabei ist, dass alle Personen an den Verhandlungen teilnehmen können (oder hinreichend repräsentiert sind), die von dem ausgehandelten Vertrag oder Regelwerk betroffen sind, bzw. die darin festgelegten Regeln befolgen sollen. 

Um eine nicht zu bewältigende Flut an Beiträgen zu vermeiden, sollte die Teilnehmendenzahl nicht höher als 10-20 Personen sein. Andererseits werden nicht alle Teilnehmenden regelmäßig Beiträge beisteuern, weswegen die Teilnehmerzahl auch nicht zu klein sein sollte, damit die Verhandlungen zügig vorangehen.

!!! info "Teilnehmende einladen"

    Sie benötigen eine Liste mit den Namen und E-Mail-Adressen aller Teilnehmenden.
    Wiederholen Sie folgende Schritte für jeden Teilnehmenden.

    1. Wählen Sie im Menü den folgenden Pfad: _Manage > People > Add User_ (URL: ``/admin/people/create``).
    2. Tragen Sie in das Formular Namen, E-Mail-Adresse und ein beliebiges aber sicheres Passwort ein.
    3. Wählen für die Benutzer-Gruppe "Member" aus. Teilnehmenden mit eingeschränkten Rechten kann die Gruppe "Beginner" zugeordnet werden.
    3. Aktivieren Sie das Kontrollkästchen _Notify user of new account_.
    4. Klicken Sie den Button _Create new account_ am Ende der Seite.

Wenn Sie diese Schritte ausgeführt haben, werden den eingeladenen Teilnehmenden E-Mails zugesendet. Darin enthalten ist ein Link, mit dem die Teilnehmenden aufgefordert werden, ihr eigenes Passwort festzulegen. Es ist nicht erforderlich, dass sie den Teilnehmenden das von Ihnen festgelegte Passwort mitteilen.    

!!! tip "Tipp: Text für Einladungs-E-Mail anpassen"

    Den Text der Einladung können Sie vor dem Anlegen der Accounts noch anpassen. Wählen Sie dazu im Menü den Pfad: _Configuration > People > Account settings_ (URL: ``/admin/config/people/accounts``) und wählen Sie unten auf der Seite den Tab _Welcome (new user created by administrator)_.

## Projekt-Moderation

Der Erfolg des Projektes ist im hohen Maße von einer Moderation abhängig. Für die Moderation gibt es eine eigene Benutzerrolle mit erweiterten Berechtigungen. Die Moderation kann aus mehreren Personen bestehen. 
Die Aufgaben der Moderation bestehen darin, ...

* bei Bedarf als erste Ansprechperson Hilfestellung zu leisten
* neu erstellte Inhalte zu prüfen, ob diese der erwarteten Form entsprechen, und ggf. Feedback zu geben
* Meetings zu moderieren
* Wahlen und Abstimmungen durchführen
* in Konflikten unparteiisch zu vermitteln

Die Moderation kann beim Projektstart von den Initiatoren oder Projekt-Verantwortlichen ausgeführt werden. Da die Rolle jedoch das Vertrauen der Teilnehmenden erforderlich macht, sollte der Moderator früher oder später durch eine Wahl bestätigt werden.



## Einweisung der Teilnehmenden in die Software-Nutzung

Machen Sie die neuen Teilnehmenden auf diese Dokumentation aufmerksam, insbesondere auf die [Vorgehensweise](../work_with_rufi/get-involved/) und die [Bedienungsanleitung](../work_with_rufi/operation-manual/), wo die wichtigsten Regeln kompakt zusammengefasst sind.

Besprechen Sie die Vorgehensweise und Bedienungsanleitung und stellen Sie sicher, dass niemand aus technischen Gründen abgehängt wird. Wenn sich dennoch jemand überfordert fühlt, ist es möglicherweise ratsam, diesen Nutzer zunächst mit der _Beginner_-Rolle starten zu lassen, welche eher eine Beobachterrolle ist und die Möglichkeit bietet, an Bewertungen und Abstimmungen teilzunehmen. 

Es ist sehr zu empfehlen, mit den neuen Nutzern zunächst spielerisch am Demo-Content zu arbeiten, bevor man sich den ernsten Fragen widmet. Auch wenn es nur ein Spiel ist, sollten alle ihre Rollen ernst nehmen, und die ein oder andere Problemstellung tatsächlich gelöst werden. Die Erfahrungen, welche die Teilnehmenden hier sammeln, können einen großen Unterschied beim Projekt-Start ausmachen.

## Terminierung regelmäßiger Sprint-Meetings

Während des Projektverlaufes sollten regelmäßig Meetings stattfinden. Eine bewährte Praxis ist, das Projekt in fortlaufende Sprints von jeweils ein oder zwei Wochen aufzuteilen. Die Meetings können dann zwischen den Sprints stattfinden, und sie dienen einerseits dazu, den alten Sprint abzuschließen und Abstimmungen durchzuführen (Review) und andererseits dazu, den nächsten Sprint zu planen (Planing).

Um die RuFi-Software auch während eines Meetings z.B. für Abstimmungen nutzen zu können, bietet es sich an, dass die Treffen in einer **online-Konferenz** stattfinden. 

### Review

In der Review werden die im Verlauf des Sprints bearbeiteten Regeln einzeln diskutiert, bevor über sie final abgestimmt wird. Folgende Fragen sollten für jede Regel erörtert werden:

1. Ist das zur Regel **angeführte Problem** formal [korrekt dargestellt](../write_content/probleme/), relevant und bringt es ein berechtigtes Interesse zum Ausdruck?
2. Sind alle Teilnehmenden der Meinung, dass die Argumentation abgeschlossen ist?<br> (Ggf. können auch während des Meetings noch kleine Änderungen eingefügt oder Bewertungen nachgetragen werden.)
3. Gibt es Contra-Argumente, denen einzuführende _Change Request_ angehängt sind? 
4. Ist die **Regel** formal [korrekt dargestellt](../write_content/regeln/)? 
5. Steht die Regel im Widerspruch zu anderen geltenden Regeln?

Wenn alle Teilnehmenden zu diesen Themen befragt wurden, kann die Abstimmung durchgeführt werden, ob die Regel in Kraft treten soll oder nicht. Dazu kann das RuFi-Voting-Tool verwendet werden, oder auch ein anderes Verfahren gewählt werden.

Die Moderation sollte unbedingt darauf achten, dass das **Abstimmungsergebnis** zu den **Erwartungen** passt, die sich aus Qualität der Argumentation sowie deren Bewertungen ergibt. Wenn es dort zu deutliche Abweichungen gibt, sollten die Gründe dafür aufgeklärt und als Argumente eingefügt werden. Auch ist in so einem Fall der Vorschlag berechtigt, die Entscheidung noch einmal zu vertagen. 

!!! tip "Ergebnisse Protokollieren"
    
    Die Ergebnisse von Abstimmungen sollten aus Gründen der Transparenz und zur Absicherung in einem statischen Protokoll festgehalten werden, welches von mehreren Teilnehmenden gegengezeichnet wird.

### Planing

Um Themen effektiv bearbeiten zu können, ist es wichtig, dass die Teilnehmenden diesen Themen fokussiert folgen. Deswegen sollten für jeden kommenden Projekt-Sprint eine gut zu bewältigende Menge an Themen besprochen und festgelegt werden.

Die RuFi-Software ist zurzeit für diesen Zweck noch nicht ausgebaut. Es sind jedoch Lösungen dafür geplant, dass die Moderierenden Sektionen oder einzelne Problemstellungen für die Bearbeitung in einem Projekt-Sprint eingrenzen können.  

## Erster Sprint: Projekt-Ziele definieren

Beginnen Sie einleitend mit den wichtigsten und grundlegenden Fragestellungen und fahren Sie mit den weniger wichtigen Themen in absteigender Reihenfolge fort. Existenziell wichtige Problemfelder (wie z.B. _Finanzen_) sollten einen höheren Stellenwert einnehmen als Themen, die z.B. das Wohlbefinden der Beteiligten oder Umgangsformen betreffen ("Must-Should-Could"). Legen Sie eine Struktur aus drei bis fünf Sektionen fest, die grob alle zu behandelnden Themenfelder abdecken. 

Für Themen, die nur schwer oder gar nicht zugeordnet werden können, sollten Sie am Ende zusätzlich noch einen Bereich _Verschiedenes_ einrichten. Zu einem späteren Zeitpunkt kann die anfängliche Themen-Struktur revidiert werden, so dass der Bereich _Verschiedenes_ durch neue Zuordnungen ggf. wieder aufgelöst werden kann.

Thema des **ersten Sprints** - wie auch der **ersten Sektion des Vertrages** - sollten die gemeinsamen Ziele und Zwecke sein, und wie diese erreicht werden sollen. Bestimmen Sie in der ersten Sektion auch die Werte, welche besonders geachtet werden sollen, und thematisieren Sie dort die Grundprobleme, welche typischerweise auftreten.

Wenn die Teilnehmenden Themen einbringen wollen, die ihnen wichtig sind und _auf der Seele brennen_, aber thematisch nicht in die Planung passen, empfehlen wir, dass Problemstellungen auch in anderen Themenbereichen als Entwurf eingefügt werden können, aber dann erst zu gegebener Zeit aufgegriffen werden. 

## Weitere Sprint-Planung

Die folgenden Sprints sollten sich - je nach Art des Projektes und des erwartbaren Aufwands - von vorne nach hinten durch alle Sektionen durcharbeiten, bis der erste Vertragsentwurf steht. 

Naturgemäß haben alle Teilnehmenden im Verlauf ihre Ideen und Gedanken geschärft, weswegen es sinnvoll ist, besonders die erste Sektion, die gemeinsamen Ziele, noch einmal zu revidieren. Sollte der Vertrag jemals einem Richter oder einer Richterin vorgelegt werden, so sind darin die wichtigen Übereinkünfte enthalten, welche einer Interpretation aller anderen Vertragsklauseln zugrunde liegt.

## Abschluss-Sprint

Für den letzten Sprint bevor die erste finale Version fertiggestellt und verabschiedet wird, sollten alle Teilnehmenden das gesamte Vertragswerk erneut sorgfalt überprüfen, 

* ob alle wichtigen [Problemstellungen](../write_content/probleme/) bearbeitet wurden
* ob alle [Regeln korrekt formuliert](../write_content/regeln/) und untereinander widerspruchsfrei sind
* ob alle [übertragbaren _Change Requests_](../write_content/change-requests/) eingefügt wurden
* ob alle [Argumente korrekt formuliert](../write_content/argumente/) sind
* ob alle [Texte gut formuliert](../write_content/general-edit-texts/) sind

Wenn alle mit dem Ergebnis zufrieden sind, kann der Vertrag rechtskräftig werden, indem alle Teilnehmenden den Vertrag mit Ort, Datum und ihrer Unterschrift bestätigen.

Um eine **finale Version** zu erstellen, gibt es einen eigenen Entitätstyp _Version_, welcher technisch gesehen einen Schnappschuss aller Inhalte zum Zeitpunkt seiner Erstellung festhält, und eine strukturierte Version aller Regeln (ohne Probleme und Argumente) ausgibt.

## Langfristige Nutzung mit Bearbeitungs-Zyklen

Je nach Art des Projektes kann es sinnvoll sein, das Regelwerk zu überarbeiten oder kontinuierlich damit zu arbeiten, um es z.B. den Strukturen einer sich ändernden Organisation oder Umwelt anzupassen. Für langfristige Vereinbarungen, z.B. mehrjährige Kooperationen mit komplexen Anforderungen, sollte von Anfang an die Möglichkeit von Updates eingeplant werden, damit Neuorientierungen und praktische Erfahrungen in das Regelwerk einfließen können.

Oft ergibt sich erst aus der Anwendung von praktischen Regeln, dass diese nicht geeignet sind, die Probleme zu lösen, zu deren Zweck sie eingeführt wurden, dass sie sogar gegenteilige Effekte erzeugen oder andere, neue Probleme zutage fördern. Aus diesem Grund empfiehlt es sich, das Regelwerk beharrlich zu verbessern. Solche Anlässe bieten auch eine gute Grundlage für zielorientierte Diskussionen, worin das gemeinsame Vorhaben reflektiert und die Kooperation gestärkt werden kann.

Darin liegt eine besondere Stärke des RulesFinder, denn alle wesentlichen Inhalte der Diskussion sind dauerhaft gespeichert und können weiterverwendet, verbessert und ergänzt werden.

Neue und bessere Versionen des Vertrages können leicht erstellt werden und ältere Vertragsversion ablösen.

## Vertrags-Versionen

Eine langfristige Nutzung der RuFi-Software wird mit Vertrags-Versionen und entsprechend fortlaufenden Versionsnummern ermöglicht, wobei spätere Versionen frühere Versionen ersetzen. Zu jeder Zeit können vollständige Zwischenstände oder Beschluss-fertige Versionen des Regelwerkes fixiert werden. Dafür wird lediglich eine Entität vom Typ "Version" erzeugt, welche automatisch einen Schnappschuss aller anderen Entitäten zu jenem Zeitpunkt festhält und dauerhaft speichert.[^1]

[^1]: Technisch gesehen, wird keine Kopie der Daten festgehalten, sondern ein Datenarray mit den IDs aller Entitäten (Problems, Rules, Arguments, Sections, ...) und deren Revisions-IDs zum Zeitpunkt der Erzeugung einer Version erstellt und gespeichert.

Zu einer Version gehört ein Kommentarfeld, in welches eingetragen werden kann:

* zu welchem Anlass die neue Version erzeugt wurde
* wer aktiv an der Sitzung teilgenommen hat
* wer nicht an der Sitzung teilgenommen hat (und ggf. durch wen vertreten wird)
* mit welchem Ergebnis die Abstimmung ausgefallen ist
* ab wann die neue Version des Regelwerkes inkraft treten soll
* usw.

In der RuFi Standard-Konfiguration hat nur ein Moderator die Berechtigung, eine neue Version zu erzeugen.

### Vertragsgeltung

Es wird sehr empfohlen, die Geltung eines Vertrages und dessen überarbeiteten Versionen formell zu regeln, z.B. durch Geltungsklauseln, Unterschriften, Entlastungserklärungen, Versammlungsprotokolle usw. Andernfalls kann es zu unerwarteten Komplikationen in Rechtsfragen kommen. 
