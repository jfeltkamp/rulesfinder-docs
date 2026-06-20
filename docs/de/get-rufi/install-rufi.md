# Neues RulesFinder-Projekt installieren

Dieses Projekttemplate bietet einen Schnellstart für die Verwaltung deiner Website-Abhängigkeiten mit [Composer](https://getcomposer.org/).

## Voraussetzungen

Du benötigst die folgende Software auf deinem Webserver.

* Apache 2.4.7+ oder Nginx 1.1+
* PHP 8.3 - 8.4
* MySQL 8.0+, MariaDB 10.6+ oder PostgreSQL 16+

## Verwendung

Zunächst musst du [Composer](https://getcomposer.org/doc/00-intro.md#installation-linux-unix-osx) und [Git](https://git-scm.com) installieren.

> Hinweis: Die folgenden Anweisungen beziehen sich auf die [globale Composer-Installation](https://getcomposer.org/doc/00-intro.md#globally).
Du musst möglicherweise `composer` durch `php composer.phar` (oder ähnlich) für dein Setup ersetzen.

Danach kannst du das Projekt erstellen:

```
composer create-project jfeltkamp/rules-finder-project -s dev <my_project_name>
```

Der Befehl `composer create-project` übergibt den Besitz aller Dateien an das
erstellte Projekt. Du solltest ein neues Git-Repository erstellen und alle
Dateien commiten, die nicht durch die .gitignore-Datei ausgeschlossen sind.

## Was macht das Template?

Bei der Installation der angegebenen `composer.json` werden einige Aufgaben erledigt:

* Drupal wird im `docroot`-Verzeichnis installiert.
* Der Autoloader ist so implementiert, dass er den generierten Composer-Autoloader in `vendor/autoload.php` verwendet,
  anstatt des von Drupal bereitgestellten (`docroot/vendor/autoload.php`).
* Module (Pakete vom Typ `drupal-module`) werden in `docroot/modules/contrib/` platziert.
* Themes (Pakete vom Typ `drupal-theme`) werden in `docroot/themes/contrib/` platziert.
* Profile (Pakete vom Typ `drupal-profile`) werden in `docroot/profiles/contrib/` platziert.
* Es werden Drupal-Scaffold-Dateien wie `index.php` oder `.htaccess` heruntergeladen.
* Das `sites/default/files`-Verzeichnis wird erstellt.
* Die neueste Version von drush wird lokal für die Verwendung unter `bin/drush` installiert.
* Die neueste Version von DrupalConsole wird lokal für die Verwendung unter `bin/drupal` installiert.

## RulesFinder installieren

Das Erstellen des Projekts installiert RulesFinder im docroot-Verzeichnis innerhalb von RulesFinder. Du kannst RulesFinder nun wie jede andere Drupal 11-Site installieren. Siehe: [Drupal-Installationsanleitung](https://www.drupal.org/node/1839310).

## RulesFinder aktualisieren

Um RulesFinder, Drupal oder ein anderes Modul auf die neueste Version zu aktualisieren, beschränkt durch die angegebene Version in `composer.json`, führe `composer update` aus. Dieser Befehl prüft jede Abhängigkeit auf eine neue Version, lädt sie herunter und aktualisiert entsprechend die `composer.lock`.
Danach kannst du `drush updb` im docroot-Ordner ausführen, um die Datenbank deiner Website zu aktualisieren.

### Dateiaktualisierung

Dieses Projekt wird versuchen, alle deine RulesFinder- und Drupal-Core-Dateien auf dem neuesten Stand zu halten; das
Projekt [drupal/core-dev](https://github.com/drupal-composer/drupal-scaffold)
wird verwendet, um sicherzustellen, dass deine Scaffold-Dateien jedes Mal aktualisiert werden, wenn Drupal/Core aktualisiert wird. Wenn du eine der „Scaffolding"-Dateien anpasst (üblicherweise .htaccess),
musst du möglicherweise Konflikte zusammenführen, wenn eine deiner modifizierten Dateien in einer neuen Version von Drupal Core aktualisiert wird.

Befolge die folgenden Schritte, um deine RulesFinder-Dateien zu aktualisieren.

1. Führe `composer update drupal/rules_finder` aus
1. Führe `git diff` aus, um zu bestimmen, ob sich einige der Scaffolding-Dateien geändert haben.
   Überprüfe die Dateien auf Änderungen und stelle alle Anpassungen an
   `.htaccess` oder `robots.txt` wieder her.
1. Commite alles zusammen in einem einzigen Commit, damit `web` mit `core` synchron bleibt,
   wenn du Branches auscheckst oder `git bisect` ausführst.
1. Falls es in Schritt 2 zu nichttrivialen Konflikten kommt, möchtest du diese Schritte möglicherweise
   auf einem Branch durchführen und `git merge` verwenden, um die aktualisierten Core-Dateien mit deinen angepassten Dateien zusammenzuführen. Dies erleichtert die Verwendung eines [Three-Way-Merge-Tools wie kdiff3](http://www.gitshah.com/2010/12/how-to-setup-kdiff-as-diff-tool-for-git.html). Diese Einrichtung ist nicht notwendig, wenn deine Änderungen einfach sind;
   alle deine Änderungen am Anfang oder Ende der Datei zu halten ist eine gute Strategie, um Merges einfach zu halten.
1. Richte den Host in den ```docroot```-Ordner.