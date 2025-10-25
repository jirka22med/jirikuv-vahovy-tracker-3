🖖 Pokročilý Váhový Tracker

Moje Váha Tracker – Projekt Admirála Jiříka

Tento projekt je moderní, modulární a offline-schopná Progresivní Webová Aplikace (PWA) určená pro detailní sledování tělesné hmotnosti a dalších zdravotních metrik. Aplikace klade důraz na soukromí, rychlost a offline dostupnost.

🚀 Odkaz na Funkční Aplikaci

Aplikace je nasazena a plně funkční na GitHub Pages:
SPUSTIT APLIKACI

⭐️ Hlavní Funkce Aplikace

Autentizace (Firebase): Bezpečné přihlášení pomocí Google účtu a/nebo e-mailu/hesla.

Modulární Architektura: Kód je rozdělen do modulů (plošná struktura pro maximální stabilitu), které se starají pouze o svou specifickou funkci (auth.js, firebaseFunctions.js, script.js).

Offline Provoz (PWA): Díky Service Workeru a Manifestu funguje aplikace i bez připojení k internetu a lze ji nainstalovat jako nativní aplikace na počítač nebo mobil.

Dynamická Ikona (Favicon): Unikátní modul dynamicky mění ikonu aplikace (favicon) na základě denní doby (noční/denní režim) a typu zařízení.

Komplexní Metriky: Sleduje a počítá:

Tělesnou hmotnost (včetně grafů a tabulek).

BMI (Body Mass Index) s vizualizací zón.

Bazální metabolický výdej (BMR) a aktivní metabolický výdej (AMR).

Tělesný tuk a tělesnou vodu v procentech.

Export a Záloha: Umožňuje export všech dat do formátů CSV a PDF a také vytvoření komplexní JSON zálohy pro obnovu.

⚙️ Technická Architektura

Projekt je postaven na principech ploché struktury (Flat File Structure), která byla zvolena pro minimalizaci chyb v cestách a zajištění bezproblémového nasazení na GitHub Pages.


## 📂 Struktura Projektu

| Soubor | Účel | Poznámka |
|:-------|:-----|:---------|
| **index.html** | Hlavní struktura, HTML a UI. | Zahrnuje odkazy na všechny moduly. |
| **style.css** | Vizuální styly (Dark Mode). | Využívá CSS proměnné pro snadnou správu vzhledu. |
| **script.js** | Hlavní aplikační logika, výpočty, události. | "Mozek" aplikace s veškerou logikou. |
| **auth.js** | Logika pro přihlášení/odhlášení (Firebase Auth). | Stará se o uživatelské relace. |
| **firebaseFunctions.js** | Databázové operace (Firestore). | Zajišťuje bezpečné ukládání dat. |
| **service-worker.js** | Cache pro offline provoz (PWA). | Implementuje strategii Cache-First. |
| **manifest.json** | Metadata pro instalaci PWA. | Nastavuje ikonu, jméno a chování aplikace. |
| **jirkuv-hlidac.js** | Unikátní Dev Tool. | Pokročilý logovací nástroj pro ladění chyb. |
| **favicon-loader.js** | Unikátní Modul. | Dynamické přepínání ikony dle zařízení/denní doby. |
| **LICENSE** | Licenční podmínky projektu. | GNU General Public License (GPL) v3. |


🛠 Instalace a Použití

1. Nasazení

Aplikace je napsána čistě v HTML, CSS a JavaScriptu a je navržena pro jednoduché nasazení. Ke spuštění nejsou potřeba žádné další kroky (NPM, Node.js, apod.).

2. Instalace PWA

Tuto aplikaci lze nainstalovat na plochu vašeho zařízení (Windows/Android/iOS):

Otevřete aplikaci v prohlížeči.

Vyhledejte ikonu "Instalovat aplikaci" (obvykle ve formě plus/šipky v adresním řádku prohlížeče).

Potvrďte instalaci. Aplikace se spustí v samostatném okně bez lišty prohlížeče, což poskytuje nativní zážitek.

📧 Kontakt

Pro dotazy, hlášení chyb nebo návrhy na vylepšení, kontaktujte autora projektu:

Admirál Jiřík

Doporučujeme přidat sem tvůj e-mail nebo odkaz na LinkedIn/jiný profil.
 
