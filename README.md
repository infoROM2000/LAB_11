# LAB_11
## Dificultati initiale
* Problema mea era ca in pom.xml aparea cu rosu <artifactId>spring-boot-starter-web</artifactId>, iar la compilare toate clasele care au in nume Spring spunea ca nu exista
* Dupa multe cautari, majoritatea spunand (aici eronat) ca e de la server-ul central, am ajuns si la ideea ca ar fi ceva legat de un proxy al Maven-ului
* Am reinstalat IntelliJ si am sters .m2 din Users care este create de Maven
* Si acum functioneaza :)

## Pasii urmati
* Am creat un nou proiect cu SpringInitializr (care este practic implementarea versiunii Web a spring.io in IDE, cu optiunile default(Maven, Java, Spring 2.2.6) + dependinta Spring Web, folosita pentru a folosi paradigma REST impreuna cu MVC (Model-View-Controller), communicand cu reteaua(locala) prin Apache.
* In timpul rularii aplicatiei create initial , se poate observa ca la portul 8080 (standard folosit de Apache) este o pagina de eroare, identica cu cea din curs de la pagina 10, ca urmare a lipsei maparii (aplicatie nu stie momentan ce ar trebui sa faca cand primeste o cerere de vizualizare de la client).
