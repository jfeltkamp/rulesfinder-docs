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

## Einladung der Teilnehmer

Laden Sie die Teilnehmer ein, die an den Verhandlungen teilnehmen sollen. Unsere Empfehlung dabei ist, dass alle Personen an den Verhandlungen teilnehmen können (oder hinreichend repräsentiert sind), die von dem ausgehandelten Vertrag oder Regelwerk betroffen sind, bzw. die darin festgelegten Regeln befolgen sollen. 

Um eine nicht zu bewältigende Flut an Beträgen zu vermeiden, sollte die Teilnehmerzahl nicht höher als 10-20 Personen sein. Andererseits werden nicht alle Teilnehmer regelmäßig Beiträge beisteuern, weswegen die Teilnehmerzahl auch nicht zu klein sein sollte, damit die Verhandlungen zügig vorangehen.

!!! info "Teilnehmer einladen"

    Sie benötigen eine Liste mit den Namen und E-Mail-Adressen aller Teilnehmer.
    Wiederholen Sie folgende Schritte für jeden Teilnehmer.

    1. Wählen Sie im Menü den folgenden Pfad: _Manage > People > Add User_ (URL: ``/admin/people/create``).
    2. Tragen Sie in das Formular Namen, E-Mail-Adresse und ein beliebiges aber sicheres Passwort ein.
    3. Wählen für die Benutzer-Gruppe "Member" für Teilnehmer aus. Teilnehmern mit eingeschränkten Rechten kann die Gruppe "Beginner" zugeordnet werden.
    3. Aktivieren Sie das Kontrollkästchen _Notify user of new account_.
    4. Klicken Sie den Button _Create new account_ am Ende der Seite.

Wenn Sie diese Schritte ausgeführt haben, werden den eingeladenen Teilnehmern E-Mails zugesendet. Darin enthalten ist ein Link, mit dem die Teilnehmer aufgefordert werden, ihr eigenes Passwort festzulegen. Es ist nicht erforderlich, dass sie den Teilnehmern das von Ihnen festgelegte Passwort mitteilen.    

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

Die Moderation kann beim Projektstart von den Initiatoren oder Projekt-Verantwortlichen ausgeführt werden. Da die Rolle jedoch das Vertrauen der Teilnehmer erforderlich macht, sollte der Moderator früher oder später durch eine Wahl bestätigt werden.



## Einweisung der Teilnehmer in die Software-Nutzung

Machen Sie die neuen Teilnehmer auf diese Dokumentation aufmerksam, insbesondere auf die [Vorgehensweise](../work_with_rufi/get-involved/) und die [Bedienungsanleitung](../work_with_rufi/operation-manual/), wo die wichtigsten Regeln kompakt zusammengefasst sind.

Besprechen Sie die Vorgehensweise und Bedienungsanleitung und stellen Sie sicher, dass niemand aus technischen Gründen abgehängt wird. Wenn sich dennoch jemand überfordert fühlt, ist es möglicherweise ratsam, diesen Nutzer zunächst mit der _Beginner_-Rolle starten zu lassen, welche eher eine Beobachterrolle ist und die Möglichkeit bietet, an Bewertungen und Abstimmungen teilzunehmen. 

Es ist sehr zu empfehlen, mit den neuen Nutzern zunächst spielerisch am Demo-Content zu arbeiten, bevor man sich den ernsten Fragen widmet. Auch wenn es nur ein Spiel ist, sollten alle ihre Rollen ernst nehmen, und die ein oder andere Problemstellung tatsächlich gelöst werden. Die Erfahrungen, welche die Teilnehmer hier sammeln, können einen großen Unterschied beim Projekt-Start ausmachen.

## Terminierung regelmäßiger Reviews und Plannings

Während des Projektverlaufes sollten in regelmäßigen Zeitabständen Meetings stattfinden, die einen Rückblick auf die bisher erstellten Inhalte und Verabredungen bezüglich der nächsten Schritte ermöglichen.



## Erster Sprint: Projekt-Ziele definieren

## Struktur des Sprints

## Bearbeitungs-Zyklen

## Versionen
