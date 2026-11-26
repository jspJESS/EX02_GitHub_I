# 6. Historial i diferències

**Responsable:** Maximo San Martino Alvarez


## Ordres per consultar els canvis

Explica què mostra cada ordre i afegeix-hi un exemple:

- `git log --oneline`: Mostra l'historial de commits de manera molt resumida, posant cada commit en una sola línia amb l'identificador curt (hash) i el missatge. És molt útil per veure ràpidament l'ordre dels canvis fets al projecte.
- `git show`: Mostra tota la informació detallada d'un commit concret (autor, data, missatge) i exactament quines línies s'han afegit o esborrat en aquell commit.
- `git diff`: Mostra les diferències exactes entre canvis que encara no s'han fet commit (per exemple, entre l'arbre de treball i l'àrea de preparació o l'últim commit), marcant amb + les línies afegides i amb - les eliminades.

## Arbre de treball

Què vol dir que l'arbre de treball estigui net? Quina ordre faries servir per comprovar-ho?

Resposta : Vol dir que no hi ha canvis pendents ni modificats als fitxers del projecte respecte a l'últim commit guardat, ni tampoc fitxers nous sense seguiment (untracked) que no estiguin contemplats. En altres paraules, tot el que hi ha al directori coincideix amb l'estat registrat al repositori.

## Consulta el teu historial

Escriu o enganxa l'ordre que has fet servir per revisar l'historial de la teva branca i explica quina informació hi has trobat.

```bash
git log --oneline
```
## Com fer un git clone

per fer un git clone en la terminal has de posar : git clone [URL DEL REPOSITORI]
