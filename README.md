# Quickstart

## Prérequis 

- [Git](https://git-scm.com/downloads)
- [Docker desktop](https://docs.docker.com/desktop/)
- [VSCode](https://code.visualstudio.com/) avec [l'extension C++](https://code.visualstudio.com/docs/languages/cpp)

Une fois les outils installés, s'assurer que Docker Desktop soit démarré.

## Lancer l'environnement

- Cloner le projet dans votre répertoire de travail

      test -d ~/workspace || mkdir -p ~/workspace && cd ~/workspace
      git clone https://github.com/cnd-fr/sandbox-c

- Ouvrir VSCode dans le projet `~/workspace/sandbox-c`.
- Dans le fichier docker-compose.yml, lancer le service "ubuntu".
- Ouvrir l'onglet "Explorateur distant"
- Sélectionnez "Conteneurs de développement", puis lancez VSCode dans le conteneur sandbox-c.
