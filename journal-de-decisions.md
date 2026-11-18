# Journal de décisions — projet Kactus

Pour chaque décision : ce qui était proposé, ce que j'ai retenu, et pourquoi.

## Environnement

### 1. Système de la VM

- **Proposé :** une VM Ubuntu ou Debian, avec accès à Internet (fiche d'environnement).
- **Retenu :**
- **Pourquoi :**

### 2. Processeur de la VM

- **Proposé :** rien de précisé par la fiche d'environnement.
- **Retenu :**
- **Pourquoi :**

### 3. Mémoire du cluster et kdump

- **Proposé :** mémoire du cluster = mémoire de la VM moins 2 Go (fiche d'environnement).
- **Retenu :**
- **Pourquoi :**

### 4. Accès à Docker sans sudo

- **Proposé :** rien dans le sujet ; Minikube refuse de tourner en root avec le pilote Docker.
- **Retenu :**
- **Pourquoi :**

### 5. Options de démarrage de Minikube

- **Proposé :** Minikube démarré avec la seule option de mémoire de la fiche d'environnement, sans aucune autre option (partie IV).
- **Retenu :**
- **Pourquoi :**

## Application

### 6. Secrets

- **Proposé :** ConfigMaps et Secrets Kubernetes, tous versionnés dans le dépôt Git (partie III), avec un dépôt GitHub public (fiche d'environnement).
- **Retenu :**
- **Pourquoi :**

### 7. Base de données

- **Proposé :** tous les services, base de données comprise, déployés avec 2 réplicas pour viser 99,99 % de disponibilité (partie II).
- **Retenu :**
- **Pourquoi :**

### 8. Règles réseau

- **Proposé :** des règles strictes d'accès réseau : seule l'application web peut joindre la base de données (partie III).
- **Retenu :**
- **Pourquoi :**
