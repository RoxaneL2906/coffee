# Coffee

Maquette Coffee

## Programme
Fondamentaux - HTML & CSS

## Prérequis
- Git (pour cloner le dépôt)
- Docker (pour la version conteneurisée)
- Un navigateur moderne

## Installation & Configuration

### En local
Cloner le projet
Ouvrir directement `index.html` dans votre navigateur.

### Avec Docker
```bash
docker build -t coffee-app .
docker run -p 8082:80 --name coffee-app coffee-app
```
Ouvrir http://localhost:8082

## Port
| Hôte | Conteneur |
|------|-----------|
| 8082 | 80        |