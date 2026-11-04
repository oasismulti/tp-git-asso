# TP Git Association

> ## 📘 TD GitHub Actions en binôme — rendu
> **Binôme :** Sofiane (A) · Valentin Cano (B) — valentincano0904@orange.fr
>
> | Livrable | Lien |
> |---|---|
> | 📄 **Compte rendu PDF** (captures + explications + questions 1 et 2) | [docs/Compte-rendu-TD-GitHub-Actions.pdf](docs/Compte-rendu-TD-GitHub-Actions.pdf) |
> | 📝 Compte rendu en ligne | [docs/compte-rendu.md](docs/compte-rendu.md) |
> | ✅ Workflow de vérification | [.github/workflows/verification.yml](.github/workflows/verification.yml) |
> | 🚀 Workflow de déploiement Pages | [.github/workflows/static.yml](.github/workflows/static.yml) |
> | ▶️ Exécutions GitHub Actions | [Onglet Actions](https://github.com/oasismulti/tp-git-asso/actions) |
> | 🔀 Pull request du TD | [PR #1](https://github.com/oasismulti/tp-git-asso/pull/1) |
> | 🖼️ Captures d'écran | [docs/captures/](docs/captures/) |

Site web statique (HTML/CSS) pour une association, réalisé dans le cadre d'un travail pratique sur Git. Il sert à mettre en pratique la gestion de versions avec Git et GitHub : branches, commits, Pull Requests.

## Prérequiss

- Un navigateur web récent (Chrome, Firefox, Edge, Safari)
- Git pour récupérer le projet et suivre ses modifications
- Un éditeur de code, par exemple Visual Studio Code

Aucune dépendance (Node.js, base de données, etc.) n'est nécessaire.

## Installation

Cloner le dépôt :
```bash
git clone https://github.com/oasismulti/tp-git-asso.git
```
Se placer dans le dossier du projet :
```bash
cd tp-git-asso
```
Ouvrir le dossier dans Visual Studio Code (ou un autre éditeur) :
```bash
code .
```

## Lancement

Ouvrir le fichier `index.html` dans un navigateur (double-clic, ou clic droit > Ouvrir avec).

Le site s'affiche directement : il n'y a pas de serveur à démarrer.

## Structure du projet

```text
tp-git-asso/
├── index.html   # structure et contenu de la page
├── style.css    # mise en forme et apparence
├── .gitignore   # fichiers ignorés par Git
└── README.md    # ce fichier
```

## Contribution

Se placer sur la branche principale et récupérer les dernières modifications :
```bash
git switch main
git pull
```

## TD GitHub Actions (binôme)

| Rôle | Membre | Contact |
|------|--------|---------|
| A | Sofiane | — |
| B | Valentin Cano | valentincano0904@orange.fr |

- Vérification automatique : `.github/workflows/verification.yml` (job `controle`, sur `push` et `pull_request` vers `main`)
- Déploiement : `.github/workflows/static.yml` (GitHub Pages)
- Compte rendu avec captures et réponses aux questions : [`docs/compte-rendu.md`](docs/compte-rendu.md) — version PDF : [`docs/Compte-rendu-TD-GitHub-Actions.pdf`](docs/Compte-rendu-TD-GitHub-Actions.pdf)
