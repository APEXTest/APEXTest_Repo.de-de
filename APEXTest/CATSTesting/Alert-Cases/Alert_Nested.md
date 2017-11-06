

## Benachrichtigung mit Link (Nest)

> [!NOTE] 
> Nest mit externem Link [baidu] (http://www.baidu.com/) Nest mit externem Link

> [!WARNING] 
> [baidu] (http://www.baidus.com/) Verschachtelung mit ungültigem externen Link+

> [!TIP] 
> Nest mit externem Link [baidu] (http://www.baidu.com/)

> [!IMPORTANT] 
> Nest mit internem Link [InternalLink] (Link.md) Nest mit internem Link

> [!CAUTION] 
> Verschachtelung mit internem Link [BookMark] (# Alarm ohne Nachricht)

## Nur mit Link melden
> [!WARNING] 
> [baidu](http://www.baidus.com/) 

## Alarm mit Bild
> [!NOTE] 
>  Text vor dem Bild
> ![Ich bin Blume](./../Reference-Files/Images/flower.jpg "This is title")
>  Text nach Bild

> [!WARNING] 
> ![Ich bin Blume](./../Reference-Files/Images/flower.jpg "This is title")
>  Text nach Bild

> [!TIP] 
>  Text vor dem Bild
> ![Ich bin Blume](./../Reference-Files/Images/flower.jpg "This is title")

> [!IMPORTANT] 
> Externes Bild
> <img src="http://pic33.nipic.com/20130916/3420027_192919547000_2.jpg" width = "860" height ="645"/>

> [!CAUTION] 
> Ungültige Bildquelle
> ![flower](./../Reference-Files/Images/flowers.jpg)

## Nur mit Bild alarmieren
> [!TIP]
> ![](./../Reference-Files/Images/flower.jpg)

## Nur mit Bild und Code benachrichtigen
> [!TIP]
> ![](./../Reference-Files/Images/flower.jpg)
>```
> Am 2. Juli drang ein außerirdisches Schiff in die Umlaufbahn der Erde ein und setzte mehrere Dutzend untertassenförmige "Zerstörer" -Raumfahrzeuge ein, die alle 15 Meilen (24 km) breit waren.
> Am 3. Juli nahmen die Black Knights, ein Geschwader von Marine Corps F / A-18 Hornets, teil
>```


> [!TIP]
> ![I am flower](./../Reference-Files/Images/flower.jpg "This is A/t text")

## Nur mit code alarmieren
> [!NOTE] 
>```
> Am 2. Juli betrat ein außerirdisches Schiff die Erdumlaufbahn und setzte mehrere Dutzend untertassenförmige "Zerstörer" -Raumfahrzeuge ein, die alle 15 Meilen (24 km) breit waren.
> Am 3. Juli nahmen die Black Knights, ein Geschwader von Marine Corps F / A-18 Hornets, teil
>```

## Mit Code und Text benachrichtigen
>[!NOTE]  
> Dieser Teil ist Text!
>```
> Am 2. Juli betrat ein außerirdisches Schiff die Erdumlaufbahn und setzte mehrere Dutzend untertassenförmige "Zerstörer" -Raumfahrzeuge ein, die alle 15 Meilen (24 km) breit waren.
> Am 3. Juli nahmen die Black Knights, ein Geschwader von Marine Corps F / A-18 Hornets, teil
>```

## Mit der Liste benachrichtigen
> [!WARNING] 
> Aufzählung
>* aaa
>* bbb
>* ccc

> [!TIP] 
>Aufzählungsliste mit leerem Element
>* aaa
>* bbb
>* 
>* ccc 

> [!IMPORTANT] 
>Bestellliste mit leerem Artikel
>1. aaa
>2. 
>3. bbb
>4. ccc


> [!CAUTION] 
> Bestellliste mit ,
>1. aaa
>2, bbb
>3. ccc

> [!CAUTION] 
>Bestellliste mit 3.7.9
>3. aaa
>7. bbb
>9. ccc

## Nur mit der Liste OL alarmieren
> [!WARNING]  
>* aaa
>* bbb
>* ccc

## Warnung mit Null <P>
> [!WARNING]  
> <P>

## Nur mit Liste warnen
> [!WARNING] 
>1. aaa
>2. bbb
>3. ccc


## Mit Tisch alarmieren
> [!NOTE] 
> Normaler Tisch
>|1|2|3|
>|-------|------- |------- |
>|1|2|3|

## Nur mit Tisch alarmieren
> [!NOTE]
>|1|2|3|
>|-------|------- |------- |
>|1|2|3|

> [!WARNING] 
>Tisch mit Zelle fehlt
> Zelle fehlt | Zweiter Header
> ------------- | -------------
> Inhaltszelle | Inhaltszelle
> |
> Inhaltszelle | Inhaltszelle

> [!TIP] 
> Tisch mit leeren Zeilen
> | leere Zeile | Beschreibung |
> | ------------- | ----------- |
> | Hilfe | Zeigt das Hilfefenster an.
> | Schließen | _Close_ ein Fenster |
>|      |    |


> [!IMPORTANT] 
> Tisch mit leerer Reihe (von entworfen)
> | | |
> | ------------- | ----------- |
> | Die erste Zeile ist leer | Zeigt das Hilfefenster an.
> | Schließen | Schließt ein Fenster
>

> [!CAUTION] 
> Anormaler Tisch
> | Normaler Tisch | Beschreibung |
> | Hilfe | Zeigt das Hilfefenster an.
> | Schließen | _Close_ ein Fenster |


## Alert mit Tabelle, Link, Liste
> [!CAUTION] 
> Normale Tabelle mit ungültiger Liste
> | Normale Tabelle mit ungültiger Liste | Beschreibung |
> | ------------- | ----------- |
> | [bing.com] (http://www.bing.com) | Test |
> | Schließen | 1. item1 <br> 2. Item2 <br> 3. |

## Mit Tisch alarmieren
> [!CAUTION] 
> Hinweis
>> [! HINWEIS]
> | Normale Tabelle mit ungültiger Liste | Beschreibung |
> | ------------- | ----------- |
> | [bing.com] (http://www.bing.com) | ! [Blume] (./../ Referenzdateien / Bilder / Blume.jpg) |
> | >! [Blume] (./../ Referenz-Dateien / Bilder / Blumen.jpg) | 1. item1 <br> 2. Item2 <br> 3. |

### Geschachtelter Alarm
> [!NOTE] 
>>NoteHinweis
>>[!WARNING] 
>>Beispielwarnung


> [!NOTE]
> Am 2. Juli drang ein außerirdisches Schiff in die Umlaufbahn der Erde ein und setzte mehrere Dutzend tassenförmige "Zerstörer" -Raumfahrzeuge ein, die alle 15 Meilen (24 km) breit waren.
  
> Am 3. Juli nahmen die Black Knights, ein Geschwader von Marine Corps F / A-18 Hornets, teil


> [!NOTE]
> Am 2. Juli drang ein außerirdisches Schiff in die Umlaufbahn der Erde ein und setzte mehrere Dutzend tassenförmige "Zerstörer" -Raumfahrzeuge ein, die alle 15 Meilen (24 km) breit waren.
  
> Am 3. Juli nahmen die Black Knights, ein Geschwader von Marine Corps F / A-18 Hornets, teil


##Alert with table & list
>[!NOTE]
> | Table nest Liste | Beschreibung | Unterstützte Vorlagen |
> | ------------- | ----------- | ------------------- |
> | Projektvorlagen | Projekttypen, die im Dialogfeld ** Neues Projekt ** verfügbar sind. | <Ul> <li> F # -Anwendung <br /> </ li> <li> <br /> </ li> <li > F # -Tutorial <br /> </ li> <li> F # Portable Bibliothek <br /> </ li> <ul /> |
> | Objektvorlagen | Dateitypen im Dialogfeld ** Neues Objekt hinzufügen **. | <Ul> <li> F # Quelldatei (.fs) <br /> </ li> <li> F # Skript (.fsx ) <br /> </ li> <li> F # Signaturdatei (.fsi) <br /> </ li> <li> Konfigurationsdatei (.config) <br /> </ li> <li> SQL-Datenbankverbindung (LINQ-to-SQL-Typanbieter) <br /> </ li> <li> SQL-Datenbankverbindung (LINQ to Entities-Typanbieter) <br /> </ li> <li> OData-Dienstverbindung (LINQ-Typ-Provider) < br /> </ li> <li> WSDL-Dienstverbindung (Typanbieter) <br /> </ li> <li> XML-Datei (.xml) <br /> </ li> <li> Textdatei <br / > </ li> <ul /> |

> [!NOTE]
> Testlink
> https://zhidao.baidu.com/search?ct=17&pn=0&tn=ikaslist&rn=10&word=win8%E5%A6%82%E4%BD%95%E6%89%93%E5%BC%80screen%20reader%E5%BF%AB%E6%8D%B7%E9%94%AE

> [!NOTE]
><code>das ist ein Codebeispiel</code>

> [!NOTE]
> ```das ist ein Codebeispiel```

> [!NOTE]
><tr>das ist tr</tr>

> [!NOTE]
><td>das ist td</td>

> [!NOTE]
><th>das ist th</th>

> [!NOTE]
><em>das ist em</em>

> [!NOTE]
><b>das ist b</b>

> [!NOTE]
><li>das ist b</li>
><li>das ist li</li>

> [!NOTE]
> <iframe width="420" height="315" src="https://www.youtube.com/embed/iyT1uILEI2U" frameborder="0" allowfullscreen></iframe>

> [!NOTE]
>[!VIDEO https://www.youtube.com/embed/iyT1uILEI2U]
