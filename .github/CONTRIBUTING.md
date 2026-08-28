# Guide de contribution - BTS SIO Paul-Louis Courier

![Bannière BTS SIO PLC](https://raw.githubusercontent.com/plc-btsio/design-assets/main/banniere_bts-sio_paul-louis-courier.png)

---

Merci de souhaiter contribuer à nos projets ! Afin de garantir la fiabilité de nos infrastructures et applications, nous appliquons des standards de l'industrie (SRE / GitOps).

## 🌿 Stratégie de branches
* `main` : Branche de production. Le code doit toujours y être fonctionnel. **Aucun push direct n'est autorisé.**
* `feature/nom-de-la-feature` : Créez une branche dédiée pour chaque nouvelle fonctionnalité ou correction.

## 📝 Format des commits (Conventional Commits)
Pour automatiser la génération des changelogs et garder un historique propre, utilisez les préfixes suivants :
* `feat:` (Nouvelle fonctionnalité)
* `fix:` (Correction de bug)
* `docs:` (Documentation, ex: MkDocs)
* `infra:` (Modification d'architecture, ex: Ansible, Docker)

## 🔄 Processus de Pull Request (PR)
1. **Développement :** Travaillez sur votre branche de `feature`.
2. **Tests locaux :** Vérifiez que votre code fonctionne avant de l'envoyer.
3. **Ouverture de la PR :** Décrivez clairement ce que fait votre code.
4. **Peer Review :** Au moins une approbation d'un pair est requise avant de fusionner.
5. **CI/CD :** Les pipelines d'intégration continue doivent valider votre code (tests, linting) automatiquement.

## 🔐 Sécurité et Secrets
* Ne commitez **jamais** de mots de passe, de clés d'API ou de tokens.
* Utilisez des fichiers `.env` ignorés par Git (via `.gitignore`) ou des gestionnaires de secrets.