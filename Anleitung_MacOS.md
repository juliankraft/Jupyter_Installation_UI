### Intel oder M1/M2
Bist du dir unsicher ob du einen M1/M2 Chip oder einen Intel Prozessor besitzt? 

Überprüfe dies bevor du den Download startest. Ganz oben links auf deinem Desktop siehst du das <span style="color: #FF5733">Apple Symbol</span>. Klicke dort drauf -> <span style="color: #FF5733">Über diesen Mac.</span> Bei der Rubrik Chip siehst du deinen Prozessor.


### Python herunterladen

Führe das Programm aus klicke auf weiter und akzeptieren. Es sollte automatisch die Datei richtig abspeichern.<br>
https://www.python.org/ftp/python/3.11.5/python-3.11.5-macos11.pkg

### R installieren
Hier kannst du R herunterladen, wähle dabei die version Intel oder Apple silicon (M1/M2) aus.<br>
https://cran.r-project.org/bin/macosx/<br>

Führe das Programm aus klicke auf weiter und akzeptieren. Es sollte automatisch die Datei richtig abspeichern.


### Jupyterlab einrichten
```bash
pip install jupyterlab
```
```bash
R
```
```bash
install.packages('IRkernel', repos='http://cran.us.r-project.org')
```

```bash
q()
```
```bash
sudo R -e "install.packages('IRkernel', repos='http://cran.us.r-project.org')"
```
Tippe nun dein Mac Passwort ein (es ist nicht sichtbar das du schreibst)


### R Pakete 
Nun werden wir alle Pakete installieren, die du für dein Studium brauchst.:

```bash
R
```
```bash
install.packages('ggplot2', repos='http://cran.us.r-project.org')
```
```bash
install.packages('devtools', repos='http://cran.us.r-project.org')
```
```bash
install.packages('pak', repos = sprintf('https://r-lib.github.io/p/pak/stable/%s/%s/%s', .Platform$pkgType, R.Version()$os, R.Version()$arch), clean = TRUE)
```


### Test
Um zu testen ob alles funktioniert hat tippe bitte q() um die R Umgebung zu verlassen.<br>
Tippe nun:
```bash
jupyter lab
```

Es sollte sich automatisch ein Browser öffnen.