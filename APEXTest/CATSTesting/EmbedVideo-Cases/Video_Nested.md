# Video von verschachtelt
## video nest in der Tabelle (mit Text)
>|1|2|
>| ------------- | ----------- |
>|<iframe width="420" height="315" src="https://www.youtube.com/embed/iyT1uILEI2U" frameborder="0" allowfullscreen></iframe>| Das ist Video gut spielbar|
>|<iframe width="420" height="315" src="https://www.youtube.com/embed/iyT1uIL" frameborder="0" allowfullscreen></iframe>| Das ist Video kann nicht gut spielen|

## video nest in der Tabelle (nur Video in der Tabelle)
>|<iframe width="420" height="315" src="https://www.youtube.com/embed/iyT1uILEI2U" frameborder="0" allowfullscreen></iframe>|
>| ------------- | 
>|<iframe width="420" height="315" src="" frameborder="0" allowfullscreen></iframe> |

## Video-Nest in der Liste (mit Text)
>1. <iframe width="420" height="315" src="https://www.youtube.com/embed/iyT1uILEI2U" frameborder="0" allowfullscreen></iframe> 
>2. Das ist eine Liste
>3. <iframe width="420" height="315" src="https://www.youtube.com/embed/iyT1" frameborder="0" allowfullscreen></iframe> 

## Video-Nest in der Liste (nur Video in der Liste)
>1. <iframe width="420" height="315" src="https://www.youtube.com/embed/iyT1uILEI2U" frameborder="0" allowfullscreen></iframe>
>1. <iframe width="420" height="315" src="https://www.youtube.com/embed/iyT1" frameborder="0" allowfullscreen></iframe>

## Video-Nest im Code (mit Text)
>```
>Das ist Code-Text
>[!VIDEO https://sec.ch9.ms/ch9/f882/07d5474f-4235-4d89-90bc-ed008b98f882/WAMFAAnnimated_high.mp4]
>```

## Video-Nest im Code (nur Video)
>```
><iframe width="420" height="315" src="https://www.youtube.com/embed/iyT1uILEI2U" frameborder="0" allowfullscreen></iframe>
>``` 

## Video-Nest in Alert (Video)
> [!NOTE] 
> [!VIDEO https://sec.ch9.ms/ch9/f882/07d5474f-4235-4d89-90bc-ed008b98f882/WAMFAAnnimated_high.mp4]

## Videoschacht in Alert (iframe)
> [!NOTE] 
> <iframe width="420" height="315" src="https://www.youtube.com/embed/iyT1uILEI2U" frameborder="0" allowfullscreen></iframe>

## Ungültiges Video-Nest in Alert (iFrame)
> [!NOTE] 
> <iframe width="420" height="315" src="https://www.youtube.com/embed/iyT" frameborder="0" allowfullscreen></iframe>
