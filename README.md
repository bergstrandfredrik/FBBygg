# F. Bergstrand Bygg AB

Officiell hemsida för F. Bergstrand Bygg AB – en lokal byggfirma
med utgångspunkt i Ängelholm och över 10 års erfarenhet inom bygg
och snickeri.

**Hemsida:** https://fbergstrandbygg.se/

## Om projektet

Webbplatsen är framtagen för att presentera företagets tjänster,
referensprojekt och kontaktuppgifter samt generera nya
kundförfrågningar genom lokal sökmotoroptimering (SEO).

## Funktioner

- Responsiv design för dator, surfplatta och mobil.
- Mobilanpassad navigationsmeny.
- Projektgalleri med egna referensbilder.
- Före-, under- och efterbilder från byggprojekt.
- Sökmotoroptimerade tjänstesidor.
- Internlänkning mellan relevanta tjänster.
- Kontaktvägar för kostnadsfria offertförfrågningar.
- Företagsanpassad logotyp och favicon.
- Strukturerad data med Schema.org.
- Open Graph-metadata för sociala medier.
- Sitemap.xml och robots.txt.
- HTTPS med egen domän.

## Teknik

| Teknik       | Användningsområde            |
| ------------ | ---------------------------- |
| HTML5        | Innehåll och struktur        |
| CSS3         | Design och responsiv layout  |
| JavaScript   | Interaktivitet och mobilmeny |
| WebP         | Optimerade projektbilder     |
| SVG          | Logotyp och favicon          |
| Git          | Versionshantering            |
| GitHub Pages | Webbhosting                  |
| One.com      | Domän och DNS                |

Webbplatsen är helt statisk och kräver ingen databas,
backend, externa JavaScript-ramverk eller byggprocess.

## Projektstruktur

```text
FBBygg/
├── assets/
│   ├── images/
│   ├── favicon.svg
│   └── logo-white.svg
├── tjanster/
│   ├── altaner/
│   │   └── index.html
│   ├── koksrenovering/
│   │   └── index.html
│   └── renovering/
│       └── index.html
├── CNAME
├── index.html
├── README.md
├── robots.txt
├── sitemap.xml
└── style.css
```

## Tjänstesidor

### Färdigställda

- [ROT & renovering](https://fbergstrandbygg.se/tjanster/renovering/)
- [Köksrenovering](https://fbergstrandbygg.se/tjanster/koksrenovering/)
- [Altaner & utekök](https://fbergstrandbygg.se/tjanster/altaner/)

### Planerade

- [ ] Fasadrenovering
- [ ] Takarbeten
- [ ] Staket & grindar
- [ ] Fönster & dörrar
- [ ] Tillbyggnader
- [ ] Nyproduktion
- [ ] Betong & grunder
- [ ] Byggservice
- [ ] Företag & entreprenad

## Sökmotoroptimering (SEO)

Webbplatsen är anpassad för lokal synlighet i Ängelholm
och omkringliggande orter.

SEO-arbetet omfattar:

- Unika sidtitlar och metabeskrivningar.
- Semantisk HTML och tydlig rubrikstruktur.
- Canonical-adresser.
- Beskrivande alt-texter för bilder.
- Optimerade bildstorlekar.
- Strukturerad data i JSON-LD-format.
- Internlänkning mellan tjänstesidor.
- Mobilanpassning.
- Lokal geografisk relevans.
- Sitemap och robots.txt.

### SEO-resurser

- Sitemap: https://fbergstrandbygg.se/sitemap.xml
- Robots: https://fbergstrandbygg.se/robots.txt

## Lokal utveckling

Projektet utvecklas i Visual Studio Code med Git
och UCRT64-terminal.

Klona projektet:

```bash
git clone https://github.com/bergstrandfredrik/FBBygg.git
cd FBBygg
```

Webbplatsen kan förhandsvisas med en lokal webbserver,
exempelvis Live Server i Visual Studio Code.

Ingen installation av projektberoenden krävs.

## Branchstrategi

| Branch                 | Syfte                                  |
| ---------------------- | -------------------------------------- |
| main                   | Produktionsversion av hemsidan         |
| seo-2027               | Fortsatt utveckling och SEO-arbete     |
| backup-before-seo-2027 | Säkerhetskopia före större uppdatering |

Större förändringar utvecklas och testas på en separat
branch innan de publiceras till main.

Säkerhetskopian ska bevaras för eventuell återställning.

## Publicering

Webbplatsen publiceras automatiskt via GitHub Pages
när ändringar pushas till main.

### GitHub Pages

- Source: Deploy from a branch
- Branch: main
- Folder: / (root)
- Custom domain: fbergstrandbygg.se
- HTTPS: Enforce HTTPS

Domänens DNS hanteras via One.com.

Filen CNAME ska bevaras för att säkerställa kopplingen
mellan GitHub Pages och företagets domän.

## Underhåll

Vid framtida uppdateringar:

- Kontrollera interna länkar och bildsökvägar.
- Testa webbplatsen på dator och mobil.
- Optimera nya projektbilder före publicering.
- Uppdatera sitemap.xml när nya sidor tillkommer.
- Kontrollera metadata och strukturerad data.
- Verifiera publiceringen via GitHub Actions.
- Följ upp indexering via Google Search Console.

## Fortsatt utveckling

- [x] Ny startsida
- [x] Responsiv design
- [x] Mobilmeny
- [x] Projektgalleri
- [x] Före- och efterbilder
- [x] Företagslogotyp
- [x] Favicon
- [x] Grundläggande SEO
- [x] Strukturerad data
- [x] Tre individuella tjänstesidor
- [x] Sitemap.xml
- [x] Robots.txt
- [x] Säkerhetskopia av tidigare hemsida
- [x] Merge och push till main
- [ ] Slutlig verifiering av livehemsidan
- [ ] Google Search Console
- [ ] Indexering av nya tjänstesidor
- [ ] Resterande nio tjänstesidor
- [ ] Löpande uppdatering av referensprojekt
- [ ] Fortsatt lokal SEO och organisk marknadsföring

## Kontakt

**F. Bergstrand Bygg AB**

- Organisationsnummer: 559569-2517
- Utgångspunkt: Ängelholm
- Telefon: 072-962 54 40
- E-post: fredrik@fbergstrandbygg.se
- Hemsida: https://fbergstrandbygg.se/
- [Facebook](https://www.facebook.com/profile.php?id=61596413686099)
- [Instagram](https://www.instagram.com/f.bergstrandbyggab/)

## Upphovsrätt

Copyright © 2026 F. Bergstrand Bygg AB.

Alla rättigheter förbehållna.

Webbplatsens källkod, design, texter, logotyper och
projektbilder får inte kopieras, återanvändas eller
distribueras utan tillstånd från F. Bergstrand Bygg AB.
