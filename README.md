# KAIZEN

Ce projet a pour objectif de créer une infrastructure cloud évolutive et résiliente sur Azure. Il comprend le déploiement d'un équilibreur de charge et de deux machines virtuelles hébergeant un site web, ainsi que la mise en place d'un pipeline CI/CD pour automatiser la construction et le déploiement de l'application.

## Fonctionnalités

* **Equilibreur de charge :** Répartit le trafic entre les deux machines virtuelles pour assurer la haute disponibilité.
* **Machines virtuelles :** Hébergent le site web et sont configurées pour se mettre à l'échelle automatiquement en fonction de la charge.
* **Mise à l'échelle automatique :** Augmente le nombre de machines virtuelles si l'utilisation du CPU dépasse 50% pendant 5 minutes.
* **Zones de disponibilité :** Les machines virtuelles sont déployées dans des zones de disponibilité distinctes pour garantir la redondance en cas de panne.
* **Azure Key Vault :** Stocke les secrets du projet de manière sécurisée.
* **Pipeline CI/CD :** Automatise la construction, les tests et le déploiement de l'application.

## Technologies utilisées

* Azure DevOps
* GitHub
* Azure Key Vault
* Azure Virtual Machines
* Azure Load Balancer
* [langage de programmation]

## Instructions de déploiement

1. Cloner le dépôt GitHub.
2. Créer un Azure Key Vault et y stocker les secrets du projet.
3. Configurer le pipeline CI/CD dans Azure DevOps.
4. Lancer le pipeline pour déployer l'infrastructure sur Azure.


