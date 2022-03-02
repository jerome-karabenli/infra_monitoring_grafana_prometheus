# Monitorer son infrastructure avec Grafana et Prometheus

<div id="top"></div>


<!-- ABOUT THE PROJECT -->
## A propos
Dans ce repo vous trouverez un fichier principal qui se base sur `docker-compose`, ainsi qu'une configuration optimisée pour consommer le moins de ressources possible et une configuration de regles d'alerting prête a l'emploi.

## Stack utilisée
* [Docker](https://www.docker.com/)
* [Prometheus (promQL)](https://prometheus.io/)
* [Grafana](https://grafana.com/)
* [AlertManager](https://prometheus.io/docs/alerting/latest/alertmanager/)

## Prérequis
* [Docker et docker-compose](https://docs.docker.com/engine/install/)


<!-- ROADMAP -->
## Roadmap

- [x] Configurer le fichier docker-compose.
- [x] Réduire la consommation CPU de Cadvisor
- [x] Rédiger les regles d'alerting
- [x] Modeliser le dashboard Grafana

Voir les [issues en cours](https://github.com/jerome-karabenli/infra_monitoring_grafana_prometheus/issues) pour voir la liste complete des fonctionalités proposées et les bugs existants.


<!-- HOW TO -->
## Documentation
Vous trouverez [__un article sur mon blog__](https://jkarabenli.dev/posts/infra_monitoring_grafana_prometheus/) expliquant l'utilisation des fichiers dans ce repo. 

<!-- CONTRIBUTING -->
## Contribuer

Les contributions sont ce qui fait de la communauté open source un endroit incroyable pour apprendre, s'inspirer et créer. Toutes les contributions que vous apportez serront __grandement appréciées__.

Si vous avez une suggestion qui améliorerait le projet, vous pouvez `fork` le repo et créer une `pull request`. Vous pouvez aussi simplement ouvrir une `issue` avec le tag "enhancement".
N'oubliez pas de mettre une étoile au projet ! Merci encore!


1. Fork le projet
2. Créez votre branche (`git checkout -b feature/AmazingFeature`)
3. Commit vos changements (`git commit -m 'Add some AmazingFeature'`)
4. Push sur votre branche (`git push origin feature/AmazingFeature`)
5. Ouvrir une __Pull Request__


<!-- CONTACT -->
## Liens

Lien du blog: [jkarabenli.dev](https://jkarabenli.dev/posts)

Lien du projet: [Github](https://github.com/jerome-karabenli/infra_monitoring_grafana_prometheus)