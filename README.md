# Image Duplicates Detector

Ce projet permet de détecter et de déplacer les images en doublon dans un répertoire donné. Le programme génère une empreinte (hash) pour chaque image et compare ces empreintes pour identifier les doublons.

## Fonctionnalités

- **Détection de doublons** : compare les images dans un dossier pour identifier les doublons.
- **Déplacement automatique** : déplace les doublons trouvés dans un dossier spécifié, `doublons`.

## Prérequis

- Python 3.x
- Bibliothèques Python nécessaires :
  - `PIL` (Pillow) pour manipuler les images
  - `os`, `shutil` pour la gestion des fichiers et des répertoires

## Installation

1. Clonez le dépôt ou téléchargez le fichier.
2. Installez les dépendances nécessaires avec la commande suivante :

    ```bash
    pip install Pillow
    ```

## Utilisation

1. Téléchargez ou clonez ce projet.
2. Modifiez la variable `folder_path` pour spécifier le répertoire contenant les images à analyser.
3. Lancez le script avec la commande suivante :

    ```bash
    python detect_duplicates.py
    ```

4. Les images en doublon seront déplacées dans un dossier `doublons`.

## Contribuer

Les contributions sont les bienvenues ! Si vous souhaitez améliorer ce projet, ouvrez une **pull request**. Assurez-vous de bien tester vos modifications avant de les soumettre.

## Licence

Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus de détails.
