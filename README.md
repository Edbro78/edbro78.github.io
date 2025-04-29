# Eksempel på GitHub Markdown

Denne filen demonstrerer grunnleggende skrive- og formateringssyntaks på GitHub ved hjelp av Markdown, basert på [GitHubs dokumentasjon](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

## Overskrifter

Markdown bruker `#` for å lage overskrifter. Antallet `#` bestemmer nivået.

# Dette er Overskrift 1 (H1)
## Dette er Overskrift 2 (H2)
### Dette er Overskrift 3 (H3)
#### Dette er Overskrift 4 (H4)
##### Dette er Overskrift 5 (H5)
###### Dette er Overskrift 6 (H6)

---

## Tekstformatering

Du kan enkelt formatere tekst for å fremheve den.

*Denne teksten er kursiv.*
_Denne teksten er også kursiv._

**Denne teksten er fet.**
__Denne teksten er også fet.__

***Denne teksten er fet og kursiv.***
___Denne teksten er også fet og kursiv.___

~~Denne teksten er gjennomstreket.~~

---

## Lister

### Uordnet liste (punktliste)

Bruk bindestrek (`-`), stjerne (`*`) eller plusstegn (`+`) for å lage uordnede lister.

- Punkt 1
- Punkt 2
  - Underpunkt 2.1 (bruk innrykk)
  - Underpunkt 2.2
* Punkt 3 (bruker stjerne)
+ Punkt 4 (bruker pluss)

### Ordnet liste (nummerert liste)

Bruk tall etterfulgt av punktum.

1. Første element
2. Andre element
   1. Underpunkt 2.1 (nummerering starter på nytt med innrykk)
   2. Underpunkt 2.2
3. Tredje element

---

## Lenker

Du kan lage lenker på flere måter.

Dette er en [inline lenke til GitHub](https://github.com).
Dette er en lenke med en tittel: [GitHub Docs](https://docs.github.com/ "GitHub Dokumentasjon").

Du kan også bruke referansestil-lenker:
Her er en referanse til [Google][google-link].
Og her er en annen til [Wikipedia][wiki-ref].

[google-link]: https://www.google.com "Søkemotor"
[wiki-ref]: https://www.wikipedia.org

URL-er blir ofte automatisk lenket: https://www.google.com

---

## Bilder

Bruk `![Alt-tekst](URL "Bildetittel")` for å sette inn bilder.

![GitHub Octocat](https://github.githubassets.com/images/modules/logos_page/Octocat.png "GitHub Octocat Logo")

Du kan også kombinere bilder og lenker:
[![GitHub Octocat](https://github.githubassets.com/images/modules/logos_page/Octocat.png "Klikk for å gå til GitHub")](https://github.com)

---

## Kode

### Inline kode

Bruk enkle backticks (`` ` ``) rundt koden for å formatere den inline, f.eks. `git status` eller `npm install`.

### Kodeblokker

Bruk tre backticks (```` ``` ````) før og etter kodeblokken. Du kan spesifisere språket etter de første tre backticks for syntaksutheving.

```javascript
function greet(name) {
  console.log(`Hello, ${name}!`);
}

greet('World');
