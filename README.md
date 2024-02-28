# emplacement des fichiers

Le docher-compose de l'étape 2 du TP1 se trouve à la racine, le dockerfile de l'étape 3 du TP1 se trouve dans le git submodule TPDockerSampleApp (cliquez dessus depuis la racine du repo)

Le projet se trouve dans les repositories doodlestudent pour les fichiers de build et doodle-config pour les fichiers de configurations et de déployement

Pensez à fetch les submodules:

```sh
git clone --recurse-submodules -j3 https://github.com/quentinlegot/doodle-config.git
``` 
utilisez l'option `-j3` si vous voulez clone les 3 submodules en même temps, supprimez l'option si vous voulez faire 1 par 1

ou si vous avez déjà clone le projet:

```sh
git submodule update --init --recursive
```