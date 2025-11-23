🌱 Ecosystem
Un jeu en C++ simulant un écosystème dynamique avec des entités vivantes, de la nourriture, et des interactions visuelles.

🎮 Présentation
Ecosystem est un projet personnel développé en C++ qui modélise un environnement vivant.
 Chaque entité évolue dans un monde 2D, interagit avec la nourriture, et est rendue graphiquement via une architecture modulaire. 
 Ce projet met en œuvre des concepts de programmation orientée objet, de rendu graphique, et de simulation comportementale.

📁 Structure du projet
ecosystem/
│
├── include/                 # Fichiers d'en-tête (.h)
│   ├── Core/
│   │   ├── Structs.h        # Structures de base : Vector2D, Color, Food
│   │   ├── Entity.h         # Définition des entités vivantes
│   │   └── Ecosystem.h      # Logique globale de l'écosystème
│   └── Graphics/
│       ├── Window.h         # Gestion de la fenêtre
│       └── Renderer.h       # Rendu graphique
│
├── src/                     # Fichiers source (.cpp)
│   ├── Core/
│   │   ├── Entity.cpp
│   │   └── Ecosystem.cpp
│   └── Graphics/
│       ├── Window.cpp
│       └── Renderer.cpp
│   └── main.cpp             # Point d'entrée du jeu
│
├── assets/                  # Textures a venir

🚀 Fonctionnalités
- 🧠 Simulation intelligente : les entités se déplacent, consomment de la nourriture et interagissent.
- 🎨 Rendu graphique : affichage en temps réel avec gestion des couleurs et des positions.
- 🧩 Architecture modulaire : séparation claire entre logique, structures et rendu.
- ⚙️ Extensible : facile à enrichir avec de nouveaux comportements ou types d'entités.

🛠️ Technologies utilisées
- Langage : C++
- Bibliothèques : SDL3
- Paradigme : Programmation orientée objet
- Compilation : Clang++ avec C++17

📦 Compilation et exécution
- Clone le dépôt :
git clone https://github.com/ton-utilisateur/ecosystem.git
cd ecosystem
- Compile le projet :
clang++ -std=c++17 -Iinclude -o ecosystem src/*.cpp src/Core/*.cpp src/Graphics/*.cpp -lSDL3
- Lance le simulateur :
./ecosystem

🧪 À venir
- Ajout de comportements évolutifs (reproduction, mort, etc.)
- Système de score ou de statistiques
- Interface utilisateur plus riche
- Sauvegarde/chargement de l'état du monde

📜 Licence
Ce projet est sous licence MIT — libre à toi de l'utiliser, le modifier et le partager.





