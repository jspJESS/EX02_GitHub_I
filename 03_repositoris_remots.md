
# 3. Repositoris remots

**Responsable:** Pau Constanseu

## Conceptes

- **Què vol dir `origin`?**  
  És el nom que Git dona normalment al repositori remot principal, com per exemple un repositori de GitHub.

- **Què fa `git push`?**  
  Serveix per pujar els commits del nostre repositori local al repositori remot.

- **Què fa `git pull`?**  
  Descarrega els canvis del repositori remot i els integra a la nostra branca local.

- **Què fa `git fetch` i en què es diferencia de `git pull`?**  
  `git fetch` descarrega els canvis del repositori remot, però no els aplica directament a la nostra branca. En canvi, `git pull` els descarrega i també els integra automàticament.

## Ordres per pujar una branca

Per pujar per primera vegada a `origin` la meva branca `BrancaPauC`, utilitzarem aquesta ordre:

    git push -u origin BrancaPauC

L'opció `-u` serveix per vincular la branca local amb la branca remota. D'aquesta manera, les pròximes vegades podrem utilitzar simplement `git push` o `git pull` sense haver d'especificar el repositori i la branca.

## Si una altra persona ja ha actualitzat main

Si una altra persona ha fet canvis a la branca `main` del repositori remot, primer ens situarem a la nostra branca local `main` i després descarregarem els canvis.

    git switch main
    git pull origin main

- **`git switch main`:** ens permet canviar a la branca `main` del nostre repositori local.
- **`git pull origin main`:** descarrega els últims canvis de la branca `main` remota i els integra a la nostra branca local.

Així tindrem la branca `main` actualitzada amb els canvis que hagin fet els altres companys.

