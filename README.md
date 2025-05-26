##  CV Fullstack – Docker Setup

Ce projet regroupe trois composants indépendants, chacun dans son propre dépôt Git :

-  **Frontend** – Application Blazor/Web
-  **Backend** – API .NET
-  **Base de données** – PostgreSQL

Chaque composant peut être échangé ou mis à jour indépendamment. Le tout fonctionne via un `docker-compose`.

---

##  Structure du projet
```
/
├── CV-front/ ← Cloné depuis le dépôt front
├── CV-back/ ← Cloné depuis le dépôt back
├── CV-db/ ← Contient les scripts d'initialisation PostgreSQL
├── docker-compose.yml
└── README.md
```

---

##  Dépôts Git à utiliser

| Service    | Lien Git à cloner                           |
|------------|----------------------------------------------|
| Frontend   | `https://github.com/pyrofir/CV-front` |
| Backend    | `https://github.com/pyrofir/CV-back`  |
| Database   | `https://github.com/pyrofir/CV-db`    |


## Contact

Si vous avez des suggestions, remarques, ou que vous souhaitez echanger autour du projet, n'hesitez pas a me contacter :

**samuel.israel@sfr.fr**
