# Les jeux Olympiques

## Présentation de la base de données

On possède une base de données relatives aux jeux olympiques dont le schéma se résume à :

<center>
    <img src="./images/bdd.png" alt="image" width="1200" height="auto">
</center>

## Questions

### Requêtes simples

Avant de répondre aux questions suivantes, vous pouvez observer la table **PERSON** à l'aide de la requête suivante :

{{ sqlide titre="Table PERSON" base="./bdd/olympics.db" espace="olympiques" sql="sql/person.sql" }}

!!! question Requêtes simples

    1. Écrire la requête qui donne la taille du sportif **Rok Perko**.

        {{ sqlide titre="Réponse" espace="olympiques" }}

    2. Écrire la requête qui donne le nombre d'athlète Féminine plus grande que lui.

        {{ sqlide titre="Réponse" espace="olympiques" }}

    3. Quelle requête renvoie le nom de l'athlète Féminine la plus grande ?

        {{ sqlide titre="Réponse" espace="olympiques" }}

    4. Quelle requête renvoie les cinq plus lourds athlètes masculins ?

        {{ sqlide titre="Réponse" espace="olympiques" }}

    5. Quelle requête renvoie le poids moyen des hommes et des femmes ?

        {{ sqlide titre="Réponse" espace="olympiques" }}

### Premiers JOIN

Avant de répondre aux questions suivantes, vous pouvez observer la table **GAMES_COMPETITOR** à l'aide de la requête suivante :

{{ sqlide titre="Table GAMES_COMPETITOR" espace="olympiques" sql="sql/gc.sql" }}

!!! question Requêtes avec JOIN

    1. Quelle requête renvoie le nom de l'athlète le plus jeune ?

        {{ sqlide titre="Réponse" espace="olympiques" }}

    2. Quelle requête renvoie l'âge moyen des hommes et des femmes athlètes ?

        {{ sqlide titre="Réponse" espace="olympiques" }}

    3. Quelle requête renvoie le nombre de fois où **Erling Rudolf Aastad** a participé aux jeux olympiques ?

        {{ sqlide titre="Réponse" espace="olympiques" }}

    4. Quelle requête renvoie l'âge du plus vieil athlète des jeux olympiques de 2012 ?

        {{ sqlide titre="Réponse" espace="olympiques" }}

    5. À l'aide d'une sous-requête, quelle était la taille moyenne des athlètes Français ?

        {{ sqlide titre="Réponse" espace="olympiques" }}

### Requêtes HARDCORE

Afin de répondre aux questions suivantes, vous pouvez observer la table que vous souhaitez à l'aide de la requête suivante :

{{ sqlide titre="Visionneur de tables" espace="olympiques" sql="sql/all.sql" }}

!!! question Requêtes HARDCORE

    1. Quelle requête renvoie le nom des cinq plus grandes athlètes féminines au Badminton ?

        {{ sqlide titre="Réponse" espace="olympiques" }}

    2. Quelle requête renvoie le nombre de médaille d'or en Natation classé par pays durant les jeux de Paris ?

        {{ sqlide titre="Réponse" espace="olympiques" }}
