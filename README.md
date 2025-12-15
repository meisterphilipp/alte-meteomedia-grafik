# Alte Meteomedia Grafik

Diese WebApp soll die inzwischen nicht mehr verfügbare Ansicht von wetterstationen.meteomedia.de nachbauen:

<img width="400" alt="grafik" src="https://github.com/user-attachments/assets/70745e6a-00b1-4b77-b14d-8281c112f1e4" />

## Nutzung

Über diesen Link: https://meisterphilipp.github.io/alte-meteomedia-grafik/app.html - Alternativ kann die Datei app.html heruntergeladen und in einem Browser geöffnet werden.

Nach auswahl der Station wird die ID an die URL angehängt, damit kann diese auch als Bookmark gespeichert werden.

## Ansicht

So sieht derzeit die App aus:

<img width="845" height="524" alt="grafik" src="https://github.com/user-attachments/assets/6e081e92-8242-4b7d-9456-6d9d08e9cfe3" />


## Informationen

Da die API Endpoints von DWD keine CORS Header setzen, müssen wir die Inhalte über einen CORS-Proxy laden. Falls dieser irgendwann nicht mehr verfügbar ist oder funktioniert, klappt die ganze App nicht. Außerdem werden JS Bibiliotheken von cdn.jsdelivr.net geladen. 
