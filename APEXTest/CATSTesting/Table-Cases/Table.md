---
# required metadata
title: You can create tables by assembling a list of words and dividing them with hyphens | Microsoft Docs
ms.prod: .net
ms.technology: 
---

Tabellen in Ihrem Content verwenden
---
Sie können Tabellen erstellen, indem Sie eine Liste zusammenstellen || von Wörtern und dividiert durch Bindestriche - (für die erste Zeile) und dann jede Spalte durch eine Pipe |

## Normaler Tisch
| 1_Normaler Tisch | Beschreibung |
| ------------- | ----------- |
| 1_Hilfe | Zeigt das Hilfefenster an.
| Schließen | _Close_ ein Fenster |


## Tabelle mit Zelle fehlt
2_Zelle fehlt | Zweiter Header
------------- | -------------
2_Content-Zelle | Inhaltszelle
   |
Inhaltszelle | Inhaltszelle
Inhaltszelle | Inhaltszelle


## Tabelle mit Zelle fehlt
| 3_table mit Zelle fehlt | Beschreibung | row3 |
| ------------- | ----------- | --------- |
| 3_Hilfe | Zeigt das Hilfefenster an.
| Schließen | _Close_ ein Fenster |

## Tabelle mit Zelle fehlt
<table>
<thead>
<tr>
<th>Normal table</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>1_Help</td>
<td>Display the help window.</td>
</tr>
<tr>
<td>Close</td>
</tr>
</tbody>
</table>

## Tabelle mit leerer Zeile

| 4_empty row | Description          |
| ------------- | ----------- |
|      | 4_Display the help window.|
|      | _Closes_ a window     |
|      |    |

## Tabelle mit leerer Zeile (von desighed)

| | |
| ------------- | ----------- |
| 5_Die erste Zeile ist leer | Zeigt das Hilfefenster an.
| Schließen | _Close_ ein Fenster |


## Tabelle mit leerer Spalte

| | 6_ Leere Spalte | Richtig ausgerichtet |
| : ------------ |: ---------------: | -----: |
| | 6_some wordy Text | $ 1600 |
| | zentriert | 12 $ |
| | sind ordentlich | $ 1 |


## Tabelle mit leerer Spalte

| 6_ Leere Spalte | | |
| : ------------ |: ---------------: | -----: |
| 6_some wordy Text | | |
| sind ordentlich | | |

## Tabelle mit leerer Zeile und Spalte

| 6_ Leere Spalte | | |
| : ------------ |: ---------------: | -----: |
| 6_some wordy Text | | |
| | | |
| sind ordentlich | | |

## Tabelle mit nur Bild (er) in ganzen Zeilen oder Spalten

| ![smile](Images\flower.jpg) | Only images on Row/Column |
| ------------- | ----------- |
| ![smile](Images\flower.jpg)  | 7_Display the help window. |
| ![smile](Images\flower.jpg)  | _Closes_ a window        |
| ![smile](Images\flower.jpg)    | ![smile](Images\flower.jpg)   |



## Die Tabelle ist breiter als der Hauptinhalt
| Tabelle ist breiter als der Hauptinhalt | Verwandte Links | Beschreibung |
| --------------------- | ------------- | ----------- |
| 8_ProjectDesignerpageqwqqqqqqqqqqqqqqqqqqqqqqqqqqsdfssdsdffsdfqqqqqqqqqqqqqqqqq | Verwandte Links | Beschreibung |

## Html Syntax-Tabelle
<table width='1880px'>
<tr>
 <th width='200'>
 aa
 </th>
  <th width='880'>
 aa
 </th>
  <th width='500'>
 aa
 </th>
  <th width='500'>
 aa
 </th>
</tr>
<tr>
 <td>
 bb
 </td>
 <td>
 bb
 </td>
 <td>
 bb
 </td>
 <td>
 bb
 </td>
</tr>
</table>

