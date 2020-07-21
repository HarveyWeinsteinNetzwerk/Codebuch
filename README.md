# Codebuch      

**Datensatz**       
Codebuch Stand 2020-07-23     
erstellt von Clara Schneemann (hdm), Brigitte Buck, Lili Biberthaler, Valerija Vas, Michelle Noss, Julia Lindner      

**Inhalt**      
Edges.csv (Edgelist)      
Nodes.csv (Nodelist)      
Codebuch.rm (Codierung der Datensätze)      

# Ursprung und Datenerhebung      
Wir haben den Datensatz aller Schauspielerinnen nach folgenden Recherchen erstellt:     

- 

Wir erstellen ein ungerichtetes Two-Mode-Netzwerk (Akteur-Unternehmen-Netzwerk) aus Schauspielerinnen und Produktionsfirmen. Fehlende Daten werden mit NA codiert. Die Daten sind aus eigener (Online-)Recherche entstanden.    

# Edgelist    

**from** = Name Schauspielerin     
**to** = Name des Films     
**to** = Name der Produktionsfirma        

**year**     
1 = ab 1980,    
2 = ab 1990,    
3 = ab 2000,    
4 = ab 2010.        

# Nodelist

**ID/Name**   
ID muss identisch zur Edgelist sein (z.B. Name, Abkürzung, etc.)    

**type**
0 = Film,     
1 = Schauspielerin.

**production**     
1 = Miramax,    
2 = The Weinstein Company,   
3 = Universal Studios,       
4 = Paramount Pictures,       
5 = andere.   

**sex**     
1 = weiblich,   
2 = männlich.   

**birth**   
1 = 1950 bis 1960,      
2 = 1961 bis 1970,    
3 = 1971 bis 1980,    
4 = 1981 bis 1990,    
5 = 1991 bis 2000.    

**ethnicity**   
1 = deutsch,    
2 = Mittel/Osteuropa (auch UK),   
3 = Südeuropa,    
4 = Asien,    
5 = Skandinavien,   
6 = Südamerika,   
7 = Nordamerika,    
8 = Russland,   
9 = Afrika.   

**frequency**       
Anzahl der Produktionen unter Weinstein     
1 = bis zweimal,     
2 = bis viermal,    
3 = bis sechsmal.     

##
