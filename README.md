# ATD_Chef_Projet_Devops
# [Nom du projet] — Chaîne CI/CD et transformation DevOps
 
## Contexte
 
Vous prenez la responsabilité DevOps d'une plateforme nationale permettant aux usagers d'accéder à plusieurs services numériques. La plateforme repose sur des applications conteneurisées et un cluster Kubernetes. Les équipes utilisent Git pour la gestion du code, mais les mises en production comportent encore plusieurs interventions manuelles. Au cours des deux derniers mois, quatre incidents ont été enregistrés après déploiement, dont deux ont nécessité une restauration de la version précédente. Les environnements de développement, de recette et de production présentent également des écarts de configuration. La direction souhaite désormais passer à des mises en production hebdomadaires, réduire les risques de régression et garantir un retour arrière rapide en cas d'incident.
 
**Voici les objectifs fixés par la direction :**

1. Passer à des mises en production hebdomadaires.
2. Réduire le risque de régression.
3. Garantir un retour arrière rapide en cas d'incident.
 
## Sommaire
 
- [Tâche 1 — Architecture cible de la chaîne CI/CD](docs/01-architecture-cible.md)
- [Tâche 2 — Plan de transformation DevOps sur 3 mois](docs/02-plan-transformation.md)
## Structure du dépôt
 
```
.
├── README.md
├── docs/
│   ├── 01-architecture-cible.md
│   └── 02-plan-transformation.md
└── diagrams/
    ├── diagram_pipeline.md
    ├── diagram_flow_rollback.md
    └── diagram_secrets_mgmt.md
    └── diagram_cluster.md
```
