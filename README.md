# Terminaler

## Popis projektu

* Webová aplikace pro spouštění terminálových příkazů na webovém serveru.
* Účelem projektu bylo vytvoření jednoduché webové aplikace s odesíláním formuláře, ve které použiji vybrané technologie a frameworky (především Spring MVC a šablony JSP), nikoliv navrhnout uživatelsky smysluplnou aplikaci, například chybí CSS (pardon) a výstupy uživatelem zadaných příkazů se vypisují do konzole vývojářského prostředí. 
* Příkazy ve webovém rozhraní prosím zadávat ve správném tvaru (a žádné hacky), ve formuláři jsou sice připravené validace, ale kontrolují pouze prázdný vstup.
* Později jsem v projektu připravila repozitář CRUD příkazů pro práci s databází a testovací databázi HSQLDB, tak aby bylo v budoucnu možné dodělat perzistentní ukládání uživatelem zadaných příkazů.


## Poznámky k projektu

* K vytvoření projektu jsem použila maven-archetype-webapp. 
* Pro spuštění aplikace používám lokálně nainstalovaný Tomcat 8.0.47. (Stručný návod nastavení v Intellij Idea: otevřít projekt – Edit Configuration (v liště vpravo nahoře) – Plus (vlevo nahoře) – vybrat Tomcat Server – Local – Deployment (nahoře) – Plus - Artifacts - druhá možnost (war exploded) – Apply.)
* Projekt vznikl na macOS, zkoušela jsem jej spustit i na Windows a spuštění proběhlo v pořádku.
* Projekt jsem vyvíjela v Intellij IDEA 2016.3.7.
