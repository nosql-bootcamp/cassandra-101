# Installation
Nous allons maintenant installer Cassandra.

## Java

Cassandra étant basée sur le langage Java, veillez à disposer au minimum de **Java 8** installé sur votre machine. Vous pouvez vérifier l'installation de Java à l'aide de la commande `java -version`.

## Python

Le shell de Cassandra `cqlsh` qui permet de requêter Cassandra depuis un terminal est basé sur **Python**. Vous devez donc disposer de la version 2.7 (minimum) pour pouvoir suivre ce workshop.

Vous pouvez vérifier l'installation de **Python** à l'aide de la commande `python --version`.

Si souhaitez vous passer de **Python**, vous pouvez installer Datastax DevCenter, pour votre OS préféré, disponible via le lien suivant : https://academy.datastax.com/downloads/download-previous-versions#dl-devcenter

## Cassandra

Téléchargez la dernière version de **Cassandra** à l'adresse suivante : http://cassandra.apache.org/download/. **Privilégiez la version `tar.gz`.**

Ce workshop est basé sur la version `3.11.3`.

Pour installer Cassandra, dézippez l'archive dans le dossier de votre choix, par exemple `~/progs/apache-cassandra-3.11.3`.

Pour démarrer Cassandra, lancez la commande suivante dans un terminal :

```
bin/cassandra -f
```

Dans un second terminal, vous pouvez ouvrir le shell, lancez la commande suivante :

```
bin/cqlsh
```

Dans le shell **Cassandra** vous pouvez taper la commande suivante qui liste les schémas disponibles :

```
DESCRIBE keyspaces;
```

## Next

Vous pouvez passer à l'étape suivante : * Étape 1 - [Prise en main](./step-1.md)
