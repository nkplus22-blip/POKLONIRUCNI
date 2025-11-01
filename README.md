# DekorationsGeschenke

Jednostavna web stranica za prikaz ručno izrađenih voskanih dekoracija (poklona) sa opcijom kupovine preko WhatsApp-a. Stranica je dvojezična: njemački (DE) i hrvatski (HR).

---

## Struktura projekta

/ (glavni direktorij) │ ├─ index.html ├─ README.md ├─ image1.jpeg ├─ image2.jpeg ├─ image3.jpeg ├─ image4.jpeg ├─ image5.jpeg ├─ image6.jpeg ├─ image7.jpeg ├─ image8.jpeg ├─ image9.jpeg

> Sve slike proizvoda se nalaze direktno u glavnom direktoriju, ne u folderu `images/`.

---

## Kako koristiti stranicu

1. Klonirajte ili preuzmite projekat na svoj uređaj.
2. Provjerite da su sve slike (`image1.jpeg` … `image9.jpeg`) u istom direktoriju kao `index.html`.
3. Otvorite `index.html` u pregledniku.
4. Klikom na dugme **Kupi proizvod / Produkt kaufen** otvorit će se WhatsApp chat sa unaprijed pripremljenom porukom za narudžbu.
5. Možete prebacivati jezik klikom na 🇩🇪 DE ili 🇭🇷 HR u gornjem desnom kutu.

---

## Opcije plaćanja

Ispod kontakta se nalaze opcije plaćanja:

- 💳 IBAN  
- 💵 WesternUnion  
- 💰 RiaMoney  
- 🅿️ PayPal  
- 💸 Skrill  
- 💳 Payonner  

---

## Tehničke informacije

- HTML, CSS i JavaScript (bez dodatnih frameworka)  
- Responsive dizajn za mobitele i desktop  
- Animacija simbola 🎁 🌸 🎀 🥳 u pozadini  

---

## Prilagodba

- Dodavanje novih proizvoda: u `index.html` u `products` array dodajte novi objekat sa svojom slikom i podacima.  
- Promjena WhatsApp broja: izmijenite vrijednost `WHATSAPP_NUMBER` u `<script>` sekciji.  
- Promjena jezika i teksta: izmijenite `copy` objekat u `<script>` sekciji.

---

## Upute za commit i push na GitHub (mobitel)

1. Otvorite GitHub app i idite u vaš repository.
2. Kliknite **Add file → Upload files** i odaberite sve slike (`image1.jpeg` … `image9.jpeg`) i `index.html`.
3. U **Commit changes** polje unesite:

Add index.html and product images Added index.html with product grid and animations. Added all product images (image1.jpeg to image9.jpeg) in main directory.

4. Odaberite **Commit directly to main branch**.
5. Kliknite **Commit changes**.
6. Stranica i slike su sada spremni na GitHub-u i mogu se prikazati preko GitHub Pages.

---

> Projekt je spreman za direktno postavljanje na GitHub Pages
