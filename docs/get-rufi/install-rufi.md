# Install new RulesFinder project

This project template should provide a kickstart for managing your site
dependencies with [Composer](https://getcomposer.org/).

## Prerequisites

You will need the following software on you webserver.

* Apache 2.4.7+ oder Nginx 0.7+
* PHP 7.4+
* MySQL 5.7.8+, MariaDB 10.3.7+ oder PostgreSQL 10+

## Usage

First you need to install [Composer](https://getcomposer.org/doc/00-intro.md#installation-linux-unix-osx) and [Git](https://git-scm.com).

> Note: The instructions below refer to the [global composer installation](https://getcomposer.org/doc/00-intro.md#globally).
You might need to replace `composer` with `php composer.phar` (or similar)
for your setup.

After that you can create the project:

```
composer create-project jfeltkamp/rules-finder-project -s dev <my_project_name>
```

The `composer create-project` command passes ownership of all files to the
project that is created. You should create a new git repository, and commit
all files not excluded by the .gitignore file.

## What does the template do?

When installing the given `composer.json` some tasks are taken care of:

* Drupal will be installed in the `docroot`-directory.
* Autoloader is implemented to use the generated composer autoloader in `vendor/autoload.php`,
  instead of the one provided by Drupal (`docroot/vendor/autoload.php`).
* Modules (packages of type `drupal-module`) will be placed in `docroot/modules/contrib/`
* Theme (packages of type `drupal-theme`) will be placed in `docroot/themes/contrib/`
* Profiles (packages of type `drupal-profile`) will be placed in `docroot/profiles/contrib/`
* Downloads Drupal scaffold files such as `index.php`, or `.htaccess`
* Creates `sites/default/files`-directory.
* Latest version of drush is installed locally for use at `bin/drush`.
* Latest version of DrupalConsole is installed locally for use at `bin/drupal`.

## Installing RulesFinder

Create project will install RulesFinder into the docroot direcrory inside of RulesFinder. You can now install RulesFinder as you would with any Drupal 9 site. See: [Drupal installation guide](https://www.drupal.org/node/1839310).

## Updating RulesFinder

To update RulesFinder, Drupal or any module to the newest version, constrained by the specified version in `composer.json`, execute `composer update`. This command will check every dependency for a new version, downloads it and updates the `composer.lock` accordingly.
After that you can run `drush updb` in the docroot folder to update the database of your site.

### File update

This project will attempt to keep all of your RulesFinder and drupal core files up-to-date; the
project [drupal/core-dev](https://github.com/drupal-composer/drupal-scaffold)
is used to ensure that your scaffold files are updated every time drupal/core is
updated. If you customize any of the "scaffolding" files (commonly .htaccess),
you may need to merge conflicts if any of your modfied files are updated in a
new release of Drupal core.

Follow the steps below to update your RulesFinder files.

1. Run `composer update drupal/rules_finder`
1. Run `git diff` to determine if any of the scaffolding files have changed.
   Review the files for any changes and restore any customizations to
   `.htaccess` or `robots.txt`.
1. Commit everything all together in a single commit, so `web` will remain in
   sync with the `core` when checking out branches or running `git bisect`.
1. In the event that there are non-trivial conflicts in step 2, you may wish
   to perform these steps on a branch, and use `git merge` to combine the
   updated core files with your customized files. This facilitates the use
   of a [three-way merge tool such as kdiff3](http://www.gitshah.com/2010/12/how-to-setup-kdiff-as-diff-tool-for-git.html). This setup is not necessary if your changes are simple;
   keeping all of your modifications at the beginning or end of the file is a
   good strategy to keep merges easy.
