## 1. Was bringt mehr Speicherersparnis? Ein "UHD-1 4k" Bild anstatt in Farben (RGB) in Graustufen (Y) abzuspeichern oder das "UHD-1 4k" Bild auf ein "HD720" Bild herunter zu skalieren?

Beide bringen dieselbe Speicherersparnis

## 2. Kann man durch die Bildumwandlung vom RGB- in den YCbCr-Farbraum bereits Speicherplatz einsparen?

Nein, die Umwandlung von RGB in YCbCr spart noch keinen Speicher – erst das Subsampling (z. B. 4:2:0) tut das.

## 3. Berechnen sie für folgendes Subsamplingvarianten die Speichereinsparung in % gegenüber dem Original: "4:4:4", "4:2:2", "4:1:1", "4:2:0".

Speicherersparnis im Vergleich zu 4:4:4:

4:4:4 → 0 % Ersparnis

4:2:2 → ca. 33 % Ersparnis

4:1:1 → ca. 50 % Ersparnis

4:2:0 → ca. 50 % Ersparnis

## 4. Warum verschlechtert sich die Bildschärfe von 4:1:1-Subsampling gegenüber 4:4:4-Subsampling nicht?

Weil das menschliche Auge Farben weniger genau wahrnimmt als Helligkeit.

## 5. Warum bilden sich bei der JPG-Bildkompression (DCT) bei sehr starker Komprimierung sogenannte Block-Artefakte?

Weil bei starker Komprimierung zu viele Details pro 8x8-Block verloren gehen – man sieht dann Kanten/Blöcke.

## 6. Was versteht man unter der Bezeichnung GOP25?

GOP25 heisst: Eine Gruppe von 25 Bildern, davon ist 1 ein I-Frame, die anderen sind P- oder B-Frames.





