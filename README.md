# car-counter-prototype
The first shot of the mobile app car counter - just for training, lets count cars in an mp4 runing on a normal PC

Many thanks to  Cade Gallagher for the provided video who provided it for free here: 
https://www.pexels.com/de-de/video/autos-auf-der-autobahn-1171461/


Project Setup for now:
ein Video einliest,
MobileNet SSD nutzt,
IDs ab 0 vergibt,
und die Anzahl der vergebenen IDs anzeigt?

Project Setup for the future on the mobile:
Kamera-Stream → Frames an Modell.
MobileNet SSD erkennt Autos → Bounding Boxes.
Tracking: IDs vergeben (SORT).
Counting: Wenn ID die Linie überquert → Zähler hoch.
UI: Live-Anzeige der Zähler.