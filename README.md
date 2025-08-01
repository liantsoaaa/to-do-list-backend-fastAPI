# to-do-list-backend-fastAPI

## Description

Ce projet est une API backend pour une application de gestion de tâches, développée avec FastAPI. Elle permet de créer, lire, mettre à jour et supprimer des tâches.

## Déploiement

L'API est déployée sur Render et accessible à l'adresse suivante :  
[https://to-do-list-backend-fastapi.onrender.com](https://to-do-list-backend-fastapi.onrender.com)

## Fonctionnalités

- Ajouter une nouvelle tâche
- Récupérer la liste des tâches
- Modifier une tâche existante
- Supprimer une tâche

## Utilisation

Vous pouvez interagir avec l'API en envoyant des requêtes HTTP (GET, POST, PUT, DELETE) à l'aide de Postman ou de tout autre outil similaire, que ce soit en local ou via l'URL du projet déployé.

Pour vérifier que l'API fonctionne, envoyez une requête GET à `${URL}/health` ; la réponse sera un statut `OK`.

## Technologies

- Python
- FastAPI
- SQLite
- pydantic

## Démarrer localement

```bash
git clone https://github.com/liantsoaaa/to-do-list-backend-fastAPI.git
cd to-do-list-backend-fastAPI
pip install -r requirements.txt
uvicorn main:app --reload
```