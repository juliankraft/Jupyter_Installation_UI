# Anleitung zur Installation von R-Packages

Da ihr R als Administratoren installiert habt, habt ihr keinen uneingeschränkten Zugriff auf die library. Das heisst, dass ihr nicht einfach mit `install.packages("package")` ein Package installieren könnt. Ihr müsst das als Administrator machen.

Ihr habt 3 Möglichkeiten ein Packet zu installieren wobei ich euch die 3. empfehle:

1. Ihr startet R als Administrator. Das heist rechtsklick auf das R Symbol auf dem Bildschirm oder im Startmenü und dann "Als Administrator ausführen". Dann könnt ihr einfach `install.packages("package")` ausführen. Dann müsst ihr noch eine Quelle für den Download auswählen.

2. Ihr öffnet das CMD als Administrator und gebt `R` ein. Nun seid ihr in einer R Konsole mit Administratorrecht da gebt ihr ein: `install.packages("package")`. Und wählt eine Quelle für den Download aus.

3. Ihr öffnet das CMD als Administrator und führt dort folgenden Befehl aus:<br> `R -e "install.packages('package', repos='https://stat.ethz.ch/CRAN//')"`.
