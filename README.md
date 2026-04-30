# Pilates 97 Studio

Ekskluzivni pilates studio vebsajt – moderan, elegantan i minimalistički dizajn posvećen vrhunskom iskustvu.

## Opis Projekta

Ovo je profesionalna veb stranica (*landing page*) namenski napravljena za **Pilates 97** studio u Obrenovcu. Dizajn se fokusira na čistu, premijum estetiku, jednostavnu navigaciju i jasne pozive za akciju (povezivanje na Instagram, lokaciju i poziv). Stranica je tehnološki maksimalno optimizovana za brzinu, sa lazy-loading funkcijom fotografija i *responsive* interfejsom za telefone.

## Tehnologije

Projekat je u potpunosti izgrađen koristeći "čiste" (Vanilla) jezike, bez glomaznih biblioteka poput React-a ili okvira poput Bootstrap-a. Ovo garantuje maksimalne performanse na svakom uređaju:
- **HTML5:** Organizacija sadržaja i "skelet" sajta.
- **CSS3:** Detaljno stilizovanje, ukrasni fontovi (Google Fonts), kropovanje i upravljanje fokusom fotografija, moderni mobilni *hamburger* meni, kaskadna prilagođavanja za uređaje svih veličina.
- **JavaScript (Vanilla JS):** Upotreba `Intersection Observer API`-a za prefinjene "Scroll Reveal" efekte kod pomeranja ekrana na dole, osvežavanje pozicije (scroll-to-top), i slušač za funkcionisanje mobilnog padajućeg menija.

## Struktura fajlova

- `index.html` — Glavna mark-up datoteka sajta (uključuje integrisanu Google Mapičicu).
- `index.css` — Centralizovani stilovi i *Media Queries* responzivnost.
- `app.js` — Sva interaktivna i logička funkcionalnost.
- `slike/` — Optimizovane galerijske i portretne fotografije neophodne za rad sajta.

## Razvoj (Kako Pokrenuti Lokalno)

S obzirom na to da je ovo statički sajt, možete ga videti u sekundi.
1. Preuzmite fajlove u jedan folder.
2. Dvostrukim klikom otvorite `index.html` fajl (podrazumevano će se otvoriti u Google Chrome / Safari / Edge-u).
3. Ili za još bolji rad ako i dalje razvijate kod, koristite VS Code ekstenziju *Live Server*.

## Spreman za Deploy (Objavljivanje)

Ovaj repozitorijum je tehnički spreman i *očišćen* za deploy odmah. Možete iskoristiti brze i komercijalno besplatne platforme za hostovanje statičkih sajtova:
- **Netlify ili Vercel:** Najprostija i najbrža metoda. Samo označite i prevucite (*Drag & Drop*) ovaj folder mišem u njhov prozor i sajt je online za 15 sekundi na sopstvenom domenu.
- **GitHub Pages:** Idealan za one koji žele da drže svoj kod javnim ili potpuno besplatno kroz proces komitovanja grana repozitorijuma.
- **Klasičan standardni host (Hostinger/GoDaddy/MCL):** Dovoljno je samo iskopirati fajlove na File Manager putanju u `/public_html/`. 
