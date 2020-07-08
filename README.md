# Codebuch
Wir erstellen ein ungerichtetes Two-Mode-Netzwerk (Akteur-Unternehmen-Netzwerk) aus Schauspielerinnen und Produktionsfirmen. Fehlende Daten werden mit NA codiert. Die Daten sind aus eigener (Online-)Recherche entstanden. 

# Edgelist

from = ID des Knoten
to = ID des Knoten (Richtung)

weight 
1 = Hauptrolle im Film, 
2 = Nebenrolle im Film.

amount
0 = noch gar nicht zusammen gespielt,
1 = einmal zusammen gespielt,
2 = zweimal zusammen gespielt, 
3 = mehr als zweimal zusammen gespielt.

relationship
0 = haben im Film nicht zusammen gespielt,
1 = haben im Film zusammen gespielt. 

year 
1 = ab 1980,
2 = ab 1990,
3 = ab 2000,
4 = ab 2010.

production 
1 = Miramax,
2 = The Weinstein Company, 
3 = andere.

# Nodelist

ID/Name
ID muss identisch zur Edgelist sein (z.B. Name, Abkürzung, etc.)

sex (Geschlecht)
1 = weiblich,
2 = männlich.

birth
1 = 1950 bis 1960,
2 = 1961 bis 1970, 
3 = 1971 bis 1980,
4 = 1981 bis 1990,
5 = 1991 bis 2000.

ethnicity
1 = deutsch,
2 = Mittel/Osteuropa (auch UK),
3 = Südeuropa,
4 = Asien, 
5 = Skandinavien,
6 = Südamerika,
7 = Nordamerika,
8 = Russland,
9 = Afrika.

frequency (wie oft wurde in einem Weinstein Film mitgespielt?)
1 = bis zweimal, 
2 = bis viermal, 
3 = bis sechsmal. 
