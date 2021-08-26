# ExpressJS user

Initialisation d'un projet ExpressJS/MongoDB comprenant une gestion basique d'utilisateur

### Base de donnée

- ```MongoDB```

### Initialisation

- ```npm install```
- ```npm run start```

### Fonctionalité

- ```Gestion des variable d'environement dans le fichier .env (dotenv)```
- ```Gestion de compte utilisateur basic (CRUD)```
- ```Vérification d'email (email de confirmation)```
- ```Swagger automatiser au lancement du serveur```
  
 MaJ du 26/08 :
```
  Gestion administrateur des utilisateur
    - Création de compte administrateur
    - Récupération de tout les utilisateur ou par ID ou recherché par nom/email
    - Modifier le login/mail ou role d'un utilisateur
    - Supprimer le compte d'un utilisateur
```

### Documentation

- ```server.js > routes > controllers > services > models```
- ```http://localhost:4200/api```

![Documentation Image](assets/swaggerView.png)
