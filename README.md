# cassandra-101

**Cassandra 101** est un workshop permettant de découvrir la base de données NoSQL Cassandra et son écosystème, étape par étape.

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a>

## Introduction
**Cassandra** est une base de données NoSQL orientée colonnes. Cassandra a été déversée dans l'Open Source en 2008. Cassandra est une des bases les plus scalables actuellement disponibles sur le marché. C'est par ailleurs une des seules bases qui peut être installée sur une infrastructure multi-datacenters (i.e. connexions WAN). **Cassandra** propose des performances d'écriture très élevée et hautement disponible, un exemple souvent cité est celui d'Apple qui dispose d'un cluster de 75 000 noeuds.

En terme de CAP, **Cassandra** privilégie la disponibilité à la cohérence en cas de partitionnement. De fait, **Cassandra** propose de la cohérence à terme ([Eventual Consistency](https://en.wikipedia.org/wiki/Eventual_consistency)). Néanmoins, l'utilisateur peut choisir de privilégier la cohérence au dépend de la disponibilité. Cette option est paramétrable pour chaque requête.

### Use Cases
Quelques cas d'utilisation pour lesquels bases de données orientées colonnes, et en particulier Cassandra, sont adaptées :

* Time-series (notamment objets connectés)
* Référentiels, Catalogues
* Messaging
* Analyse des utilisateurs (traffic web, réseaux sociaux, recommandations)

## Étapes du workshop

* Étape 0 - [Installation](./instructions/step-0.md)
* Étape 1 - [Prise en main](./instructions/step-1.md)

## Liens utiles

* Site officiel : https://www.elastic.co
* Le site de Datastax : http://www.datastax.com/
* La documentation officielle : https://www.elastic.co/guide/en/elasticsearch/reference/current/index.html
