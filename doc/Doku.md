# Aktien-Ticker

## Definition
- Mit einem Video-Slider aktuelle Aktien-, Rohstoff- und Indizienkurse in Echtzeit anzeigen.
- API zur Abfrage von Finanzdaten 
- KI-API verwenden, die die Vorhersage von Preisbewegungen basierend auf historischen Daten und Marktanalysen durchführt.

## Umsetzung
1. Technologien:
   - Backend: Java, um die serverseitige Logik und die Integration mit der Finanzdaten-API zu verwalten.
   - Frontend: HTML, CSS, JavaScript, um eine benutzerfreundliche Oberfläche zu erstellen.
   - Datenquelle: API für Finanzdaten (Alpha Vantage) zur Abfrage von Echtzeitkursen.
2. Funktionen:
   - Echtzeit-Aktienkurse: Anzeige von aktuellen Kursen für Aktien, Rohstoffe und Indizes.
   - Slider-Funktion: Implementierung eines Video-Sliders, der alle 15 Sekunden automatisch zwischen verschiedenen Seiten wechselt, um die unterschiedlichen Kurse anzuzeigen.
   - Ansprechendes Design: Sicherstellung eines ansprechenden und intuitiven Designs, das die Benutzererfahrung fördert.
3. Integration von KI:
   - Vorhersage von Kursbewegungen: Verwendung der OpenAI-API (https://platform.openai.com/docs/overview) zur Analyse historischer Daten und aktuellen Trends, um Vorhersagen über zukünftige Preisbewegungen zu erstellen.
   - Anpassung der Vorhersagen: Möglichkeit zur Anpassung von Vorhersagen basierend auf verschiedenen Parametern (z. B. wirtschaftliche Indikatoren, Markttrends).
4. Benutzerinteraktion:
   - QR-Code für Mobile-App-Download: Rechts unten am Bildschirm einen großen QR-Code platzieren, der auf den Download der Mobile-App verweist.
   - Interaktive Chart-Auswahl: Benutzer können durch Scannen von spezifischen QR-Codes, die in der App integriert sind, Charts auswählen und speichern, um sie später zu beobachten.
   - Alarme und Benachrichtigungen: Möglichkeit für Benutzer, Preisalarme zu setzen und Benachrichtigungen über wichtige Änderungen zu erhalten.

## Zielsetzung
Durch die Entwicklung des Aktien-Tickers sollen Schüler und interessierte Benutzer in die Welt der Finanzen eingeführt werden. Die Anwendung soll:
- Wissen vermitteln: Den Nutzern helfen, ein grundlegendes Verständnis für den Aktienmarkt und die Preistrends zu entwickeln.
- Interaktive Erfahrungen bieten: Durch die Kombination von realen Daten und KI-Analysen eine ansprechende und lehrreiche Benutzererfahrung schaffen.
- Nutzerbindung fördern: Durch die Möglichkeit, Charts zu speichern und Alarme zu setzen, eine langfristige Nutzerbindung aufbauen.

## Projektorganisation
1. Teamzusammensetzung (Rollen):
   - Projektleiter und Backend-Entwickler: Paul Summerauer
   - Frontend-Entwickler: Pius Rauch
   - Designer und Backend-Entwickler: Fabian Holzknecht
2. Zeitrahmen:
   - Zuerst genaue Planung der Geschäftslogik, dann die Ressourcenanschaffungen (siehe Punkt Ressourcen), dann die Strukturierung (z. B. Klassenhierarchien), dann die Entwicklung, Tests und Veröffentlichung.
   - Vorgegebener Termin der Lehrpersonen
3. Benötigte Ressourcen:
   - IntelliJ Ultimate/Community Edition (neueste)
   - JDK (neueste)
   - Git-Installation
   - GitHub-Link
   - API-Lizenzen
   - Zugang zum Schulserver, der die Bilder und Videos auf dem Bildschirm im Schuleingangsbereich einspielt.
4. Testphase:
Durchführung von Tests, um sicherzustellen, dass die Anwendung stabil und benutzerfreundlich ist, gefolgt von einer Feedback-Runde, um Verbesserungsvorschläge zu sammeln.