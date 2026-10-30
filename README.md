# ČZU PEF – Reveal.js téma

Téma vychází z přiložené prezentace Řízení IT projektů – 1. cvičení. Nejde o oficiální distribuovaný design systém ČZU.

## Spuštění

V adresáři spusťte `python3 -m http.server 8000` a otevřete `http://localhost:8000`.

Reveal.js se načítá z CDN, takže je pro první spuštění potřeba internet. Pro offline provoz stáhněte Reveal.js lokálně a upravte odkazy v `index.html`.

## Použití

- `czu-theme.css` – vlastní téma a layouty.
- `index.html` – ukázkové snímky a jejich struktura.
- `assets/` – původní grafické podklady vytažené z dodané PPTX.
- Běžný snímek: `<section><h2 class="slide-title">Nadpis</h2>...</section>`.
- Dva sloupce: `<div class="columns"><div>...</div><div>...</div></div>`.
- Tři sloupce: `<div class="columns three">...</div>`.
- Úvodní snímek: `<section class="cover">...</section>`.
- Fotografický závěr: `<section class="photo-slide">...</section>`.

Obsah může být i v Markdownu pomocí Reveal.js Markdown pluginu; pro tento vzhled je nejspolehlivější HTML struktura uvedená v ukázce. CSS je samostatné a znovupoužitelné.
