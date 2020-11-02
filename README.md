# Codebuch      

**Datensatz**       
Codebuch Stand 2020-07-27  

erstellt von 
- Clara Schneemann (cs286@hdm-stuttgart.de)
- Brigitte Buck (bb095@hdm-stuttgart.de)
- Lili Biberthaler (lb144@hdm-stuttgart.de)
- Valerija Vasylevytska (vv010@hdm-stuttgart.de)
- Michelle Noss (mn063@hdm-stuttgart.de)
- Julia Lindner (jl125@hdm-stuttgart.de)

**Inhalt**      
Edges.csv (Edgelist)      
Nodes.csv (Nodelist)      
Codebuch.rm (Codierung der Datensätze)      

# Ursprung und Datenerhebung      
Wir haben den Datensatz aller Schauspielerinnen nach folgenden Recherchen erstellt:     

- https://www.theguardian.com/film/ng-interactive/2017/oct/13/the-weinstein-allegations
- https://praxistipps.focus.de/harvey-weinstein-skandal-diese-frauen-beklagen-sexuelle-belaestigungen_116394
- https://www.imdb.com/
- https://de.wikipedia.org/wiki/Weinstein-Skandal
- https://www.faz.net/aktuell/gesellschaft/kriminalitaet/harvey-weinstein-hatte-maechtige-freunde-15327758.html
- https://www.zeit.de/kultur/2020-02/harvey-weinstein-prozess-anklage-plaedoyer
- https://www.zeit.de/kultur/film/2020-01/harvey-weinstein-spionage-vergewaltigung-prozess-metoo-usa
- https://www.nytimes.com/2017/10/05/us/harvey-weinstein-harassment-allegations.html
https://www.nytimes.com/2020/02/24/nyregion/harvey-weinstein-case-sexual-assault.html
https://www.newyorker.com/news/news-desk/harvey-weinsteins-army-of-spies
- Dokumentation "Unantastbar - Der Fall Harvey Weinstein"
- Dokumentation "Harvey Weinstein, Chronik eines Skandals" 


Wir erstellen ein ungerichtetes Two-Mode-Netzwerk (Akteur-Unternehmen-Netzwerk) aus Schauspielerinnen und Produktionsfirmen. Fehlende Daten werden mit NA bzw. 99 codiert. Die Daten sind aus eigener (Online-)Recherche auf Basis der Fokus-Liste und der Filmdatenbank IMDb (s.o.) entstanden.    

# Edgelist    

**from** = Name Schauspielerin     
**to** = Name des Films               

# Nodelist

**ID/Name**   
ID muss identisch zur Edgelist sein (z.B. Name, Abkürzung, etc.)    

**type**        
Typus           
0 = Film,         
1 = Schauspielerin.   
    
**production**         
Produktionsfirma des Filmes     
1 = Miramax,        
2 = The Weinstein Company,       
3 = Universal Studios/Pictures,                   
4 = Paramount Pictures,           
5 = andere.       

**year**         
Erscheinungsjahr des Films     
1 = 1980 bis 1989,             
2 = 1990 bis 1999,            
3 = 2000 bis 2009,                  
4 = 2010 bis einschließlich 2018.                   

**sex**  
Geschlecht      
1 = weiblich,       
2 = männlich.       

**birth**   
Geburtsjahr    
1 = 1950 bis 1960,          
2 = 1961 bis 1970,        
3 = 1971 bis 1980,        
4 = 1981 bis 1990,        
5 = 1991 bis 2000.        

**ethnicity**  
Herkunft      
1 = deutsch,        
2 = Mittel/Osteuropa (auch UK),       
3 = Südeuropa,        
4 = Asien,        
5 = Skandinavien,       
6 = Südamerika,       
7 = Nordamerika (auch Kanada),                 
8 = Russland,       
9 = Afrika.       

**frequency**           
Anzahl der Produktionen unter Weinstein (Miramax und The Weinstein Company)                 
1 = kein mal,        
2 = bis dreimal,                
3 = ab viermal. 

**pattern**                     
entspricht dem Muster von Harvey Weinstein
0 = entspricht nicht Muster
1 = entspricht Muster

**payment** 
Schweigegeldzahlungen
0 = keine Zahlung von Schweigegeld
1 = Zahlung

**relationship** 
Beziehung
0 = keine
1 = Ben Affleck
2 = Brad Pitt

**personal connection** 
persönliche Beziehungen
0 = keine
1 = Uma Thurman
2 = Daryl Hannah
3 = Ashley Judd
4 = Salma Hayek
5 = Gwyneth Paltrow
6 = Rosanna Arquette
7 = Claire Forlani
8 = Angelina Jolie
9 = Rose McGowan
10 = Kate Beckinsale

**business connection** 
geschäftliche Verbindungen
0 = keine
1 = Uma Thurman
2 = Annabella Sciorra
3 = Daryl Hannah
4 = Sean Young
5 = Salma Hayek
6 = Ashley Judd
7 = Kate Beckinsale
8 = Gwyneth Paltrow
9 = Alice Evans
10 = Romola Garai
11 = Mira Sorvino

**social media** 
folgen sich auf Social Media
0 = keine
1 = Uma Thurman
2 = Gwyneth Paltrow
3 = Rose McGowan
4 = Lena Headey
5 = Kate Beckinsale
6 = Mira Sorvino
7 = Ashley Judd
8 = Cara Delevigne
9 = Salma Hayek

##
