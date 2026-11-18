# 1. Flux bàsic de Git

**Responsable:** alumne/a 1

## Per a què serveix Git?

Git és un sistema de control de versions que registra els canvis d'un projecte. Permet consultar-ne l'historial, recuperar versions anteriors i treballar en equip sense sobreescriure directament els canvis dels altres.

## Què fa cada ordre?

- `git clone`: crea una còpia local d'un repositori remot.
- `git status`: mostra la branca actual i l'estat dels fitxers: modificats, preparats o sense seguiment.
- `git add`: prepara els canvis indicats perquè s'incloguin al pròxim commit.
- `git commit`: desa els canvis preparats com una nova versió a l'historial local.

## Exemple de treball

Primer clono el repositori i entro a la carpeta. Després edito el fitxer assignat, comprovo l'estat, preparo el fitxer i creo el commit.

```bash
git clone https://github.com/jspJESS/EX02_GitHub_I.git
cd EX02_GitHub_I
git switch -c ex02-01-codex-simulacio
# Edito 01_flux_basic.md
git status
git add 01_flux_basic.md
git commit -m "Completa l'apartat 1"
```

## Comprova la teva explicació

Un fitxer modificat té canvis al directori de treball però encara no està preparat per al commit. Un fitxer preparat ha passat per `git add` i s'inclourà al pròxim commit.

