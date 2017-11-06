# Liste
## Ungeordnete Liste
### Aufzählungsliste mit leerem Artikel
* aaa
* bbb
*
* CCC


### Aufzählung beginnt mit "* + -"
* aaa
+ bbb
- CCC
* `` `Am 3. Juli nahmen die Black Knights, ein Geschwader von Marine Corps F / A-18 Hornets, teil```
+

### Fehler verifizieren, wenn nach "*" / "+" / "-" kein Einzug erfolgt
* | Normaler Tisch | Beschreibung |
   | ------------- | ----------- |
   | 1_Hilfe | Zeigt das Hilfefenster an.
   | Schließen | _Close_ ein Fenster |
* b
* | Normaler Tisch | Beschreibung |
   | ------------- | ----------- |
   | 1_Hilfe | Zeigt das Hilfefenster an.
   | Schließen | _Close_ ein Fenster |

### Fehler verifizieren, wenn nach "*" / "+" / "-" kein Einzug erfolgt
* aaa
1. Test1
2. Test2
* bbb
* CCC

## Bestellliste
### geordnete Liste mit leerem Artikel
1. aaa
2.
3. bbb
4.cc


### Bild als verschachteltes Listenelement überprüfen
1. aaa1
	* ![I am flower](./Images/flower.jpg "This is A/t text")
	* ![I am flower](./Images/flower.jpg "This is A/t text")
	* 
3. test
	7. hhh
	9. 
4. test
5. 
	
### Bild als Listenelement überprüfen
1. ![I am flower](./Images/flower.jpg "This is A/t text")
2. aaaa
3. 
4. cccc

### Überprüfen Sie die geschachtelte Liste
1. aaa
	* bbb
	* eee
	*  

### Liste der geschachtelten Nachrichten überprüfen
1. aaa
	3. > [!NOTE] Beispielbenachrichtigungsnachricht
	2. 
2. 
2. bbb

### Überprüfen Sie die geschachtelte Liste
1. aaa	
* bbb	
* eee	
*  ![Flower](/Image/Flower.jpg)
3. ccc
	7. hhh
	9. kkk
	
### Überprüfen Sie die Bilderliste
1.  ![Flower](/Image/Flower.jpg)
2. aaaa
3. 
4. cccc

### Überprüfung der Alert-Nested-Liste
> [! TIPP]
> Aufzählungsliste mit leerem Artikel
> * aaa
> * bbb
> *

### Liste der verschachtelten Nachrichten überprüfen
1. aaa
> 3. > [! HINWEIS]
> Beispielbenachrichtigungsnachricht
> 2. > [! WARNUNG]
> Beispielwarnung
2.
2. bbb

### Code-Auszug
1. abc
> 1.
test1
> 2.
test2
> 3.

2. abc

### Tabellen-Nested-Liste überprüfen
| Table nest Liste | Beschreibung | Unterstützte Vorlagen |
| ------------- | ----------- | ------------------- |
| Projektvorlagen | Projekttypen, die im Dialogfeld ** Neues Projekt ** verfügbar sind. | <Ul> <li> F # -Anwendung <br /> </ li> <li> <br /> </ li> <li> F # Tutorial <br /> </ li> <li> Tragbare Bibliothek F # <br /> </ li> <ul /> |
