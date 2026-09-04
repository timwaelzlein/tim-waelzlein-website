# Tim Wälzleins Fotografie-Website

## 🚀 Quick Start

### Lokal starten (auf deinem Computer)

1. **Hugo installieren** (falls noch nicht geschehen):
   - Windows: `choco install hugo-extended` (in PowerShell als Admin)
   - Mac: `brew install hugo`
   - Linux: `sudo apt install hugo`

2. **Website lokal starten**:
   ```
   hugo server
   ```
   
3. **Im Browser öffnen**: http://localhost:1313

Das war's! Du siehst deine Website live. Änderungen werden automatisch aktualisiert.

---

## 📁 Ordnerstruktur erklärt

```
tim-waelzlein/
├── content/              ← Deine Inhalte
│   ├── _index.md        (Startseite)
│   ├── about.md         (Über mich)
│   ├── contact.md       (Kontakt)
│   ├── gallery/
│   │   └── _index.md    (Galerie)
│   └── posts/
│       └── erste-fotografie.md  (Blog-Beispiel)
│
├── static/              ← Bilder & Downloads
│   └── images/         (Deine Fotos hier ablegen!)
│
├── hugo.toml           ← Konfiguration (ändern!)
└── README.md           (Diese Datei)
```

---

## ✏️ Was du jetzt tun solltest

### 1. **hugo.toml anpassen**
   - Öffne `hugo.toml`
   - Ersetze `https://example.com/` mit deiner echten Domain (später)
   - Der Rest sieht schon gut aus!

### 2. **contact.md bearbeiten**
   - Öffne `content/contact.md`
   - Ersetze `[deine-email@example.com]` mit deiner echten Email
   - Füge deine Social-Media-Links hinzu

### 3. **about.md personalisieren**
   - Öffne `content/about.md`
   - Füge mehr über dich ein
   - Erzähle von deiner Ausrüstung, deinen Erlebnissen, etc.

### 4. **Bilder hochladen**
   - Erstelle einen neuen Ordner: `static/images/voegel/`
   - Lege deine Fotos dort ab
   - In deinen Posts kannst du sie dann so einbinden:
     ```markdown
     ![Schöner Vogel](/images/voegel/mein-foto.jpg)
     ```

### 5. **Blog-Posts schreiben**
   - Kopiere `content/posts/erste-fotografie.md`
   - Erstelle neue `.md` Dateien für jeden Blog-Post
   - Format: `YYYY-MM-DD-titel.md`

---

## 📝 Markdown Quick-Guide

Blog-Posts und Seiten schreibst du in **Markdown** - super einfach:

```markdown
# Überschrift 1
## Überschrift 2

**fett** | *kursiv* | ***fett + kursiv***

- Punkt 1
- Punkt 2
  - Unterpunkt

1. Erste Sache
2. Zweite Sache

[Link](https://example.com)
![Bild](/images/mein-foto.jpg)

> Zitat

---

Code:
```

---

## 🌐 Online stellen (auf Netlify)

Später, wenn alles fertig ist:

1. **GitHub Account erstellen** (kostenlos auf github.com)
2. **Dein Projekt hochladen**
3. **Netlify.com**: Mit GitHub verbinden
4. **Fertig!** - Deine Website ist online!

(Ich helfe dir dann dabei!)

---

## 🎨 Nächste Schritte

- Theme anpassen (farblich, etc.)
- Blog-Posts schreiben
- Galerien aufbauen
- Später: Videos integrieren

---

## ❓ Hilfreiche Ressourcen

- Hugo Doku: https://gohugo.io/
- Markdown Guide: https://www.markdownguide.org/
- PaperMod Theme: https://github.com/adityatelange/hugo-PaperMod

---

**Viel Spaß mit deiner Website! 🦅📸**
