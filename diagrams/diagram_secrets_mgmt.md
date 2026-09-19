```mermaid
flowchart LR
    Dev[Développeur] -->|ne committe jamais de secret| Git[Dépôt Git]
    Vault[(Coffre à secrets<br/>ex. Vault / K8s Secrets chiffrés)] -->|injection à l'exécution| Pod[Pod applicatif]
    CI[Pipeline CI/CD] -->|référence uniquement, jamais la valeur| Vault
    Admin[Administrateur] -->|gère droits par environnement| Vault
```