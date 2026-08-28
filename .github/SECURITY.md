# Politique de sécurité - BTS SIO Paul-Louis Courier

![Bannière BTS SIO PLC](https://raw.githubusercontent.com/plc-btsio/design-assets/main/banniere_bts-sio_paul-louis-courier.png)

---

La sécurité de nos infrastructures et applications est une priorité. Dans une démarche SRE, nous appliquons des standards stricts pour protéger nos dépôts et nos environnements.

## 🔒 Versions supportées

Seule la branche principale (`main`) et les versions (releases) majeures en cours d'exploitation sont activement maintenues pour les correctifs de sécurité.

## 🚨 Signaler une vulnérabilité

**Ne créez jamais d'Issue publique pour une faille de sécurité.** 
Si vous découvrez une vulnérabilité (fuite de secret, faille d'infrastructure, etc.) :
1. Contactez directement et en privé les administrateurs de l'organisation.
2. Fournissez les détails techniques permettant de reproduire ou de comprendre la faille.
3. Attendez la correction avant toute divulgation publique.

**Résponsable de la sécurité :** Louis MEDO ([louis.medo@loutik.fr](mailto:louis.medo@loutik.fr))

## 🛡️ Pratiques de sécurité

* **Aucun secret dans le code :** Les identifiants, clés d'API et certificats ne doivent jamais être commités. 
* **Moindre Privilège (Conteneurs) :** Les environnements conteneurisés (Docker, Podman) doivent être exécutés avec un utilisateur *non-root* et avec des capacités restreintes (dropped capabilities).
* **Analyse automatisée :** Les dépôts doivent, dans la mesure du possible, activer l'analyse des dépendances (ex: Dependabot) et le Secret Scanning.