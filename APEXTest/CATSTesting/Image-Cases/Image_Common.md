---
# required metadata
title: Images | Microsoft Docs
description: This topic provides a description of Anomaly detection policies and provides reference informati on about the building blocks of an anomaly detection policy.
keywords: list&meta
author: Ruixiang
ms.author: Ruixiang
manager: Yingjie
ms.date: 11/06/2016
ms.topic: article, title, English
ms.prod: .net-core
ms.service: 
ms.technology: Visual C++
ms.assetid: ab9bc377-d2f5-4f4c-a419-f1728a15d1c7

# optional metadata
#ROBOTS:
#audience:
#ms.devlang: en1111111
ms.reviewer: reutam
ms.suite: ems

#ms.tgt_pltfrm:
#ms.custom:
---

# Bild

### Das Bild wird normal mit Alt Text angezeigt

> ![I am flower](./../Reference-Files/Images/flower.jpg "This is title")

### Das Bild wird normal ohne Alt-Text angezeigt
  ![](./../Reference-Files/Images/flower.jpg)
  ![](./../Reference-Files/Images/flower.jpg)
  ![](./../Reference-Files/Images/flower.jpg)
    
### Das Bild wird normal mit Referenzeinsatz angezeigt
  ![Flower][Flower]
  [Flower]: ./../Reference-Files/Images/flower.jpg
  
### ungültiger Einfügestil
![flower][./../Reference-Files/Images/flower.jpg]


### Ungültige Bildquelle
![flower](./../Reference-Files/Images/flowers.jpg)

### Leere Bildquelle
![flower]()

### Das normale Bild mit zu großer Breite (externes Bild)
<img src="http://pic33.nipic.com/20130916/3420027_192919547000_2.jpg" width = "860" height ="645"/>


### Das normale Bild mit normaler Breite (externes Bild)
<img src="http://pic33.nipic.com/20130916/3420027_192919547000_2.jpg" width = "200" height ="100"/>


## Bild in der Tabelle

| ![smile](./../Reference-Files/Images/Flower.jpg) | Only images on Row/Column |
| ------------- | ----------- |
| ![smile](./../Reference-Files/Images/Flower.jpg)  | Display the help window. |
| ![smile](./../Reference-Files/Images/Flower.jpg)  | _Closes_ a window        |
| ![smile](./../Reference-Files/Images/Flower.jpg)    | ![smile](./../Reference-Files/Images/Flower.jpg)   |

## Bild in Alarmbereitschaft
> [!NOTE] 
>  Text vor dem Bild
> ![I am flower](./../Reference-Files/Images/flower.jpg "This is title")
>  Text nach Bild

## Bild in Benachrichtigung keine Nachricht
> [!WARNING] 
> ![](./../Reference-Files/Images/flower.jpg)
>  Text nach Bild

## Bild in Alarm ohne Titel
> [!TIP] 
>  Text vor dem Bild
> ![](./../Reference-Files/Images/flower.jpg "")


## Bild in Benachrichtigung keine Nachricht
> [!WARNING] 
> ![I am flower][111]
> [111]:./../Reference-Files/Images/flower.jpg
>  Text nach Bild

## Externes Bild
> [!IMPORTANT] 
> Externes Bild
> <img src="http://pic33.nipic.com/20130916/3420027_192919547000_2.jpg" width = "860" height ="645"/>

## Ungültige Quelle
> [!CAUTION] 
> Ungültige Bildquelle
> ![flower](./../Reference-Files/Images/flowers.jpg)

## Bild in der Liste
1. aaa
	* bbb
	* eee
	*  ![Flower](./../Reference-Files/Images/flower.jpg)
    
    
## Magier in der Liste
1.  ![Flower](./../Reference-Files/Images/flower.jpg)
2. aaaa
4. cccc

### Fehlerbild in der Liste
1. ![Flower](./../Reference-Files/Images/flowers.jpg)
2. bbb

## Externes Bild breiter als Hauptinhalt
> [!IMPORTANT] 
> External image
> <img src="http://pic33.nipic.com/20130916/3420027_192919547000_2.jpg" width = "1860" height ="1245"/>

## Bild als Linktext
[![Image](./../Reference-Files/Images/flower.jpg)](./../Reference-Files/Images/gif.gif)

[![Internallink](./../Reference-Files/Images/flower.jpg)](./../Image-Cases/index.md)

[![ExternalLink](./../Reference-Files/Images/flower.jpg)](http://www.baidu.com/)

[comment]: <> (![INT access rules (inbound)](./../Reference-Files/Images/flower.png))
[comment]: <> (![INT access rules (outbound)](./../Reference-Files/Images/flowerssss.png))
