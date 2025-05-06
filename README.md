# 🇷🇴 Calculator Popriri Salariu & Fracții (Salary Garnishment & Fractions Calculator)

Acesta este un calculator web conceput pentru a ajuta utilizatorii din România să estimeze popririle aplicabile pe salariu și să calculeze rapid diverse fracții dintr-o sumă. Aplicația este scrisă în HTML, CSS și JavaScript vanilla.

---

## Cuprins

-   [Descriere](#descriere)
-   [Funcționalități](#funcționalități)
-   [Cum se Utilizează](#cum-se-utilizează)
-   [Tehnologii Folosite](#tehnologii-folosite)
-   [Structura Proiectului](#structura-proiectului)
-   [Capturi de Ecran (Placeholder)](#capturi-de-ecran-placeholder)
-   [Disclaimer Important](#disclaimer-important)
-   [Posibile Îmbunătățiri](#posibile-îmbunătățiri)

---

## Descriere

Calculatorul oferă două funcționalități principale:

1.  **Calcul Simplu de Fracții:** Permite calcularea rapidă a 1/2, 1/3 sau 2/3 dintr-o sumă introdusă (de obicei salariul).
2.  **Calcul Avansat al Popririlor:** Estimează suma care poate fi reținută din salariu în cazul existenței uneia sau mai multor popriri active (ANAF, Primărie/Impozite Locale, BEJ - Birou Executor Judecătoresc). Calculatorul ia în considerare opțiunea aplicării plafonului salariului minim pe economie și numărul de dosare BEJ.

Interfața este concepută să fie intuitivă, cu câmpuri care devin active sau vizibile în funcție de selecțiile utilizatorului.

---

## Funcționalități

* **Interfață Curată și Modernă:** Design responsiv și ușor de utilizat.
* **Calcul Rapid Fracții:**
    * Butoane dedicate pentru 1/2, 1/3, 2/3 din salariu.
* **Calcul Detaliat Popriri:**
    * Introducerea sumei salariului.
    * Opțiune pentru aplicarea plafonului salariului minim net pe economie (cu valoare configurabilă).
    * Selecție individuală pentru tipurile de popriri:
        * ANAF (cu opțiune de poprire integrală).
        * Primărie/Impozite Locale (cu opțiune de poprire integrală).
        * BEJ (cu specificarea numărului de dosare active).
    * Afișarea sumei maxime ce poate fi reținută.
    * Afișarea sumei rămase clientului.
    * Detalii despre distribuția estimată a sumei reținute între creditori (logică simplificată).
* **Validare Input:** Verificări de bază pentru sumele introduse.
* **Afișare Rezultate:** Mesaje clare pentru succes sau eroare.
* **Funcție de Reset:** Golește toate câmpurile și resetează selecțiile la valorile implicite.
* **Câmpuri Condiționale:** Anumite câmpuri apar/dispar sau devin active/inactive în funcție de opțiunile selectate.

---

## Cum se Utilizează

1.  **Descărcați** fișierele proiectului sau clonați repository-ul.
2.  **Deschideți fișierul `index.html`** (sau numele principal al fișierului HTML) într-un browser web modern (Chrome, Firefox, Edge, Safari).
3.  **Pentru Calcul Simplu Fracții:**
    * Introduceți suma dorită în câmpul "Suma (RON)".
    * Apăsați pe unul dintre butoanele: "Calculează 1/2", "Calculează 1/3", sau "Calculează 2/3".
    * Rezultatul va fi afișat dedesubt.
4.  **Pentru Calcul Popriri Active:**
    * Introduceți suma salariului în câmpul "Suma (RON)".
    * Bifați "Se aplică plafonul salariului minim?" dacă este cazul și verificați/modificați valoarea salariului minim net.
    * Selectați tipurile de popriri active (ANAF, Primărie, BEJ) bifând căsuțele corespunzătoare.
    * Dacă ați selectat o poprire, opțiuni suplimentare pot deveni disponibile (ex: "Integrală?" pentru ANAF/Primărie, "Număr dosare active" pentru BEJ). Completați aceste detalii.
    * Apăsați butonul "Calculează".
    * Rezultatul detaliat va fi afișat.
5.  **Pentru a reseta:** Apăsați butonul "Reset".

---

## Tehnologii Folosite

* **HTML5:** Pentru structura paginii web.
* **CSS3:** Pentru stilizarea interfeței, inclusiv variabile CSS pentru temă și design responsiv.
    * Font: Google Fonts (Poppins).
* **JavaScript (Vanilla):** Pentru toată logica de calcul, manipularea DOM-ului și interactivitate. Nu sunt folosite framework-uri sau biblioteci externe de JS.

---
