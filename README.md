# *README – Documentation Projet 2603 Recepteur Joypad*

## 1. Objectif du projet

Réaliser un programme permettant de lire une manette de jeu 8bitdo (Joystick et boutons) avec un Raspberry pi pico W pour commander un robot. 
Le but est de pouvoir transmettre les valeurs lues (par la manette de jeu) à un uC via un UART 11520 bauds. La manette (bluetooth) devra support les vibrations pour fournir un feedback de la manette.
La trame UART devra être standardisé et documenté affin de pouvoir convertir les valeurs lues en valeur pour le uC réceptionneur.

_Pour plus d'informations, consulter le CDC dans le dossier du projet_

---

## 2. Environnement & Versionning

### Outils utilisés

* IDE : Arduiono IDE
* Compilateur : Intégré à l'IDE
* Librairies : Bluepad32 => (https://github.com/ricardoquesada/bluepad32)
* OS : Win 10 22H2
* Autres outils : Manette => 8bitdo Lite2, Xbox series X (Manette personnel), Logitec pebble (perso, test fonctionnement bluetooth)

### Versions

* Version du compilateur : 2.3.8
* Version des librairies : 1.3.5
* Version du projet : V1.0

---

## 3. Mise en place du projet

### Installation

1. Cloner le dépôt :

```bash
git clone <url_du_repo>
```

2. Accéder au dossier :

```bash
cd <nom_du_projet>
```

3. Compiler :

```bash
<commande_de_build>
```

---

### Déploiement

* Étapes de déploiement :
* Configuration spécifique :
* Matériel nécessaire (si applicable) :

---

## 4. Explication des fonctions implémentées

### Communication (Trames)

* Description du protocole utilisé
* Structure des trames :

  * Header
  * Données
  * Checksum
* Exemple de trame

---

### Calculs

* Algorithmes utilisés
* Formules importantes
* Optimisations éventuelles

---

### Gestion des données

* Structures de données utilisées
* Stockage (RAM, fichiers, EEPROM, etc.)
* Flux de données

---

## 5. Validation des fonctions implémentées

### Testing

* Méthodologie de test
* Cas de tests

#### Informations de debug

* Logs
* Messages d’erreur
* Outils utilisés (debugger, UART, etc.)

#### Signaux mesurés

* Types de signaux
* Outils de mesure (oscilloscope, analyseur logique, etc.)
* Résultats obtenus

---

## 6. Commentaires dans le code

* Convention de commentaire utilisée
* Organisation dans les fichiers `.c` et `.h`
* Bonnes pratiques appliquées

---

## 7. Modélisation du système

### Machine d’état

* Description des états
* Transitions

### Diagrammes

* Flow chart :
* Code d'example Bluepad32
  <img width="2189" height="1608" alt="mermaid-diagram-2026-04-29-093216" src="https://github.com/user-attachments/assets/d28e81b7-db20-437c-8e8f-e411d4e796b8" />

* Structogramme

### Pseudo-code

* Description simplifiée des algorithmes principaux

---

## 8. Bugs rencontrés

* Liste des bugs identifiés
* Cause
* Solution apportée
* Statut (corrigé / en cours)

---

## 9. Fiche de modification (Changelog)

| Version | Date    | Auteur | Description                   |
| ------- | ----    | ------ | -----------                   |
| v1.0    | XX.XX.26| TMK    |  Version originelle           |

---

## Annexes (optionnel)

* Schémas
* Datasheets
* Liens utiles

---
