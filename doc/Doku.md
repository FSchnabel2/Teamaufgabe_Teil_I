# Aktien-Ticker

## Einleitung
In der heutigen Zeit, in der Finanzwissen für die persönliche und berufliche Entwicklung unerlässlich geworden ist, ist es wichtig, dass junge Menschen ein grundlegendes Verständnis für den Aktienmarkt erlangen. Unser Projekt „Aktien-Ticker“ zielt darauf ab, eine innovative und interaktive Plattform zu schaffen, die Schüler und interessierte Nutzer in die Welt der Finanzen einführt. Durch den Einsatz von Echtzeitdaten und KI-Analysen möchten wir eine ansprechende Benutzererfahrung bieten, die das Lernen fördert und den Nutzer in die Lage versetzt, fundierte Entscheidungen im Finanzbereich zu treffen.

## Definition
- Mit einem **Video-Slider aktuelle Aktien-, Rohstoff- und Indizeskurse** in Echtzeit anzeigen.
- **API zur Abfrage von Finanzdaten** integrieren, um verlässliche Informationen bereitzustellen.
- **API von OpenAI** verwenden, die Vorhersagen von Preisbewegungen basierend auf historischen Daten und Marktanalysen durchführt.

## Umsetzung
1. **Technologien**:
   - **Backend**: Java, um die serverseitige Logik und die Integration mit der Finanzdaten-API zu verwalten.
   - **Frontend**: HTML, CSS, JavaScript, um eine benutzerfreundliche Oberfläche zu erstellen.
   - **Datenquelle**: API für Finanzdaten (Alpha Vantage) zur Abfrage von Echtzeitkursen.
2. **Funktionen**:
   - **Echtzeit-Aktienkurse**: Anzeige von aktuellen Kursen für Aktien, Rohstoffe und Indizes.
   - **Slider-Funktion**: Implementierung eines Video-Sliders, der alle 15 Sekunden automatisch zwischen verschiedenen Seiten wechselt, um die unterschiedlichen Kurse anzuzeigen.
   - **Benachrichtigungen**: Möglichkeit für Benutzer, Mitteilungen über stark steigende oder fallende Kurse zu erhalten, um sie über wichtige Marktbewegungen zu informieren.
   - **Ansprechendes Design**: Sicherstellung eines ansprechenden und intuitiven Designs, das die Benutzererfahrung fördert.
3. **Integration von KI**:
   - **Vorhersage von Kursbewegungen**: Verwendung der OpenAI-API (https://platform.openai.com/docs/overview) zur Analyse historischer Daten und aktuellen Trends, um Vorhersagen über zukünftige Preisbewegungen zu erstellen.
   - **Anpassung der Vorhersagen**: Möglichkeit zur Anpassung von Vorhersagen basierend auf verschiedenen Parametern (z. B. wirtschaftliche Indikatoren, Markttrends).
4. Benutzerinteraktion:
   - **QR-Code für Mobile-App-Download**: Rechts unten am Bildschirm einen großen QR-Code platzieren, der auf den Download der Mobile-App verweist.
   - **Interaktive Chart-Auswahl**: Benutzer können durch Scannen von spezifischen QR-Codes, die in der App integriert sind, Charts auswählen und speichern, um sie später zu beobachten.
   - **Verbindung zwischen Video-Slider und App**: Die im Video-Slider angezeigten Kurse und Informationen können durch spezifische QR-Codes in der App abgerufen werden, um eine konsistente Benutzererfahrung zu gewährleisten. Benutzer können die gewünschten Aktien oder Indizes scannen, um sie in der App zu speichern und zu verfolgen.
   - **Alarme und Benachrichtigungen**: Möglichkeit für Benutzer, Preisalarme zu setzen und Benachrichtigungen über wichtige Änderungen zu erhalten.

## Zielsetzung
Durch die Entwicklung des Aktien-Tickers sollen Schüler und interessierte Benutzer in die Welt der Finanzen eingeführt werden. Die Anwendung soll:
1. **Wissen vermitteln**: 
    - Den Nutzern helfen, ein grundlegendes Verständnis für den Aktienmarkt und die Preistrends zu entwickeln.
    - **Messbare KPI**: Mindestens 75 % der Nutzer sollen nach der Nutzung der App angeben, ein besseres Verständnis für Aktienkurse und Marktentwicklungen zu haben.
2. **Interaktive Erfahrungen bieten**:
   - Durch die Kombination von realen Daten und KI-Analysen eine ansprechende und lehrreiche Benutzererfahrung schaffen.
   - **Messbare KPI**: Mindestens 100 Nutzer sollen die App innerhalb von drei Monaten nach dem Launch heruntergeladen haben und mindestens 50 Nutzer sollen innerhalb von zwei Monaten Kursalarme setzen.
3. **Nutzerbindung fördern**: 
   - Durch die Möglichkeit, Charts zu speichern und Alarme zu setzen, eine langfristige Nutzerbindung aufbauen.
   - **Messbare KPI**: Nach den ersten drei Monaten sollen mindestens 30 % der Nutzer regelmäßig (mindestens einmal pro Woche) die App nutzen.

## Projektorganisation
1. **Teamzusammensetzung** (Rollen):
   - **Projektauftraggeber**: HAK Imst (Prof. Strigl)
   - **Projektleiter und Backend-Entwickler**: Paul Summerauer
   - **Projektmitarbeiter (Frontend-Entwickler)**: Pius Rauch
   - **Projektmitarbeiter (Designer und Backend-Entwickler)**: Fabian Holzknecht
   - **Kunden**: Alle Schüler, Lehrer und sonstige Personen an der Schule
2. **Form der Zusammenarbeit**: 
**Matrix-Projekt-Organisation**, weil sie interdisziplinäre Zusammenarbeit fördert, Flexibilität in der Aufgabenverteilung ermöglicht und eine optimale Nutzung der Ressourcen gewährleistet. Zudem stärkt sie die Kommunikation und Verantwortlichkeit im Team, was für die erfolgreiche Umsetzung des Aktien-Ticker-Projekts entscheidend ist.
3. **Zeitrahmen**:
   - Zuerst genaue Planung der Geschäftslogik, dann die Ressourcenanschaffungen (siehe Punkt Ressourcen), dann die Strukturierung (z. B. Klassenhierarchien), dann die Entwicklung, Tests und Veröffentlichung.
   - Vorgegebener Termin der Lehrpersonen
4. **Benötigte Ressourcen**:
   - IntelliJ Ultimate/Community Edition (neueste)
   - JDK (neueste)
   - Git-Installation
   - GitHub-Link
   - API-Lizenzen
   - Zugang zum Schulserver, der die Bilder und Videos auf dem Bildschirm im Schuleingangsbereich einspielt.
   - Plan zur Verwaltung von API-Schlüsseln und Zugangskontrollen für die App zur Gewährleistung der Sicherheit.
5. **Testphase**:
   - Durchführung von Tests, um sicherzustellen, dass die Anwendung stabil und benutzerfreundlich ist.
   - Feedback-Runde zur Sammlung von Verbesserungsvorschlägen und Nutzererfahrungen während der Testphase.
6. **Risiken und Herausforderungen**:
   - Mögliche Herausforderungen bei der Integration der APIs und der Gewährleistung von Echtzeitdaten.
   - Technische Probleme bei der Bereitstellung der Anwendung auf dem Schulserver.
   - Strategie zur regelmäßigen Überprüfung und Aktualisierung der API-Keys und Sicherheitsmaßnahmen.

Paul Summerauer, Fabian Holzknecht, Pius Rauch