# EX02 · GitHub I — examen pràctic

**Modalitat:** treball col·laboratiu en un equip de sis alumnes  
**Durada orientativa:** 90 minuts  
**Lliurament:** repositori del grup, pull requests i un document individual d'evidències

## Repte

Entre tots sis elaborareu una guia breu de supervivència per a estudiants que comencen a fer servir Git i GitHub. Cada persona completarà un apartat diferent. Treballareu amb branques i pull requests, i us revisareu entre vosaltres.

El repositori és compartit. Cada alumne ha de fer servir el seu propi compte de GitHub perquè es pugui identificar l'autoria de la pull request.

## Repartiment de tasques

Completa únicament el fitxer que tens assignat:

| Alumne/a | Fitxer | Tema |
|---|---|---|
| 1 | [01_flux_basic.md](01_flux_basic.md) | `clone`, `status`, `add` i `commit` |
| 2 | [02_branques.md](02_branques.md) | Crear, canviar i fer servir branques |
| 3 | [03_repositoris_remots.md](03_repositoris_remots.md) | `origin`, `push`, `pull` i `fetch` |
| 4 | [04_pull_requests.md](04_pull_requests.md) | Obrir una pull request i entendre base i compare |
| 5 | [05_revisio.md](05_revisio.md) | Revisar canvis i respondre a una revisió |
| 6 | [06_historial.md](06_historial.md) | Consultar l'historial i comparar canvis |

## Flux de treball obligatori

### 1. Clona el repositori

Obre un terminal a la carpeta on desaràs el treball:

```bash
git clone https://github.com/jspJESS/EX02_GitHub_I.git
cd EX02_GitHub_I
```

### 2. Crea una branca per a la teva tasca

Fes servir el teu número i el teu usuari de GitHub al nom. Per exemple:

```bash
git switch -c ex02-01-usuari
```

Canvia `01` pel teu número i `usuari` pel teu nom d'usuari de GitHub. No treballis directament a `main`.

### 3. Completa el teu fitxer

Edita només el fitxer que tens assignat. Explica els conceptes amb les teves paraules i inclou les ordres que et demana l'apartat.

Comprova els canvis:

```bash
git status
```

### 4. Crea un commit i puja la branca

```bash
git add nom-del-fitxer.md
git commit -m "Completa l'apartat assignat"
git push -u origin ex02-01-usuari
```

Canvia el nom del fitxer i de la branca pels teus.

### 5. Obre una pull request

A GitHub, crea una pull request amb:

- **base:** `main`;
- **compare:** la teva branca;
- un títol que indiqui la tasca;
- una descripció breu dels canvis.

Demana la revisió del company o companya que tens a la dreta. Numereu els llocs en cercle i seguiu aquest torn: **la pull request de l'alumne 1 la revisa l'alumne 2; la de l'alumne 2, l'alumne 3; la de l'alumne 3, l'alumne 4; la de l'alumne 4, l'alumne 5; la de l'alumne 5, l'alumne 6; i la de l'alumne 6, l'alumne 1**.

### 6. Revisa i completa el procés

El revisor ha de llegir els canvis i deixar una observació concreta. Pot aprovar-los o demanar una correcció. Si l'autor rep comentaris, els respon i actualitza la mateixa branca.

Quan la pull request estigui aprovada, l'autor fa el merge a `main`. No feu push directament a `main`.

## Lliurament individual

Cada alumne lliurarà a la professora:

1. L'URL del repositori del grup.
2. L'enllaç a la seva pròpia pull request.
3. L'enllaç a la pull request que ha revisat segons el torn assignat.
4. Un document individual en PDF o DOCX amb captures i explicacions, seguint la [plantilla d'evidències](PLANTILLA_EVIDENCIES.md).

Anomena el document `EX02_Cognoms_UsuariGitHub.pdf` (o `.docx`). No incloguis contrasenyes, tokens ni cap altra dada privada a les captures.

## Avaluació

Consulta la [rúbrica d'avaluació](RUBRICA.md). La nota combina el procés individual, la revisió entre companys i la qualitat final de la guia.

> Per clonar un repositori públic no cal cap invitació. Per pujar-hi branques, sí que necessites permís d'escriptura i haver acceptat la invitació de col·laborador.
