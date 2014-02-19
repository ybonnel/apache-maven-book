apache-maven-book
=================

[![Build Status](https://apache-maven.ci.cloudbees.com/buildStatus/icon?job=apache-maven-book)](https://apache-maven.ci.cloudbees.com/job/apache-maven-book/)

Apache Maven (le livre)

Pearson ayant décidé d'arrêter l'exploitation de ce livre, Arnaud et moi-même avons décidé de récupérer nos droits et de le publier pour qu'il soit accessible gratuitement à tous, et - sait on jamais - vive un second souffle avec l'aide de contributeurs bénévoles.

![cover](cover.jpg)

License : [Creative-commons CC BY-SA 4.0](http://creativecommons.org/licenses/by-nc-sa/4.0/deed.fr)

compile
=======

Pour produire les chapitres au format html, il suffit de lancer ```mvn clean compile```, le résultat est disponible sous ```target/html```

Si vous n'aimez pas maven (commencez par demander pourquoi vous êtes sur ce repo), vous pouvez générer les fichiers html avec gradle : ```gradlew asciidoctor```, le résultat est produit dans ```build/docs```.

Vous pouvez visualiser le contenu directement sur GitHub, ou consulter la [version HTML](https://apache-maven.ci.cloudbees.com/job/apache-maven-book/HTML/)
