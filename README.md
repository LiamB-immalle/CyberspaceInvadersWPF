
# Code analyse

Gebruik Visual Studio technieken om de code (actief) te lezen.

Dit doe je door de cursor op een bepaald stuk code te zetten
(een variabele, functie- of constructor-aanroep, ...) en uit het
context-menu 1 van volgende dingen te kiezen:

- Jump to **definition** (`SHIFT-F12`)
- Jump to **implementation** (`CTRL-F12`)
- Find all references (`SHIFT-F12`)
- Search in solution (`CTRL-SHIFT-F`)

(Gebruik na verloop van tijd bij voorkeur de keyboard-shortcuts.)

Probeer volgende dingen:

1. Spring naar de **definitie** van de method `UpdateElement`. Wat valt op?
2. Spring naar de **implementatie** van de method `UpdateElement`. Hoeveel zijn er?
3. Hoe kan je zoeken in VS naar alle plaatsen waar de asset `user.gif` gebruikt wordt?
4. Zoek alle referenties naar de `DisplayOn`-method.
5. Hoeveel keer wordt `createBitmap` aangeroepen in het project?

Enkele vragen over OOP:

1. Waarom heeft men de class `Sprite` abstract gemaakt?
2. Lasers bevat een `List<Laser>`. Hoe noemen we het mechanisme waarbij een class (in dit geval `Lasers`) een andere class (in dit geval `List<Laser>`) bevat? 
3. Waarom is `createBitmap` `protected`?
4. Bekijk de diffs tussen de branches en verklaar wat er veranderd is.


