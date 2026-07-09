# BruClean Service — strona internetowa

Statyczna strona wizytówkowa firmy BruClean Service (Kraków) — mycie elewacji, dachów, kostki brukowej, prace wysokościowe.

Live: [brucleanservice.pl](https://brucleanservice.pl)

## Struktura

```
index.html          — strona główna
uslugi/              — 7 podstron usług (mycie dachów, mycie elewacji, mycie kostki brukowej,
                        malowanie/impregnacja, prace wysokościowe, czyszczenie rynien, czyszczenie przemysłowe)
images/              — zdjęcia realizacji, opinii i usług
robots.txt           — dyrektywy dla robotów wyszukiwarek
sitemap.xml          — mapa strony dla SEO
CNAME                — własna domena (brucleanservice.pl) dla GitHub Pages
```

## Tech

Czysty HTML + [Tailwind CSS](https://tailwindcss.com) (CDN), bez build stepu — strona działa od razu z plików statycznych.

## Hosting

Strona jest hostowana przez GitHub Pages z tego repozytorium (branch `main`, katalog główny), z podpiętą domeną własną `brucleanservice.pl` przez plik `CNAME`.
