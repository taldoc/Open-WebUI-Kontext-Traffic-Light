# Open WebUI - Context Light / Kontext-Ampel 🚦

**[EN]** A precise context window monitor (context traffic light) that reads the hardware limit directly from the Open WebUI SQLite database and displays the exact token usage from the Ollama metadata. The usage is visualized using traffic light colors, and the exact token values are also output. 

**[DE]** Ein präziser Kontextfenster-Monitor (Kontext-Ampel), der das Hardware-Limit direkt aus der Open WebUI SQLite-Datenbank ausliest und die exakte Token-Nutzung anhand der Ollama-Metadaten anzeigt. Die Auslastung wird mit Ampelfarben visualisiert und die genauen Token-Werte werden zusätzlich ausgegeben.

<img width="430" height="100" alt="Kontext-Ampel" src="https://github.com/user-attachments/assets/4e440cd6-7cf0-4601-ac38-bfa09c85c122" />

---

## 📥 Installation (GUI)

**[EN]**
1. Download the `.json` file from this repository.
2. Open your Open WebUI.
3. Navigate to **Workspace** -> **Functions** in the left menu.
4. Click the **Import** button (top right) and upload the `.json` file.
5. Ensure the toggle switch next to the new function is turned **ON**.

**[DE]**
1. Lade die `.json` Datei aus diesem Repository herunter.
2. Öffne dein Open WebUI.
3. Navigiere im linken Menü zu **Arbeitsbereich** (Workspace) -> **Funktionen** (Functions).
4. Klicke oben rechts auf **Importieren** (Import) und lade die `.json` Datei hoch.
5. Stelle sicher, dass der Schalter neben der neuen Funktion auf **Aktiviert** (ON) steht.

---

## ⚙️ Configuration & Usage / Nutzung

**[EN]**
⚠️ **Attention:** The `num_ctx` value (context window limit) must be changed or set in your model parameters so the traffic light can calculate the limits correctly! Once configured, the traffic light will automatically monitor your chat context. If the value is missing in the database, a notification will prompt you to set it.

💡 **Pro Tip:** After importing, click the `...` menu next to the function and set it to **Global**. This will instantly apply the traffic light to all your models without any further manual assignment!

**[DE]**
⚠️ **Achtung:** Der Wert `num_ctx` (Kontextfenster-Limit) muss in den Modell-Parametern zwingend angepasst bzw. gesetzt werden, damit die Ampel die Grenzen korrekt berechnen kann! Sobald dies erledigt ist, überwacht die Ampel automatisch deinen Chat-Kontext. Fehlt der Wert in der Datenbank, erscheint im Chat ein entsprechender Hinweis.

💡 **Pro-Tipp:** Klicke nach dem Import auf das `...` Menü rechts neben der Funktion und setze sie als **Global** (Global aktivieren). Dadurch wird die Ampel sofort und automatisch bei allen Modellen angewendet, ohne dass du sie einzeln im Chat zuweisen musst!
