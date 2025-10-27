# 🍸 Cocktail Menu — GSAP Demo

Jednoduchá React aplikace, jejímž cílem bylo seznámit se s knihovnou **[GSAP (GreenSock Animation Platform)](https://greensock.com/gsap/)** a jejím pluginem **ScrollTrigger** pro tvorbu plynulých animací při scrollování.

---

## 🧠 O projektu

Tato aplikace zobrazuje interaktivní webovou stránku pro bar, kavárnu, atd..  
Součástí je několik **GSAP animací**, například:
- animace videa podle scrollování po stránce
- animace listů při scrollování sekce menu,
- plynulé přechody mezi jednotlivými koktejly,
- testování `ScrollTrigger` a práce s DOM pomocí `useRef`.

Cílem projektu nebylo vytvořit plně funkční produkt, ale **procvičit si práci s animacemi v Reactu** a pochopit, jak GSAP funguje v kombinaci s React hooky (`useEffect`, `useRef`, `useState`).

---

## ⚙️ Použité technologie

- ⚛️ **React** — UI knihovna
- 💫 **GSAP + ScrollTrigger** — animace a interakce na scroll
- 🧩 **Vite** — vývojové prostředí (rychlé bundlování)
- 🎨 **Tailwind CSS** — jednoduché stylování
- 🍹 Vlastní data o koktejlech (`allCocktails.js`)

---

## 🚀 Instalace a spuštění

1. Naklonuj repozitář:
   git clone https://github.com/Ondrej2556/react-gsap-demo.git
   cd react-gsap-demo

2. Nainstaluj závislosti:
    npm install


3. Spusť vývojový server:
    npm run dev
