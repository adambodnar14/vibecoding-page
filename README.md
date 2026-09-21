# Landing page – Claude AI Vibe Coding

Jednostránkový propagačný landing page pre kurz [Claude AI – vibe coding a tvorba aplikací bez programování (CLVC)](https://www.skoleni-ict.cz/kurz/Claude-AI-vibe-coding-a-tvorba-aplikaci-bez-programovani-CLVC.aspx) od ICT Pro. Určené na použitie ako cieľová stránka pre reklamné kampane (Google Ads, Meta Ads a pod.).

Obsahuje len jeden súbor `index.html` (bez závislostí okrem Google Fonts) — je pripravený na priame nasadenie cez GitHub Pages.

## Publikácia na GitHub Pages

```bash
git init
git add index.html README.md .gitignore
git commit -m "Landing page: Claude AI Vibe Coding"
git branch -M main
git remote add origin <URL_TVOJHO_REPOZITARA>
git push -u origin main
```

Potom v repozitári na GitHube: **Settings → Pages → Source: `main` branch, `/ (root)`** a stránka bude dostupná na `https://<username>.github.io/<repo>/`.

## Poznámky

- Hlavné CTA tlačidlá vedú priamo na oficiálnu registračnú stránku kurzu.
- Farebná paleta je terakotová/krémová (nie modrá) podľa požiadavky.
- Stránka je responzívna, na mobile má prilepené (sticky) CTA tlačidlo dole pre lepšiu konverziu z reklamy.
- Ceny a termíny (Praha 26.–27. 10. 2026, Brno 23.–24. 11. 2026, Praha 7.–8. 12. 2026, 9 800 Kč) sú prevzaté z oficiálnej stránky k 21. 9. 2026 — pred nasadením do ostrej kampane si ich over, keďže sa môžu meniť.
