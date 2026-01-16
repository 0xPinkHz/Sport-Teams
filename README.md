# Sport-Teams
Erstelle ein Programm das Sport-Teams mit Strukturen abbildet:
## Teil 1: Player
1.	Erstelle eine Struktur `TPlayer` mit
    1.	einem Vornamen
    2.	einem Nachnamen
    3.	einer Nummer
    4.	einem Ranking (1 bis 10)
2.	Erstelle eine Funktion `createPlayer(…)`, die alle Daten für ein Teammittglied über die Kommandozeile abfragt und dann als `TPlayer` zurückliefert.
3.	Schreibe eine Funktion void `updatePlayer(…)`, die die Werte für ein Teammittglied einliest und ein bestehendes `TPlayer`-Objekt damit überschreibt.
4.	Erstelle eine Funktion `printPlayer(…)`, die ein `TPlayer`-Objekt auf den Bildschirm schreibt
5.	Bringe deinen aktuellen Stand ins Remote Repository. 

## Teil 2: Team
6.	Erstelle eine Struktur `TTeam` mit
    1.	einem Array von `TPlayer`, das alle Mitglieder im Team speichert
    2.	einer Team-Größe (Anzahl von Mitgliedern)
    3.	einem Team-Namen
7.	Erstellte eine Funktion `createTeam(…)`, die einen Team-Namen einliest und dann ein leeres Team mit diesem Namen erstellt.
8.	Erstelle eine Funktion `addPlayer(…)` die ein neues Mitglied zu einem Team hinzufügt. Die Funktion soll zurückliefern, ob genug Platz im Team ist, um das zu tun.
9.	Erstelle eine Funktion `getTeamRating(…)`, die den Durschnitt der Ratings aller Mitglieder eines Teams berechnet und zurückliefert.
10.	Schreibe eine Funktion `printTeam(…)`, die ein Team am Bildschirm ausgibt. Dabei soll zuerst der Name und das TeamRating ausgegeben werden, dann die Mitglieder jeweils in einer neuen Zeile.
11.	Bringe deinen aktuellen Stand ins Remote Repository.

## Teil 3: File-Verwaltung für Teams
12.	Schreibe eine Funktion `saveTeam(…)`, die ein Team in eine .csv-Datei schreibt. Dabei soll die Datei den Namen des Teams haben und nur die Daten der Mitglieder (Namen, Nummern und Rankings) enthalten.
13.	Schreibe eine Funktion `updateRating(TTeam team, int value)`, die den value zum Rating von allen Team-Mitgliedern hinzufügt. Achte dabei darauf, dass die Grenzen nicht überschritten werden. (Sollte ein `TPlayer` ein Rating größer als 10 bekommen, setze das Rating auf 10 und setze das Rating auf 1, sollte es kleiner als 1 werden.)
14.	Bringe deinen aktuellen Stand ins Remote Repository.
 
## Teil 4: League
15.	Schreibe eine Struktur `TLeague` mit
    1.	einem Array von Teams
    2.	einer Anzahl von Teams
16.	Bringe deinen aktuellen Stand ins Remote Repository. 

## Teil 5: Menü
17.	Erstelle eine Funktion `getNextPlayerID()`. Dafür soll eine Nummer, die in einer Datei gespeichert ist, ausgelesen werden, um eins erhöht, in die Datei speichert, und zurückliefert.
18.	Erstelle eine Funktion `deleteTeam()`, die eine Team Datei löscht, falls diese schon besteht, und das Team in der Liga sucht und dort entfernt.
19.	Erstelle im `main()` ein Liga-Objekt, das alle Teams verwaltet.
20.	Erweitere deine `main`-Funktion so, dass ein Menü präsentiert wird, das folgende Optionen anbietet:
    1.	Team hinzufügen
    2.	Player hinzufügen
    3.	Player transferieren (aus einem Team entfernen und in ein anderes Team einfügen)
    4.	Team speichern
    5.	Team löschen
21.	Bringe deinen aktuellen Stand ins Remote Repository. 


Schreibe für alle commits eine sinnvolle commit-Messages!
