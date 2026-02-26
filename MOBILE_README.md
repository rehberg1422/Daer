# 📱 DAER MOBILE WEB-APP - INSTALLATION

## 📁 Dateien hochladen

Lade folgende Dateien auf GitHub hoch:

1. **mobile.html** - Die mobile Ansicht
2. **manifest.json** - PWA Manifest
3. **sw.js** - Service Worker für Offline

## 🌐 Zugriff

Nach dem Upload erreichbar unter:
- **https://rehberg1422.github.io/Daer/mobile.html**

## 📲 Als App installieren

### iPhone/iPad:
1. Öffne die Seite in Safari
2. Tippe auf "Teilen" Button (Quadrat mit Pfeil)
3. Scrolle runter und wähle "Zum Home-Bildschirm"
4. Tippe "Hinzufügen"
5. ✅ App ist jetzt auf deinem Home-Screen!

### Android:
1. Öffne die Seite in Chrome
2. Tippe auf ⋮ (Menü)
3. Wähle "Zum Startbildschirm hinzufügen"
4. Tippe "Hinzufügen"
5. ✅ App ist jetzt auf deinem Home-Screen!

## ✨ FEATURES

### Touch-Optimiert
- ✅ Große Touch-Targets (44x44px)
- ✅ Swipe-Gesten (Links/Rechts für Wochen)
- ✅ Pull-to-Refresh (Nach unten ziehen)
- ✅ Native App Feel

### Design
- ✅ Hell/Dunkel-Modus
- ✅ Responsiv für alle Handys
- ✅ Safe-Area Support (Notch/Home-Indicator)
- ✅ Moderne iOS/Android Optik

### Funktionen
- ✅ Offline-fähig (PWA)
- ✅ Installierbar auf Home-Screen
- ✅ Auto-Refresh
- ✅ Live-Updates von Firebase
- ✅ Statistik-Ansicht
- ✅ Heute-Markierung (rot)
- ✅ Krank-Meldungen als Toast

### Navigation
- ✅ Swipe Links/Rechts → Wochen wechseln
- ✅ Buttons ← → oben
- ✅ Pull-to-Refresh → Seite neu laden
- ✅ Smooth Scrolling

## 🎨 UNTERSCHIEDE TV vs MOBILE

| Feature | TV Version | Mobile Version |
|---------|-----------|----------------|
| Layout | Horizontal Grid | Vertical Scroll |
| Navigation | Pfeiltasten + Buttons | Swipe + Buttons |
| Heute | Pulsierender Rahmen | Rote Spalte |
| Stats | Fixed unten rechts | Scrollbare Karten |
| Theme | Auto Hell/Dunkel | Toggle Button |
| Einträge | Vertikal in Zelle | Vertikal gestapelt |

## 🔧 ANPASSUNGEN

### Farben ändern
In `mobile.html` Zeile 14-26:
```css
:root {
  --primary: #00acc1;  /* Hauptfarbe */
  --bg: #f5f7fa;       /* Hintergrund */
  --card: #ffffff;     /* Karten */
}
```

### Icons ändern
In `manifest.json` Zeile 10+:
Ersetze die SVG Emoji-Icons mit eigenen Bildern.

## 📊 PERFORMANCE

- ⚡ Schneller Start (< 1 Sek)
- 💾 Kleiner Cache (< 100KB)
- 🔄 Live-Updates via Firebase
- 📱 60 FPS Animationen
- 🌐 Funktioniert auch offline (nach erstem Laden)

---

**Viel Erfolg! 🚀**
