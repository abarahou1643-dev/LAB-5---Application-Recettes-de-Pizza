

#  PizzaRecipes

Application Android de recettes de pizzas - Développée en Java

---

## Démarrage Rapide

### Installation

- Ouvrir avec **Android Studio**
- Synchroniser Gradle
- Exécuter sur émulateur/device API 24+

### Fonctionnalités
-  Splash Screen animé
-  Liste des pizzas avec images
-  Détails complets des recettes
-  Navigation fluide

---

##  Structure

```
app/src/main/java/com/example/pizzarecipes/
├── classes/Produit.java          # Modèle données
├── dao/IDao.java                 # Interface DAO  
├── service/ProduitService.java   # Gestion données
├── adapter/PizzaAdapter.java     # Adapteur liste
└── ui/                           # Activités
    ├── SplashActivity.java
    ├── ListPizzaActivity.java
    └── PizzaDetailActivity.java
```

---

##  Tech Stack

- **Langage** : Java
- **SDK Min** : Android 7.0 (API 24)
- **Architecture** : MVC
- **Patterns** : Singleton, DAO, Adapter

---

##  Données

10 pizzas incluses avec :
- Nom, prix, durée
- Ingrédients complets
- Étapes de préparation
- Images haute qualité

---

##  Ressources

### Google Drive
```
  PizzaRecipes_Resources/
├──  Documentation.pdf
├──  Maquettes_Figma/
├──  APK_Builds/
├──  Assets_Images/
└──  Database_Export/
```

**Lien Drive** : https://drive.google.com/file/d/1uTIuXltM1WHexD5OXK521in9RXd7Q_lm/view?usp=sharing

---

