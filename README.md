# Liferay project

## Compilation et déploiement

1. Builder le service sur portlet des web services: (concerne les webservies)
    ```
    cd portlets/services-portlet;
    mvn liferay:build-service;
    mvn compile;
    mvn liferay:build-wsdd
    cd ../../;
    ```
2. Builder tous les plugins
    ```
    mvn clean install
    ```
3. Déployer les plugins (avec "mvn liferay:deploy" ou en copiant les war dans le dossier deploy) et démarrer le Liferay

## ext


## hooks


## layouttpl


## portlets


## themes

