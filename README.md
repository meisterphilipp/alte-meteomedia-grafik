# Alte Meteomedia Grafik

Diese WebApp soll die inzwischen nicht mehr verfügbare Ansicht von wetterstationen.meteomedia.de nachbauen:

<img width="400" alt="grafik" src="https://github.com/user-attachments/assets/70745e6a-00b1-4b77-b14d-8281c112f1e4" />

## Nutzung

Die Datei app.html herunterladen und in einem Browser öffnen. Nach auswahl der Station wird die ID an die URL angehängt, damit kann diese auch als Bookmark gespeichert werden.

## Ansicht

So sieht derzeit die App aus:

<img width="630" height="516" alt="grafik" src="https://github.com/user-attachments/assets/91dc2c83-1b3f-4743-94b1-ea23b4b5bf12" />


## Informationen

Da die API Endpoints von DWD keine CORS Header setzen, müssen wir die Inhalte über einen CORS-Proxy laden. Falls dieser irgendwann nicht mehr verfügbar ist oder funktioniert, klappt die ganze App nicht. Außerdem werden JS Bibiliotheken von cdn.jsdelivr.net geladen. 
