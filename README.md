# Sebi Sallon - Website Zyrtar ✂️💈

Ky repozitor përmban kodin burimor për faqen e re zyrtare të **Sebi Sallon**, një berber profesional në Tiranë, Shqipëri, me përvojë që nga viti 2012. 

Faqja është ndërtuar për të qenë jashtëzakonisht e shpejtë, moderne dhe e optimizuar 100% për pajisjet celulare (Mobile-First), duke i ofruar klientëve një eksperiencë të lehtë për t'u informuar dhe për të rezervuar.

🔗 **Shiko faqen Live:** [sebisallon.github.io/index](https://sebisallon.github.io/index/)

---

## 🚀 Veçoritë Kryesore

* **Dizajn "Dark & Gold":** Një estetikë premium, maskuline dhe moderne që përfaqëson më së miri identitetin e një berberi profesional.
* **Arkitekturë Single-Page (SPA):** Ndërtuar me React për navigim të menjëhershëm pa rifreskuar faqen.
* **Galeri Interaktive (Lightbox):** Seksion portofoli me funksionalitet "Swipe" në celularë dhe navigim me shigjeta në desktop.
* **Menu Shërbimesh me Kategori:** Kategorizim i zgjuar (Të gjitha, Koka, Mjekrra, Fytyra) për t'i gjetur shërbimet dhe çmimet me lehtësi.
* **Rezervim i Fërkimit të Ulët:** Butona statikë "Rezervo Tani" që lidhen direkt me WhatsApp dhe thirrje telefonike.
* **SEO e Optimizuar:** Përmbajtje e strukturuar saktë, ikona të optimizuara dhe strategji për emërtimin e imazheve.
* **Social Proof:** Seksion i dedikuar për vlerësimet nga Google Reviews.

---

## 🛠️ Teknologjitë e Përdorura

Për të ruajtur lehtësinë e hostimit direkt në GitHub Pages pa patur nevojë për procese të komplikuara "Build", projekti përdor një qasje hibride:

* **HTML5:** Baza e strukturës së faqes në një skedar të vetëm (`index.html`).
* **React 17 & Babel (via CDN):** Për të menaxhuar gjendjen (state), navigimin dhe ndërfaqen interaktive direkt në shfletues.
* **Tailwind CSS (via CDN):** Për stilim ultra të shpejtë dhe të përgjegjshëm (responsive).
* **SVG Icons:** Ikona të vizatuara manualisht (frymëzuar nga Lucide) për të eliminuar varësitë e jashtme dhe për t'u ngarkuar në mënyrë të menjëhershme.

---

## 📂 Struktura e Projektit

```text
sebisallon.github.io/index/
│
├── index.html               # Skedari kryesor (përmban kodin HTML, Tailwind dhe React/JSX)
├── README.md                # Dokumentacioni i projektit
│
└── assets/                  # Dosja për elementet vizuale
    └── img/
        ├── about.jpg        # Fotoja e seksionit "Kush Jemi"
        └── gallery/         # Dosja ku ruhen fotot e galerisë (të emërtuara për SEO)
            ├── qethje-moderne-tirane.jpg
            ├── stilim-mjekrre-brisk.jpg
            └── ...
