# MH_docker_service

kubectl
minikube

Kubernetes a 3 fonctions (tous les clouds utilisent Kubernetes :
- Déploiement : Déploiement d'applications encapsulée dans des images Docker (mécanique de virtualization, seul logiciel utile pour exécuter des images --> cloud native) dans un cluster de machines (en réseau) où est installé Kubernetes.
- Maintien des app en fonctionnement : Redemarrage automatique des app en échec
- Scaling d'app : Augmenter ou diminuer le nombre d'instances de la même image Docker. Intérets ? Tolérances aux pannes & Load répartition des charges
