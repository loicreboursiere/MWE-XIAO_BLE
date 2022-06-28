# MWE-XIAO_BLE

Premier test avec le microcontrolleur XIAO BLE et le XIA BLE expansion board.


<!-- TABLE DES MATIÈRES -->
<details open="open">
  <summary><h2 style="display: inline-block">Table des matières</h2></summary>
  <ol>
    <li><a href="#installation">Installation</a></li>
    <li><a href="#utilisation-du-dépôt">Utilisation du dépôt</a></li>
      <ul>
        <li><a href="#cloner">Cloner</a></li>
        <li><a href="#ajouter">Ajouter</a></li>
        <li><a href="#mettre-à-jour">Mettre à jour</a></li>
      </ul>
    <li><a href="#contribution">Contribution</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#remerciements">Remerciements</a></li>
  </ol>
</details>



## Installation

Dans l'IDE Arduino, aller dans `Preferences³Additional boards manager URLs` et ajouter l'URL suivante : `https://files.seedstudio.com/arduino/package_seeduino_boards_index.json`


### Troubleshooting
Compilation error: exec: "adafruit-nrfutil": executable file not found in $PATH : `pip3 install --user adafruit-nrfutil`

## Utilisation du dépôt

### Cloner

Deux options : 
* Soit vous êtes intéressés par tous le dépôts :
```
git clone --recurse-submodules https://Your/repository
```
* Soit seulement quelques modules vous intéressent pour commencer : 
```
git clone
cd MWE-XIAO_BLE/
git submodule update --init /path/to/submodule
```


### Ajouter

Deux options : 
* Soit cloner le dépôt, ajouter le submodule, commit et push
```
git clone https://github.com/loicreboursiere/MWE-embedded.git
git submodule add http://your.git.repo.adress
git commit -m "Addition of module git submodule add http://your.git.repo.adress"
git push -u origin main
```


* Une méthode moins orthodoxe, mais qui fonctionne : créer une nouvelle issue demandant à la personne qui maintient le dépôt général d'ajouter (ou de mettre à jour) un dépôt particulier. Cett issue devra contenir le texte et le lien à ajouter dans le README du dépôt global.

### Mettre à jour
* Soit vous avez une copie locale du dépôt et vous travaillez à partir de celle-ci, soit vous créez une nouvelle issue

```
cd existing/module
git fetch
git merge
cd ..
git add * (si rien d'autres n'attend d'être committé)
git commit -m "Update of existing/module"
git push -u origin main
```

## Contribution

## License

## Contact

## Remerciements
