# Zadání pro vývoj webové stránky restaurace Bún Cá

---

## 1. Přehled projektu

- **Název:** Webová stránka restaurace Bún Cá
- **Klient:** Restaurace Bún Cá, Brno (rodinný vietnamský podnik)
- **Doména:** [www.bunca.cz](http://www.bunca.cz)
- **Cíl:** Vytvořit moderní, responzivní web s online objednávkovým systémem, platbou kartou (Stripe) a možností vyzvednutí jídla. Web má posílit branding, zjednodušit objednávání a zvýšit online prodej.

---

## 2. Tech stack

| Vrstva | Technologie |
| --- | --- |
| Frontend | Next.js (React), Shadcn/UI |
| CMS | Outstatic (headless, no-code editace pro klienta) |
| Platební brána | Stripe |
| Hosting | Kompatibilní s Next.js (např. Vercel) |
| SSL | Povinný (HTTPS) |

---

## 3. Vizuální identita

- **Logo:** Stávající logo „Bún Cá"
- **Barvy:** Primární – černá, Sekundární – zlatá/zlatavá, Doplňkové – bílá/krémová, tlumená zelená (olivová, šalvějová)
- **Typografie:** Serifové písmo pro logo a nadpisy, bezserifové pro texty (Open Sans / Roboto / Lato)
- **Styl:** Moderní, minimalistický, elegantní, s jemnými vietnamskými motivy (bambus, lotos, vlny)

---

## 4. Struktura webu (stránky)

### 4.1 Homepage

- Hero sekce: nadpis, krátký popis, slideshow fotografií jídel
- CTA: „Objednat online", „Prohlédnout menu"
- Náhled specialit z menu (4 jídla)
- Sekce recenzí zákazníků (volitelně synchronizace ze sociálních sítí)

### 4.2 Menu

- Kategorie: Předkrmy, Polévky, Hlavní jídla, Vegetariánské, Dezerty, Nápoje
- Každé jídlo: foto, název, popis, cena, alergeny, tlačítko „Objednat"
- Filtrování a vyhledávání

### 4.3 Objednávka / Košík

- Přehled vybraných jídel (název, množství, cena)
- Úprava množství, odebrání položek
- Souhrn: cena bez DPH, DPH, celkem
- Formulář: jméno, telefon, email (volitelné), poznámka
- Výběr času vyzvednutí (rozsah 10:00–19:30)
- Platba: online kartou (Stripe) nebo hotově při vyzvednutí
- Potvrzení objednávky

### 4.4 O nás

- Příběh restaurace a rodiny
- Fotogalerie interiéru a týmu
- Filozofie a hodnoty

### 4.5 Kontakt

- Kontaktní formulář (jméno, email, telefon, zpráva)
- Google Maps s polohou restaurace
- Adresa, telefon, email, otevírací hodiny

### 4.6 Patička (globální)

- Logo, odkazy na sociální sítě (Facebook, TripAdvisor, Restaurant Guru)
- Právní informace, GDPR

---

## 5. Klíčová funkcionalita

### Musí být (MVP)

- [ ]  Online objednávání jídla na vyzvednutí
- [ ]  Platba kartou přes Stripe
- [ ]  Zobrazení menu s kategoriemi, cenami a alergeny
- [ ]  Filtrování a vyhledávání v menu
- [ ]  Responzivní design (mobil, tablet, desktop)
- [ ]  No-code editace obsahu pro klienta (Outstatic CMS)
- [ ]  Kontaktní formulář
- [ ]  Základní SEO (meta tagy, struktura, rychlost)
- [ ]  SSL certifikát
- [ ]  Tisk objednávek pro restauraci (s kontaktem objednávajícího)
- [ ]  Fakturace e-commerce (IČ: 05557852)

### Nice to have (fáze 2)

- [ ]  Registrace uživatelů a historie objednávek
- [ ]  Synchronizace recenzí ze sociálních sítí
- [ ]  Blog sekce
- [ ]  Hover efekty a pokročilé animace
- [ ]  Odkaz na rozvoz přes externí službu
- [ ]  WCAG přístupnost

---

## 6. Nefunkční požadavky

- **Výkon:** Rychlé načítání (Lighthouse score 90+)
- **Bezpečnost:** HTTPS, Stripe PCI DSS compliance
- **Responzivita:** Plně funkční na všech zařízeních a prohlížečích
- **UX:** Intuitivní ovládání, max. 3 kroky k dokončení objednávky
- **Editovatelnost:** Klient musí zvládnout úpravu textů a obrázků bez vývojáře
