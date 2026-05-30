# 🎵 Audio to MP3 Converter

> Eine einzige HTML-Datei – M4A zu MP3 Konverter, der komplett im Browser läuft.

![Status](https://img.shields.io/badge/status-stable-brightgreen)
![Dateigröße](https://img.shields.io/badge/size-~50KB-blue)
![Lizenz](https://img.shields.io/badge/license-MIT-green)

## ✨ Features

- 🎯 **Eine einzige HTML-Datei** – keine Installation, keine Abhängigkeiten
- 🔒 **100% lokal** – Dateien verlassen nie deinen Computer
- 📁 Drag & Drop oder Dateiauswahl
- 📊 Echtzeit-Fortschrittsanzeige
- ⬇️ MP3 Download mit 128 kbps Qualität
- 🚀 Funktioniert offline (nach dem ersten Laden)

## 🖱️ Live Demo

👉 **[Jetzt testen – M4A zu MP3 Konverter](https://huby-coder.github.io/audio-to-mp3-converter/)** 👈

## 📦 Projektstruktur

Nur eine Datei:


## ⚙️ Technische Details

| Was | Wie |
|-----|-----|
| M4A Decodierung | Web Audio API (browser-intern) |
| MP3 Encodierung | lamejs (JavaScript Bibliothek) |
| Dateigröße | ~50 KB (plus externe lamejs CDN) |

## 📋 Third-Party Software

Dieses Projekt verwendet folgende Open-Source-Komponenten:

| Komponente | Lizenz | Verwendung | Quelle |
|------------|--------|------------|--------|
| **lamejs** | LGPL-3.0 | MP3 Encoding | [github.com/zhuker/lamejs](https://github.com/zhuker/lamejs) |

Die Bibliothek wird über CDN eingebunden und bleibt eine separate Komponente.  
Der LAME MP3 Encoder ist unter der LGPL lizenziert. Weitere Informationen: [lame.sourceforge.io](https://lame.sourceforge.io/)

## ⚠️ Hinweise

- Benötigt eine **Internetverbindung** beim ersten Laden (für lamejs CDN)
- Danach kann die Seite im Cache bleiben
- Funktioniert mit AAC-Codec in M4A-Dateien
- Empfohlene maximale Dateigröße: ~200 MB (abhängig vom RAM)

## 🧪 Getestet mit

- ✅ Chrome / Edge
- ✅ Firefox
- ✅ Safari

## 📄 Lizenz

- **Eigener Code:** MIT Lizenz
- **lamejs:** LGPL-3.0 Lizenz

Siehe [LICENSE](LICENSE) Datei für vollständige Lizenztexte.

---

⭐ **Stern dalassen = Motivation** ⭐
