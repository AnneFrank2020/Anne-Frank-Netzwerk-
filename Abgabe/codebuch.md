# Datensatz Netzwerkanalyse Anne Frank #
### Luisa Scheurer, Celine Bischoff, Kai Roos, Julia Gehringer, Sandra Belschner, Theresa Stumpf ###

## Inhalt
- el.csv (Edgelist)
- nl.csv (Nodelist)
- codebuch.md (Codierung der Datensätze)

## Ursprung und Datenerhebung
Auf Grundlage des Anne Frank Tagebuchs, sowie weiterer Lektüre haben wir ein Netzwerk über Anne Franks Sozialbeziehungen im zeitlichen Verlauf erstellt.

Unser Gesammtnetzwerk ist ein ungerichtetes two-mode Netzwerk, das durch weitere, gewichtete Teilnetzwerke ergänzt wird. 


## EDGE-Attribute 

ID  
codiert von 1 bis XX, jede ID entspricht einer Person bzw. einem Gegenstand.

#### Werte, die nicht verfügbar sind, werden mit "99"gekennzeichnet 

#### WEIGHT  

Ausprägung der Kantenstärke (Beziehungsstärke), definiert nach vorgegeben Skalen:

1 = Neutral 

2 = Gering (negative Emotionen)

3 = Mittel (Freundschaftliche Beziehung)

4 = Stark (starke Zuneigung)

5 = Sehr stark (Liebe) 

#### RELATIONSHIP 

Definiert die Art der Beziehung bei multiplexen Netzwerken mit verschiedenen Beziehungsarten. 

1 = Familie
2 = Kontakt
3 = Freundschaft
4 = Helfer/Hinterhausbewohner
5 = Kontakt zu Verrätern

#### KONFLIKTPOTENZIAL

Definiert die Häufigkeit von Konflikten und potentiellen Konflikten.

1 = nie
2 = sehr selten
3 = ab und zu 
4 = häufig 

#### TIME DEFINITION

Einteilung der Zeitabschnitte in normalisierten Werten:

1 = Frankfurt (Geburt Juni 1929 - Februar 1934) 

2 = Amsterdam - Umzug ins Hinterhaus (Februar 1934 - Juni 1942) 

3 = Hinterhaus Teil 1 (Juli 1942- Dezember 1942)

4 = Hinterhaus Teil 2 (Januar 1943 - Dezember 1943) 

5 = Hinterhaus Teil 3 (Januar 1944 - August 1944) 

6 = Nach dem Krieg (Januar 1946)   

7 = vor Annes Geburt (1929 und früher)


## NODE-Attribute  
  
#### SEX  

Gibt das Geschlecht an.

1 = männlich
2 = weiblich
3 = neutrum 
  

#### RELIGION

Definiert die Religion der Akteure. 
1 = Jude
2 = Christ
3 = sonstiges 

#### SURVIVAL

Todeszeitraum in Korrelation zu den Weltkriegen:

1 = vor dem Ersten Weltkrieg verstorben

2 = während des Ersten Weltkriegs verstorben

3 = gestorben zwischen dem Ende des 1. Weltkrieg und Anfang 2. Weltkrieg 

4 = während des Zweiten Weltkriegs verstorben

5 = unabhängig des Zweiten Weltkriegs nach 1945 verstorben

6 = lebt bis zur Erstellung dieses Netzwerks (2020)


#### TYPE OF DEATH

Definiert die Todesursache.

1 = Vergasung 

2 = Fahrlässige Tötung im KZ 

3 = Natürlicher Tod

4 = überlebt

#### PLACE OF DEATH

Definiert den Todesort.

1 = KZ Bergen-Belsen

2 = Birsfelden

3 = KZ Auschwitz-Birkenau

5 = Transport nach Theresienstadt

6 = KZ Mauthausen

7 = KZ Neuengamme

8 = Anderer Todesort

9 = Amsterdam

#### TYPE

Definiert den Typ des Knotens.

1 = Mensch

2 = Gegenstand (Tagebuch)

#### RESIDENT

Definiert die Bewohner des Hinterhaus.

1 = Hinterhausbewohner

2 = kein Hinterhausbewohner

#### VERRÄTER

1 = potenzieller Verräter

2 = kein potenzieller Verräter
