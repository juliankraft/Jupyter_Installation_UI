https://cran.r-project.org/bin/macosx/


For Apple silicon (M1/M2) Macs:
R-4.3.1-arm64.pkg
SHA1-hash: 14c018ff54f7f5bb37c1d96b33207343b83e9345
(ca. 90MB, notarized and signed)
 
For older Intel Macs:
R-4.3.1-x86_64.pkg
SHA1-hash: 1af8f055a601d5de5dfefdb3956ecc8f745c2401
(ca. 92MB, notarized and signed)

pip install jupyterlab


R
install.packages('IRkernel', repos='http://cran.us.r-project.org')
dannach
q()
sudo R -e "install.packages('IRkernel', repos='http://cran.us.r-project.org')"
Tippe nun dein Mac Passwort ein (es ist nicht sichtbar das du schreibst)

Nun werden wir alle Pakete installieren, die du für dein Stuium brauchst.:

Tippe zuerst R ein, um die Programmiersprache zu öffnen!

install.packages('ggplot2', repos='http://cran.us.r-project.org')

install.packages('devtools', repos='http://cran.us.r-project.org')

install.packages('ggplot2', repos='http://cran.us.r-project.org')

install.packages('pak', repos = sprintf('https://r-lib.github.io/p/pak/stable/%s/%s/%s', .Platform$pkgType, R.Version()$os, R.Version()$arch), clean = TRUE)


Um zu testen ob alles funktioniert hat tippe bitte q() um die R Umgebung zu verlassen.
Tippe nun:
jupyter lab

Es sollte sich automatisch ein Browser öffnen