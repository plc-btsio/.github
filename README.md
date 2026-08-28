# Lycée Paul-Louis Courier - BTS SIO

![Bannière BTS SIO PLC](https://raw.githubusercontent.com/plc-btsio/design-assets/main/banniere_bts-sio_paul-louis-courier.png)

---

## Contexte

Ce dépôt sert de support à la présentation et à la configuration de l’organisation GitHub du Lycée Paul-Louis Courier. Il centralise les éléments de référence pour la page publique du profil, les fichiers de contribution et les conventions de sécurité et de collaboration.

---

## Structure du dépôt

Le dépôt suit une organisation simple et cohérente, en fonction des fichiers réellement présents dans le workspace :

```text
plc-btssio_.github/
├── README.md
├── profile/
│   └── README.md
└── .github/
    ├── CODE_OF_CONDUCT.md
    ├── CONTRIBUTING.md
    ├── SECURITY.md
    ├── pull_request_template.md
    └── workflows/
        └── betterleaks-central.yml
```

* **`README.md`** : Document d’accueil du dépôt et présentation générale du projet.
* **`profile/`** : Contient la page de profil GitHub de l’organisation et les éléments de présentation visuelle.
* **`.github/`** : Regroupe les fichiers de configuration, les règles de contribution, de sécurité et le template de pull request.
* **`CODE_OF_CONDUCT.md`** : Définit les règles de conduite et les principes de respect mutuel.
* **`CONTRIBUTING.md`** : Donne les consignes utiles pour contribuer correctement au projet.
* **`SECURITY.md`** : Explique la procédure et les bonnes pratiques en matière de sécurité.
* **`pull_request_template.md`** : Modèle standard pour structurer les pull requests.
* **`workflows/`** : Stocke les workflows GitHub Actions présents dans le dépôt.
* **`betterleaks-central.yml`** : Workflow de supervision ou d’alerte actuel disponible dans le dépôt.

---

## Utilisation du dépôt

### 1. Cloner le dépôt localement

```bash
# 'git clone' : Télécharge une copie locale du dépôt distant.
git clone git@github.com:plc-btsio/.github.git
# 'cd' : Change le répertoire de travail actuel pour entrer dans le dossier cloné.
cd .github
```

### 2. Valider et propager les modifications

```bash
# 'git add .' : Ajoute tous les fichiers modifiés dans la zone de préparation.
git add .
# 'git commit -m' : Enregistre les modifications avec un message descriptif.
git commit -m "docs: mise à jour des fichiers de référence"
# 'git push origin main' : Envoie les changements vers la branche principale du dépôt distant.
git push origin main
```

---

## Fichiers de référence disponibles

Ce dépôt contient les éléments de base pour assurer une gestion cohérente et professionnelle des contributions :

* **`profile/README.md`** : Page de présentation publique de l’organisation GitHub.
* **`CONTRIBUTING.md`** : Guide de contribution pour les personnes souhaitant participer au projet.
* **`CODE_OF_CONDUCT.md`** : Règles de fonctionnement et cadre de comportement.
* **`SECURITY.md`** : Informations et procédure relatives à la sécurité du dépôt.
* **`pull_request_template.md`** : Structure standardisée pour les demandes de modification.
* **`.github/workflows/betterleaks-central.yml`** : Workflow GitHub Actions présent dans le dépôt.

---

<div align="center">
<br>
<small><i>Dernière mise à jour : 28 août 2026</i></small>
</div>
