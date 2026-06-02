# 8Bit_From_Scratch

Bienvenue dans **Construire son ordinateur 8 bits : Le guide pas à pas**.

Ce dépôt suit un parcours en 4 parties et 12 chapitres pour concevoir un ordinateur 8 bits from scratch, de la théorie des portes logiques jusqu'au débogage de programmes en langage machine.

## Format O'Reilly (AsciiDoc)

Ce livre est structuré au format O'Reilly Media, utilisant **AsciiDoc** comme format source.

### Structure du projet

```
book.adoc          ← Fichier maître (point d'entrée)
atlas.json         ← Configuration de publication O'Reilly Atlas
partie-1/          ← PARTIE I : Les fondations (Théorie & Matériel)
partie-2/          ← PARTIE II : Module par module (Le guide de câblage)
partie-3/          ← PARTIE III : L'intelligence de la machine
partie-4/          ← PARTIE IV : Programmation & Débogage
annexes/           ← Fiches techniques simplifiées
```

### Générer le livre

Pour générer le livre en différents formats :

```bash
# HTML
asciidoctor book.adoc -o build/book.html

# PDF (nécessite asciidoctor-pdf)
asciidoctor-pdf book.adoc -o build/book.pdf

# EPUB (nécessite asciidoctor-epub3)
asciidoctor-epub3 book.adoc -o build/book.epub
```

### Prérequis

- [Asciidoctor](https://asciidoctor.org/) (rendu de base)
- [asciidoctor-pdf](https://github.com/asciidoctor/asciidoctor-pdf) (génération PDF)
- [asciidoctor-epub3](https://github.com/asciidoctor/asciidoctor-epub3) (génération EPUB)
