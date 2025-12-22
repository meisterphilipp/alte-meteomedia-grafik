# Alte Meteomedia Grafik

Diese WebApp soll die inzwischen nicht mehr verfügbare Ansicht von wetterstationen.meteomedia.de nachbauen:

<img width="400" alt="grafik" src="https://github.com/user-attachments/assets/70745e6a-00b1-4b77-b14d-8281c112f1e4" />

## Nutzung

Über diesen Link: https://meisterphilipp.github.io/alte-meteomedia-grafik/app.html - Alternativ kann die Datei app.html heruntergeladen und in einem Browser geöffnet werden.

Nach auswahl der Station wird die ID an die URL angehängt, damit kann diese auch als Bookmark gespeichert werden.

## Ansicht

So sieht derzeit die App aus:

<img width="852" height="614" alt="grafik" src="https://github.com/user-attachments/assets/5fe80ecd-a041-4fae-bd19-2f2d7d849596" />


## Informationen

Da die API Endpoints von DWD keine CORS Header setzen, müssen wir die Inhalte über einen CORS-Proxy laden. Falls dieser irgendwann nicht mehr verfügbar ist oder funktioniert, klappt die ganze App nicht. Außerdem werden JS Bibiliotheken von cdn.jsdelivr.net geladen. 
