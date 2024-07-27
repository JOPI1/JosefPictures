# Josef Pictures

Willkommen bei Josef Pictures! Diese Seite dient als Portfolio für Bilder und zeigt eine Galerie von Bildern.

## Projektübersicht

Dieses Repository enthält eine einfache HTML-Seite, die eine Galerie von Bildern anzeigt.

## Verwendete Technologien

- HTML
- CSS

## Einrichtung

Folgen Sie diesen Schritten, um das Projekt lokal einzurichten:

1. **Repository klonen:**

    ```bash
    git clone https://github.com/JOPI1/josef-pictures.git
    cd josef-pictures
    ```

2. **Öffnen Sie die `index.html` Datei in Ihrem bevorzugten Webbrowser:**

    ```bash
    open index.html
    ```

## Bilder hinzufügen

Um neue Bilder zur Galerie hinzuzufügen, folgen Sie diesen Schritten:

1. **Laden Sie das Bild in das Repository hoch:**
   - Gehen Sie auf GitHub zu Ihrem Repository.
   - Klicken Sie auf `Add file` und wählen Sie `Upload files`.
   - Wählen Sie die Bilddatei von Ihrem Computer und laden Sie sie hoch.
   - Committen Sie die Änderungen.

2. **Fügen Sie das Bild zur Galerie in der `index.html` Datei hinzu:**
   - Öffnen Sie die `index.html` Datei im Bearbeitungsmodus.
   - Fügen Sie einen neuen `<img>` Tag in der Galerie-Div hinzu, z.B.:

     ```html
     <div class="gallery">
         <img src="https://github.com/JOPI1/josef-pictures/raw/main/IHR-BILD.png" alt="Bildbeschreibung">
     </div>
     ```

   - Ersetzen Sie `IHR-BILD.png` durch den Namen der hochgeladenen Bilddatei und `Bildbeschreibung` durch eine passende Beschreibung.

3. **Committen Sie die Änderungen:**

    ```bash
    git add index.html
    git commit -m "Add new image to gallery"
    git push origin main
    ```

## Lizenz

Dieses Projekt ist lizenziert unter der MIT-Lizenz. Siehe die [LICENSE](LICENSE) Datei für Details.

## Kontakt

Falls Sie Fragen oder Anregungen haben, können Sie mich unter [Ihre E-Mail-Adresse] kontaktieren.

---

Vielen Dank, dass Sie Josef Pictures besuchen!
