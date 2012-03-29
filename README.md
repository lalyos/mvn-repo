Private Maven Repo
==================

Purpose
-------

this is my personal maven repo hosted on github. i created it to be able to easily host a publicly available
maven repo, where i have full control. i will deploy my own project artifacts and archetype artifacts.

once a project becomes more widely used, i will move the maven hosting to sonatype. but they have quite a lot of
requirements: (https://docs.sonatype.org/display/Repository/Sonatype+OSS+Maven+Repository+Usage+Guide) so as a quick 
workaround i can publish here whatever artifact i want.

i followed this description to set it up: (http://cemerick.com/2010/08/24/hosting-maven-repos-on-github/)

Usage
-----

if you want to use this repo for generating a new project based on one of the here-hosted archetypes,
use the following command:

    mvn archetype:generate -DarchetypeCatalog=https://github.com/lalyos/mvn-repo/raw/master/snapshots/

