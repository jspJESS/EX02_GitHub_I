
# 3. Repositoris remots

**Responsable:** Pau Constanseu

## Conceptes

- **Què significa `origin`?**  
  És el nom que Git utilitza habitualment per identificar el repositori remot principal, que normalment es troba a GitHub.

- **Per a què serveix `git push`?**  
  Aquesta ordre permet enviar els commits que hem fet al nostre repositori local cap al repositori remot.

- **Quina funció té `git pull`?**  
  Serveix per descarregar les actualitzacions del repositori remot i incorporar-les a la nostra branca local.

- **Què fa `git fetch` i quina diferència té amb `git pull`?**  
  `git fetch` descarrega els canvis del repositori remot, però no els incorpora directament a la branca en què estem treballant. En canvi, `git pull` descarrega aquests canvis i els integra automàticament.

## Ordres per pujar una branca

Per pujar per primera vegada la meva branca `BrancaPauC` al repositori remot `origin`, hem d'executar la següent ordre:

    git push -u origin BrancaPauC

L'opció `-u` permet establir una connexió entre la nostra branca local i la branca remota. Això facilita les pròximes actualitzacions, ja que podrem fer servir `git push` i `git pull` sense haver d'indicar cada vegada el nom del repositori i de la branca.

## Si una altra persona ja ha actualitzat main

Si un company ha pujat nous canvis a la branca `main` del repositori remot, haurem d'actualitzar la nostra branca local per tenir la versió més recent.

Per fer-ho, executarem aquestes ordres:

    git switch main
    git pull origin main

- **`git switch main`:** serveix per situar-nos a la branca local `main`.
- **`git pull origin main`:** descarrega els canvis de la branca `main` del repositori remot i els incorpora a la nostra branca local.

D'aquesta manera, tindrem la branca `main` actualitzada amb les últimes modificacions que hagin fet els altres membres del grup.