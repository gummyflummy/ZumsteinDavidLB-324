# LB 324

## Aufgabe 2
Erklären Sie hier, wie man `pre-commit` installiert.
Um die pre-commits auszuführen müssen sie folgendes im cmd machen: zuerst müssen sie zu ihrem Wurzelverzeichnis mit "CD .....". Danach müssen sie folgendes eingeben: pip install pre-commit black pytest. Damit haben sie alles installiert und sie sollten es eingerichtet haben.

## Aufgabe 4
Erklären Sie hier, wie Sie das Passwort aus Ihrer lokalen `.env` auf Azure übertragen.
URL: zumsteindavidlb-324.azurewebsites.net 
Um das Passwort aus der lokalen .env zu übertragen habe ich erstmals geschaut welches Passwort in der .env Datei definiert ist. Bei meinem Fall ist es "einSehrGeheimesPasswort". Anschliessend habe ich dann bei meiner Azure Web App unter konfigurationen eine neue Anwendungseinstellung erstellt mit dem Namen PASSWORD und dem Wert einSehrGeheimesPasswort und voila nach dem Speichern ist es done.