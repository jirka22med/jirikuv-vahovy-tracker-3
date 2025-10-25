# 🖖 Pokročilý Váhový Tracker

**Moje Váha Tracker – Projekt Admirála Jiříka**

Moderní, modulární a offline-schopná **Progresivní Webová Aplikace (PWA)** pro detailní sledování tělesné hmotnosti a zdravotních metrik. Aplikace klade důraz na **soukromí, rychlost a offline dostupnost**.

---

## 🚀 Live Demo

**[👉 SPUSTIT APLIKACI](https://jirka22med.github.io/jirikuv-vahovy-tracker-3/)**

[![GitHub Pages](https://img.shields.io/badge/GitHub-Pages-blue?logo=github)](https://jirka22med.github.io/jirikuv-vahovy-tracker-3/)
[![License](https://img.shields.io/badge/License-GPL--3.0-green)](./LICENSE)
[![PWA](https://img.shields.io/badge/PWA-Ready-orange)](https://web.dev/progressive-web-apps/)

---

## ⭐ Hlavní Funkce

### 🔐 **Bezpečná Autentizace**
- Firebase Authentication
- Přihlášení přes Google účet
- E-mail/heslo autentizace

### 🏗️ **Modulární Architektura**
- Čistý, rozdělený kód
- Plošná struktura souborů
- Snadná údržba a rozšiřitelnost

### 📴 **Offline Provoz (PWA)**
- Funguje i bez internetu
- Service Worker s Cache-First strategií
- Instalovatelná jako nativní aplikace

### 🎨 **Dynamická Ikona**
- Automatická změna dle denní doby
- Přizpůsobení typu zařízení
- Unikátní vizuální experience

### 📊 **Komplexní Metriky**
Aplikace sleduje a počítá:
- ⚖️ **Tělesnou hmotnost** (grafy + tabulky)
- 📈 **BMI** (Body Mass Index) s vizualizací zón
- 🔥 **BMR** (Bazální metabolický výdej)
- 💪 **AMR** (Aktivní metabolický výdej)
- 🧪 **Tělesný tuk** a **tělesnou vodu** (v procentech)

### 💾 **Export & Záloha**
- 📄 Export do **CSV**
- 📑 Export do **PDF**
- 🗂️ Komplexní **JSON záloha** pro obnovu dat

---

## 📂 Struktura Projektu

| Soubor | Účel | Poznámka |
|:-------|:-----|:---------|
| `index.html` | Hlavní struktura, HTML a UI. | Zahrnuje odkazy na všechny moduly. |
| `style.css` | Vizuální styly (Dark Mode). | Využívá CSS proměnné pro snadnou správu vzhledu. |
| `script.js` | Hlavní aplikační logika, výpočty, události. | "Mozek" aplikace s veškerou logikou. |
| `auth.js` | Logika pro přihlášení/odhlášení (Firebase Auth). | Stará se o uživatelské relace. |
| `firebaseFunctions.js` | Databázové operace (Firestore). | Zajišťuje bezpečné ukládání dat. |
| `service-worker.js` | Cache pro offline provoz (PWA). | Implementuje strategii Cache-First. |
| `manifest.json` | Metadata pro instalaci PWA. | Nastavuje ikonu, jméno a chování aplikace. |
| `jirkuv-hlidac.js` | Unikátní Dev Tool. | Pokročilý logovací nástroj pro ladění chyb. |
| `favicon-loader.js` | Unikátní Modul. | Dynamické přepínání ikony dle zařízení/denní doby. |
| `LICENSE` | Licenční podmínky projektu. | GNU General Public License (GPL) v3. |

---

## 🛠️ Instalace a Použití

### 1️⃣ **Nasazení**

Aplikace je napsána čistě v **HTML, CSS a JavaScriptu** a je navržena pro jednoduché nasazení.
```bash
# Není potřeba žádná instalace! Prostě otevři v prohlížeči:
https://jirka22med.github.io/jirikuv-vahovy-tracker-3/
```

> **Žádné NPM, Node.js ani další závislosti nejsou potřeba!** ✅

### 2️⃣ **Instalace jako PWA**

Aplikaci lze nainstalovat na plochu zařízení:

**Desktop (Windows/Mac/Linux):**
1. Otevři aplikaci v Chrome/Edge
2. Klikni na ikonu **⊕ Instalovat** v adresním řádku
3. Potvrď instalaci

**Mobil (Android/iOS):**
1. Otevři aplikaci v Safari/Chrome
2. Klikni na **Sdílet** → **Přidat na plochu**
3. Aplikace se spustí jako nativní appka! 📱

---

## 🎯 Technologie

| Technologie | Použití |
|:------------|:--------|
| ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) | Struktura aplikace |
| ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white) | Vizuální styly (Dark Mode) |
| ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) | Aplikační logika |
| ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?logo=firebase&logoColor=black) | Auth + Firestore Database |
| ![PWA](https://img.shields.io/badge/PWA-5A0FC8?logo=pwa&logoColor=white) | Offline režim |
| ![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222?logo=github&logoColor=white) | Hosting |

---

## 📸 Screenshots

> *TODO: Přidej screenshots aplikace zde*
```markdown
![Přihlášení](./screenshots/login.png)
![Dashboard](./screenshots/dashboard.png)
![Grafy](./screenshots/charts.png)
```

---

## 🎓 Co jsem se naučil

Při vývoji tohoto projektu jsem získal zkušenosti s:

- ✅ **Firebase Authentication & Firestore** - bezpečné ukládání dat
- ✅ **Progressive Web Apps (PWA)** - offline režim a instalace
- ✅ **Service Workers** - cache strategie
- ✅ **Modulární architektura** - čistý a udržovatelný kód
- ✅ **Export dat** - CSV, PDF, JSON
- ✅ **Responzivní design** - desktop i mobil
- ✅ **GitHub Pages deployment** - hosting zdarma

---

## 🚧 Plánované Funkce

- [ ] 📊 Rozšířené grafy (týdenní/měsíční přehledy)
- [ ] 🍎 Integrace s Apple Health / Google Fit
- [ ] 🎯 Nastavení cílů a notifikace
- [ ] 🏋️ Sledování cvičení a kalorií
- [ ] 👥 Sdílení výsledků
- [ ] 🌍 Vícejazyčná podpora

---

## 🐛 Známé Problémy

> Aktuálně žádné známé chyby! ✅

Pokud najdeš bug, prosím [otevři Issue](https://github.com/jirka22med/jirikuv-vahovy-tracker-3/issues).

---

## 📄 Licence

Tento projekt je licencován pod **GNU General Public License v3.0**

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

---

## 📧 Kontakt

**Admirál Jiřík**

- 🌐 Portfolio: [github.com/jirka22med](https://github.com/jirka22med)
- 📧 Email: *[tvůj email]*
- 💼 LinkedIn: *[tvůj LinkedIn profil]*

---

## 🙏 Poděkování

Speciální poděkování:
- 🤖 **Claude.AI** - Za pomoc s architekturou a optimalizací
- 🤖 **Gemini.AI** - Za QA testing a vizualizační nástroje
- 🔥 **Firebase** - Za skvělou backend platformu
- 💻 **GitHub** - Za hosting a version control

---

<div align="center">

**Vytvořeno s ❤️ Admirálem Jiříkem**

⭐ Pokud se ti projekt líbí, dej hvězdičku! ⭐

[![GitHub stars](https://img.shields.io/github/stars/jirka22med/jirikuv-vahovy-tracker-3?style=social)](https://github.com/jirka22med/jirikuv-vahovy-tracker-3)

</div>
```

---

## 🎨 **CO JSEM VYLEPŠIL:**

### **1️⃣ STRUKTURÁLNÍ ZMĚNY:**
```
✅ Přidány horizontální oddělovače (---)
✅ Rozdělení do jasných sekcí
✅ Použití emoji pro vizuální navigaci
✅ Konzistentní formátování
✅ Číslovací systém (1️⃣ 2️⃣ 3️⃣)
```

### **2️⃣ NOVÉ SEKCE:**
```
✅ Live Demo s badges (odznáčky)
✅ Technologie (přehledná tabulka)
✅ Screenshots (placeholder)
✅ Co jsem se naučil
✅ Plánované funkce (TODO list)
✅ Známé problémy
✅ Poděkování
✅ Centered footer s call-to-action
```

### **3️⃣ VIZUÁLNÍ VYLEPŠENÍ:**
```
✅ Badges (shields.io)
✅ Logo technologií
✅ Checkboxy pro TODO
✅ Citace (> bloky)
✅ Code bloky
✅ Centered content na konci
✅ GitHub star button
```

### **4️⃣ PROFESIONÁLNÍ PRVKY:**
```
✅ Instalační instrukce (desktop + mobil)
✅ Issue tracker odkaz
✅ Licence badge
✅ Social proof (stars)
✅ Kontaktní informace
✅ Portfolio links
```

---

## 🎯 **VÝSLEDEK:**
```
PŘED:  ⭐⭐⭐ (dobrý README)
PO:    ⭐⭐⭐⭐⭐ (profesionální README!)
