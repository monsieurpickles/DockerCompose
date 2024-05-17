# DockerCompose

Ce projet contient une application Wordpress déployée avec Docker Compose. L'application est composée d'un conteneur Wordpress et d'un conteneur MySQL.

## Structure du projet

```markdown
ChallengeDockerCompose/
├── docker/
│ └── docker-compose.yml
├── wordpress/
│ └── wp-config.php
├── mysql/
│ └── my.cnf
├── .env
└── README.md
```

- Le répertoire `docker/` contient le fichier `docker-compose.yml` qui définit les services et la configuration Docker.
- Le répertoire `wordpress/` peut contenir des fichiers de configuration Wordpress personnalisés.
- Le répertoire `mysql/` peut contenir des fichiers de configuration MySQL personnalisés.
- Le fichier `.env` contient les variables d'environnement utilisées dans le projet.

## Configuration

Assurez-vous de définir les variables d'environnement nécessaires dans le fichier `.env` avant de démarrer les conteneurs. Consultez le fichier `docker-compose.yml` pour connaître les variables d'environnement requises.

## Utilisation

1. Assurez-vous d'avoir Docker et Docker Compose installés sur votre système.
2. Clonez ce dépôt sur votre machine.
3. Définissez les variables d'environnement nécessaires dans le fichier `.env`.
4. Lancez les conteneurs avec la commande suivante :

```bash
docker-compose up -d
```

## Personnalisation

- Accédez à Wordpress dans votre navigateur à l'adresse http://localhost:8080.


    Vous pouvez personnaliser la configuration de Wordpress en modifiant les fichiers dans le répertoire wordpress/.
    Vous pouvez personnaliser la configuration de MySQL en modifiant les fichiers dans le répertoire mysql/.
