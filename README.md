# Docker symfony #

Il s'agit d'une pile complète pour exécuter Symfony (dernière version: Flex) dans des conteneurs Docker à l'aide de l'outil docker-compose.

### Installation ###
Tout d'abord, clonez le dépôt. Ensuite, exécutez la commande suivante:
```console
$ docker-compose up -d --build
```

Pour voir les journaux des conteneurs, exécutez:
```console
$ docker-compose logs -f
```

Pour lister les conteneurs, exécutez:
```console
$ docker-compose ps
```

Pour utiliser la console de commande à l'intérieur du conteneur, exécutez:
```console
$ docker-compose exec <Nom du conteneur> sh
```

Pour arrêter les conteneurs, exécutez:
```console
$ docker-compose down
```

Tu peux visiter l'application Symfony sur l'URL suivante: 
> http://symfony.localhost

et accéder à Kibana sur:
> http://symfony.localhost:81

Remarque: tu peux reconstruire toutes les images Docker en exécutant:
```console
$ docker-compose build
```# symfony-docker-env
