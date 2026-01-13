# Lux Start Page 🌅

Eine minimalistische, elegante und vollständig personalisierbare Browser-Startseite mit Live-Wetter, intelligenter Suche und modernem Design.

![License](https://img.shields.io/badge/license-MIT-blue.svg)

## ✨ Features

-   **👋 Interaktives Onboarding** - 2-Schritt Einführung für neue Nutzer
-   **🌍 Multi-Sprach Support** - Deutsch, English, Español (einfach erweiterbar)
-   **🌤️ Live Wetter-Widget** - Automatische Standorterkennung mit 7-Tage-Vorhersage
-   **🔍 Intelligente Suche** - Google-Suche mit Autocomplete und Suchhistorie
-   **📌 Anpassbare Shortcuts** - Drag & Drop zum Sortieren deiner Lieblings-Websites
-   **🌓 Dark/Light Mode** - Automatische Erkennung oder manuelle Auswahl
-   **⏰ Zeitformat** - Wählbar zwischen 12h und 24h Format
-   **👤 Personalisierung** - Individueller Name in zeitbasierter Begrüßung
-   **🔄 Reset-Funktion** - Zurücksetzen auf Standardeinstellungen
-   **💾 LocalStorage** - Alle Einstellungen bleiben lokal gespeichert
-   **🎨 Glassmorphism Design** - Modernes UI mit sanften Animationen

## 🚀 Installation

1. Repository klonen:

    ```bash
    git clone https://github.com/trpwrmusic/lux-start-page.git
    ```

2. `start.html` in deinem Browser öffnen

3. (Optional) Als Browser-Startseite festlegen:
    - **Chrome/Edge**: Einstellungen → Beim Start → Bestimmte Seite öffnen
    - **Firefox**: Einstellungen → Startseite → Benutzerdefinierte Adressen

## 🎯 Verwendung

### Erster Start

Beim ersten Öffnen wirst du durch ein 2-Schritt Onboarding geführt:

1. **Willkommen** - Übersicht über die wichtigsten Features
2. **Einstellungen** - Name und Zeitformat festlegen

Du kannst die Sprache jederzeit während des Onboardings über das Dropdown unten rechts ändern.

### Shortcuts verwalten

-   **Hinzufügen**: Klicke auf das `+` Symbol
-   **Löschen**: Hover über ein Shortcut und klicke das `×`
-   **Sortieren**: Einfach per Drag & Drop verschieben

### Einstellungen

Klicke auf das ⚙️ Icon oben rechts um:

-   Theme zu ändern (Hell/Dunkel)
-   Sprache zu wechseln
-   Deinen Namen einzugeben
-   Zeitformat anzupassen (12h/24h)
-   Alle Einstellungen zurückzusetzen

### Wetter

-   Klicke auf das Wetter-Widget für detaillierte Vorhersage
-   Automatische Standorterkennung via Geolocation API (erst nach Onboarding)
-   Stündliche und 7-Tage-Vorhersage

## 🛠️ Technologien

-   Vanilla JavaScript (ES6+)
-   Tailwind CSS (via CDN)
-   Google Fonts (Bricolage Grotesque, Libertinus Serif)
-   Font Awesome Icons
-   Material Symbols
-   Open-Meteo API (Wetter)
-   BigDataCloud API (Geolocation)
-   Google Autocomplete API

## 🌐 Neue Sprache hinzufügen

1. Füge im `translations` Objekt (ca. Zeile 866) eine neue Sprache hinzu:

    ```javascript
    fr: {
        greeting_morning: 'bon <em>matin</em>',
        onboarding_title: 'bienvenue à lux',
        // ... weitere Übersetzungen
    }
    ```

2. Füge die Option im HTML hinzu (ca. Zeile 647 und 770):
    ```html
    <option value="fr">🇫🇷 FR</option>
    ```

## 📱 Browser-Kompatibilität

-   ✅ Chrome/Edge (empfohlen)
-   ✅ Firefox
-   ✅ Safari
-   ✅ Opera

## 📄 Lizenz

Dieses Projekt ist unter der [MIT License](https://opensource.org/licenses/MIT) lizenziert - du darfst es frei verwenden, modifizieren und verteilen.

## 🙏 Credits

Entwickelt mit ♥ von [@trpwrmusic](https://github.com/trpwrmusic)

---

**Gefällt dir das Projekt?** Gib ihm einen ⭐ auf GitHub!
