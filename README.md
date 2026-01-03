# 2it-web-fejtek-jiri
web
Kratos | God of War Portfolio
Tematická "osobní" webová stránka fiktivní postavy Krata ze série God of War. Tento projekt slouží jako moderní one-page portfolio prezentující jeho příběh, arzenál a dovednosti v minimalistickém, temném designu inspirovaném severskou ságou.

🛠 Použité technologie a knihovny
Projekt je postaven na čistých webových technologiích s využitím moderních CSS vlastností a animačních knihoven.

HTML5 (Sémantická struktura: <header>, <main>, <section>, <footer>)

CSS3

CSS Variables (proměnné pro barvy a fonty)

Flexbox (layout a zarovnání)

CSS Masking (mask-image pro blending obrázků)

Fluidní typografie pomocí funkce clamp()

Media Queries (plná responzivita pro mobily)

JavaScript (ES6+)

Externí knihovny:

GSAP (GreenSock Animation Platform) – Pro úvodní animace prvků.

GSAP ScrollTrigger – Pro spouštění animací při skrolování (sekce Skills).

Google Fonts – Fonty Cinzel (nadpisy) a Roboto (text).

🚀 Návod na spuštění
Webová stránka je statická a nevyžaduje žádný složitý build proces (npm/yarn). Ke spuštění stačí prohlížeč.

Stáhněte si repozitář (nebo soubory index.html a složku s obrázky).

Ujistěte se, že máte připojení k internetu (nutné pro načtení fontů a GSAP knihoven z CDN).

Spuštění:

Možnost A (Doporučeno pro vývoj): Otevřete složku ve VS Code a spusťte soubor přes rozšíření Live Server (tlačítko "Go Live").

Možnost B: Dvakrát klikněte na soubor index.html, čímž se otevře ve vašem výchozím prohlížeči.

🌟 Prvky, na které jsem nejvíce hrdý
Na tomto projektu se podařilo implementovat několik pokročilých vizuálních a technických detailů:

Efekt padajícího popela (JS):

Vlastní skript, který generuje a animuje částice "popela/sněhu" na pozadí, což dodává stránce tu správnou atmosféru God of War. Částice mají náhodnou velikost, rychlost i pozici.

Cinematic Blending Obrázků (CSS):

Použití mask-image a gradientů k dosažení efektu, kdy postava Krata plynule "vystupuje" z černého pozadí, aniž by byly vidět ostré hrany obrázku.

Responzivní Typografie:

Využití moderní CSS funkce font-size: clamp(), která zajišťuje, že nadpis "KRATOS" je vždy perfektně čitelný a velikostně odpovídající – od malého mobilu až po 4K monitor.

Interaktivní Animace:

Skill bar (ukazatele schopností) se "načtou" až ve chvíli, kdy k nim uživatel doscrolluje, díky integraci knihovny GSAP ScrollTrigger. 
