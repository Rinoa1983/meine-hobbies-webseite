# 🌟 Mini-Projekt: Unsere Lieblingsdinge Website 🌟

## Aufgabenbeschreibung

In diesem Mini-Projekt werdet ihr eine kleine Website erstellen, die eure Hobbys und Lieblingsdinge zeigt. Die Website soll aus **zwei Seiten** bestehen und mit **HTML und CSS** gebaut werden.


## Schritt für Schritt Anleitung

### 1️⃣ GitHub-Repository einrichten

**Person A:**
- Erstelle ein neues Repository auf GitHub
- Nenne es z.B. "unsere-hobbys-website"
- Wähle "Public" und setze ein Häkchen bei "Initialize with README"
- Füge deine Teamkollegin/deinen Teamkollegen als Collaborator hinzu:
  - Gehe zu "Settings" → "Collaborators" → "Add people"
  - Gib den GitHub-Benutzernamen oder die E-Mail-Adresse ein

**Hinweis:** Ein Repository ist wie ein Ordner für euer Projekt, den ihr beide bearbeiten könnt!

### 2️⃣ Das Repository auf eure Computer holen (clonen)

**Beide Personen:**
- Öffne die Befehlszeile (Terminal/Kommandozeile)
- Navigiere zu einem Ordner, wo du das Projekt speichern möchtest
- Führe folgenden Befehl aus:
  ```
  git clone https://github.com/BENUTZERNAME/unsere-hobbys-website.git
  ```
- Öffne den geklonten Ordner in VSCode oder einem anderen Code-Editor

**Hinweis:** Durch das Klonen habt ihr beide eine lokale Kopie des Projekts auf eurem Computer!

### 3️⃣ Die Grundstruktur erstellen

**Person A:**
- Erstelle die Datei `index.html` (Startseite)
- Erstelle einen Ordner namens `css` und darin eine Datei `style.css`

**Person B:**
- Erstelle die Datei `hobbys.html` (zweite Seite)

**Hinweis:** Jede HTML-Datei sollte mindestens folgendes Grundgerüst haben:
```html
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Titel der Seite</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <!-- Hier kommt euer Inhalt rein -->
</body>
</html>
```

### 4️⃣ Arbeit aufteilen und an GitHub senden

**Person A:**
- Bearbeite die `index.html` und füge grundlegende Informationen über dich hinzu
- Füge eine Navigation ein, die zur zweiten Seite verlinkt
- Speichere deine Änderungen
- Sende deine Änderungen an GitHub:
  ```
  git add .
  git commit -m "Startseite erstellt"
  git push
  ```

**Person B:**
- Bevor du beginnst, hole dir die neuesten Änderungen:
  ```
  git pull
  ```
- Bearbeite dann `hobbys.html` und füge deine Hobbys hinzu
- Füge ebenfalls eine Navigation ein, die zurück zur Startseite führt
- Speichere deine Änderungen
- Sende deine Änderungen an GitHub:
  ```
  git add .
  git commit -m "Hobbyseite erstellt"
  git push
  ```

**Hinweis:** Durch `git pull` holt ihr euch immer die neuesten Änderungen der anderen Person!

### 5️⃣ Gemeinsam am CSS arbeiten

**Beide Personen:**
- Person A kann an den Farben und Schriften arbeiten
- Person B kann am Layout und der Responsivität arbeiten
- Denkt daran, vor jeder Arbeit immer zuerst `git pull` auszuführen!
- Und nach den Änderungen: `git add .`, `git commit -m "Beschreibung"`, `git push`

**Hinweis:** Wenn ihr beide gleichzeitig dieselbe Datei bearbeitet, kann es zu einem "Konflikt" kommen. Keine Sorge, das ist normal beim gemeinsamen Arbeiten!

### 6️⃣ Inhalte für die Website

Eure Website sollte enthalten:
- Ein Header-Bereich mit Titel
- Eine Navigation zwischen den beiden Seiten
- Informationen über eure Hobbys mit Bildern
- Mindestens eine Liste (ul/ol)
- Ein Footer mit euren Namen
- Ansprechendes Design mit CSS

## Tipps & Tricks

- **HTML-Elemente die ihr nutzen könnt:** `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`, `<h1>`-`<h6>`, `<p>`, `<img>`, `<ul>`, `<ol>`, `<li>`, `<a>`
- **CSS-Eigenschaften zum Experimentieren:** `color`, `background-color`, `font-family`, `margin`, `padding`, `display`, `flex`, `border`, `border-radius`
- **Git-Probleme?** Wenn etwas schiefgeht, keine Panik! Fragt nach Hilfe und merkt euch: Fast alles kann rückgängig gemacht werden.

## Häufige Fragen

**F: Was mache ich, wenn ich einen Konflikt habe?**
A: Git zeigt dir die Konflikte in der Datei. Ihr müsst gemeinsam entscheiden, welche Version ihr behalten wollt, und dann die Änderungen erneut committen.

**F: Wie füge ich Bilder hinzu?**
A: Erstellt einen Ordner namens `images` und speichert dort eure Bilder. Dann könnt ihr sie mit `<img src="images/meinbild.jpg" alt="Beschreibung">` einbinden.

**F: Was, wenn wir mehr als zwei Seiten machen wollen?**
A: Super Idee! Erstellt einfach weitere HTML-Dateien und verlinkt sie in eurer Navigation.

## Abgabe

Wenn ihr fertig seid:
1. Stellt sicher, dass alle eure Änderungen auf GitHub sind
2. Aktiviert GitHub Pages in den Repository-Einstellungen, damit eure Website online sichtbar ist
3. Testet die Website auf verschiedenen Geräten

## Bonus-Challenge

- Fügt eine Bildergalerie mit CSS-Grid hinzu
- Erstellt ein Kontaktformular (ohne Backend-Funktionalität)
- Macht eure Website für Mobilgeräte optimiert (responsive)

Good Luck Have Fun!
