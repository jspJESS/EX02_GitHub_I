
# 1. Flux bàsic de Git

**Responsable:** alumne/a 1 (Rui Huang)

Completa aquest apartat amb les teves paraules.

## Per a què serveix Git?

Git serveix per controlar els canvis dels fitxers d'un projecte. Ens permet guardar diferents versions, recuperar canvis anteriors i treballar en equip sense perdre informació.

## Què fa cada ordre?

- `git clone`: Serveix per copiar un repositori remot al nostre ordinador.
- `git status`: Mostra l'estat dels fitxers i els canvis que hem fet.
- `git add`: Prepara els fitxers modificats per guardar-los en un commit.
- `git commit`: Guarda els canvis preparats amb un missatge que explica què hem modificat.

## Exemple de treball

Escriu les ordres que faries servir per clonar el repositori, modificar un fitxer i desar el canvi en un commit. Explica breument cada pas.

```bash
git clone https://github.com/usuari/projecte.git
cd projecte
# Modifiquem el fitxer README.md i el guardem
git status
git add README.md
git commit -m "Actualitzar el README"
```

**Explicació dels passos:**

1. Primer clonem el repositori amb `git clone`.
2. Entrem a la carpeta del projecte amb `cd projecte`.
3. Modifiquem el fitxer `README.md` i guardem els canvis.
4. Utilitzem `git status` per comprovar els canvis.
5. Amb `git add` preparem el fitxer modificat.
6. Finalment, amb `git commit` guardem els canvis amb un missatge.

## Comprova la teva explicació

Quina diferència hi ha entre un fitxer modificat i un fitxer preparat per al commit?

Un fitxer modificat és aquell en què hem fet canvis, però encara no està preparat per al commit. En canvi, un fitxer preparat és aquell que ja hem afegit amb `git add` i està llest per guardar-se amb `git commit`.


💻