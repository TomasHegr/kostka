Kostka
===========================

Účel/Zadání/Funkce
-----------------------
Při stistku tlačítka se na LED ukáže náhodné číslo 1 - 6. Jako u hrací kostky


Schéma zapojení
-----------------------

![schéma zapojení](./docs/schema.png)

Popis funkce
-----------------------

* Rozložení svítící/zhasnutých LED bude v poli cube
* Náhodné číslo se vygeneruje z času, po který uživatel drží tlačítko:
    - pokud uživatel drží tlačítko stále se inkrementuje proměnná 'num'
    - pokud uživatel tlačítko pustí provedeme num % 6, tím získá 0-5 respektive 1 - 5
* zobrazím cube[num]
* v projektu je:
    1. jednoduchá varianta: pokud jsou všechny LED na jednom portu
    2. složitější, ale reálná varianta, kdy je každá LED na jiném portu

ToDo
-----------------------

* ještě chybí tamto

Zhodnocení
-----------------------

Na tomto projektu jsem se naučíl jedno a druhé a došlo mi jak funguje třetí.
Zlepšil jsem se v tamtom.

Svou práci bych ohodnotil chvalitebně, protože jsem nepracoval úplně samostatně,
ale vše jsem implementoval a prozkoumal.

Svou práci bych ohodnotil výborně. Nepracoval jsem sice samostatně,
ale nakonec jsem hotový projekt smazal a vytvořil ho celý znovu sám.
