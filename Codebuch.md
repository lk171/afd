# Codebuch: Verbindungen der AFD zu rechten Vereinigungen #


## Ursprung und Erhebung

Die Grundlage unseres Datensatzes bildet die Liste des Antifaschistischen Dokumentations- und Informationszentrum (https://www.adiz.info/landtagswahl-2021/ ). Da die Verantwortlichen dafür aber sehr links sind, überprüfen wir die Angaben noch einmal und ergänzen sie mit biographischen Angaben der Abgeordneten und weiterer Google-Recherche. 

## EDGE-Attribute ##
**id**
eindeutige Kodierung des Knoten; jede ID entspricht einem Akteur 
**relation**
Beziehungsart zwischen den Akteuren:
1= Mitglied 
2= Anhänger (meist bei aufgelösten Vereinigungen wie dem Flügel)
3= Sympathisant (Akteur äußert sich positiv über Vereinigung)
**years** 
Dauer der Beziehung bis 2021

## NODE-Attribute ##
**id**
Identische ID wie aus der Edgelist zur Identifikation der Knoten. 
**vorname**
Vorname des Akteurs (bei realer Person)
**name**
Nachname oder Name der Vereinigung
**type** 
Art des Akteurs
1= Vereinigung
2= Privatperson
**team**
Partei-Zugehörigkeit
1 = Landtag
2 = Bundestag
3 = Junge Alternative
**sex**
1= männlich
2= weiblich
3= divers
**year**
Geburts-/ Gründungsjahr
**statement** 
Rechte Äußerungen in sozialen Medien oder bei Reden
=> Äußerungen, die nationalsozialistische/ fremdenfeindliche/ antimuslimische/ antifeministische/ queer-feindliche/ demokratiefeindliche Inhalte, Verschwörungsideologien, Drittes-Reich- und Shoa-Verharmlosungen oder sonstigen Hass und Hetze gegen andere Bevölkerungsgruppen oder Einzelpersonen beinhalten.
1= ja
2= nein
**protest** 
Teilnahme an als rechts eingestuften Demonstrationen
=> Querdenken, Demo für Alle, Kandel für alle, Aufmärsche der IB und JA, sowie des Flügels
1=ja
2=nein
**erfurter**
Unterzeichner*innen der Erfurter Resolution
1=ja
2=nein
**stuttgarter**
Unterzeichner*innen des Stuttgarter Aufrufs
1=ja
2=nein
