# Concevoir et améliorer l’UI/UX

Skill Codex en français pour créer ou améliorer les interfaces d’un logiciel de bureau, web ou mobile.

## Ce qu’il apporte

- Observer les écrans et les parcours, en distinguant les défauts constatés des hypothèses à tester.
- Rechercher des recommandations officielles et des produits comparables.
- Proposer des changements concrets et priorisés, avec sources, compromis et critères de vérification.
- Couvrir la navigation, les interactions, la présentation, le contenu et l’accessibilité.
- Produire des schémas ou maquettes lorsque cela facilite la décision.
- Implémenter et vérifier les changements lorsque la demande le prévoit.

Une tendance graphique peut inspirer une solution ; elle ne démontre pas à elle seule un bénéfice UX. Le skill privilégie les tâches des utilisateurs et les contraintes du produit.

## Installation

Copier ce dépôt dans un dossier nommé `concevoir-ameliorer-ui-ux` à l’intérieur de votre répertoire de skills Codex :

- Windows : `%USERPROFILE%\.codex\skills\concevoir-ameliorer-ui-ux`
- macOS / Linux : `~/.codex/skills/concevoir-ameliorer-ui-ux`

Si `CODEX_HOME` est personnalisé, utiliser son sous-dossier `skills`.

Le dossier installé doit contenir directement `SKILL.md` et `agents/openai.yaml`.

## Exemples d’utilisation

### Examiner un programme existant

> Utilise $concevoir-ameliorer-ui-ux pour analyser l’interface de ce programme, rechercher des références pertinentes et proposer les améliorations prioritaires, sans modifier le code.

### Concevoir une interface

> Utilise $concevoir-ameliorer-ui-ux pour concevoir le parcours et les écrans d’un outil de classement de photos destiné à des utilisateurs débutants. Compare les solutions pertinentes et propose une direction.

### Réaliser une amélioration

> Utilise $concevoir-ameliorer-ui-ux pour améliorer le parcours de configuration de ce projet. Recherche des références adaptées, implémente les changements utiles et vérifie le rendu et les interactions.

## Fonctionnement et limites

Le skill fournit des instructions réutilisables ; il n’installe aucun outil et ne dépend pas d’un framework particulier. La recherche externe, l’observation de l’application et les maquettes utilisent les capacités disponibles dans la session.

Une demande de propositions ne déclenche pas automatiquement une modification du code. Les vérifications techniques ou manuelles ne sont pas présentées comme des tests utilisateurs. Un contrôle partiel d’accessibilité ne vaut pas déclaration de conformité.

## Contenu

- [SKILL.md](SKILL.md) : instructions de travail et références de départ.
- [agents/openai.yaml](agents/openai.yaml) : nom et exemple d’invocation pour l’interface Codex.

La structure du skill a été validée avec l’outil de validation de skill-creator. Son efficacité doit être évaluée sur les cas d’usage réels.
