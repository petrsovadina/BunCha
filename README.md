# BunCha 🍜

**Moderní, responzivní web s online objednávkovým systémem pro asijskou restauraci.**

Cílem projektu je posílit branding, zjednodušit proces objednávání pro zákazníky a zvýšit online prodej prostřednictvím intuitivního rozhraní s možností platby kartou a osobního vyzvednutí.

---

## 🚀 Klíčové funkce

- **Online objednávkový systém:** Jednoduchý výběr jídel a konfigurace objednávky.
- **Click & Collect:** Možnost zvolit čas vyzvednutí jídla s sebou.
- **Platby:** Bezpečná integrace platební brány **Stripe**.
- **Responzivní design:** Optimalizováno pro mobily, tablety i desktop.
- **Moderní UI:** Čistý a rychlý design postavený na nejnovějších technologiích.

---

## 🛠 Technologie a Zdroje

Pro vývoj, design a provoz projektu využíváme moderní stack (T3/Next.js stack) a metodiku Spec-Driven Development.

| Kategorie | Nástroj / Odkaz | Popis |
| :--- | :--- | :--- |
| **Dokumentace** | [**Notion Workspace**](https://www.notion.so/B-n-C-dbdd47c31c3d4f21b5880c266ea61607?source=copy_link) | **Single Source of Truth.** Kompletní specifikace, design manuál, user stories a roadmapa projektu. |
| **Framework** | [**Next.js**](https://nextjs.org/) | React framework pro produkci. Zajišťuje SSR/SSG, routing a API routes. |
| **UI Komponenty** | [**shadcn/ui**](https://ui.shadcn.com/) | Kolekce znovupoužitelných komponent postavených na Radix UI a Tailwind CSS. |
| **Backend & DB** | [**Supabase**](https://supabase.com/) | Open-source alternativa k Firebase. PostgreSQL databáze, Auth a Realtime subscriptions. |
| **Vývoj (SDD)** | [**GitHub: Spec-Kit**](https://github.com/github/spec-kit) | Toolkit pro **Spec-Driven Development**. Používáme pro generování kódu a správu zadání pomocí AI agentů. |
| **Hosting** | [**Vercel**](https://vercel.com/home) | Platforma pro nasazení frontendu a serverless funkcí. |

---

## ⚙️ Instalace a Lokální spuštění

Pro spuštění projektu na lokálním stroji potřebuješ Node.js (doporučeno v20+) a správce balíčků (npm, pnpm nebo yarn).

### 1. Klonování repozitáře

```bash
git clone [https://github.com/tvoje-uzivatelske-jmeno/buncha.git](https://github.com/tvoje-uzivatelske-jmeno/buncha.git)
cd buncha

---

🧩 Vývojový proces (Spec-Driven Development)
Tento projekt využívá metodiku Spec-Driven Development. Před implementací složitějších funkcí definujeme specifikace pomocí toolkitu spec-kit.
