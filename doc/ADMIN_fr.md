D'autres dossiers de musique peuvent être ajoutés dans le fichier d'environnement `__INSTALL_DIR__/.env`
Ex :
```
GONIC_MUSIC_PATH=__DATA_DIR__/music,/home/yunohost.multimedia/<user>/Music/,/home/yunohost.multimedia/share/Music/,/path/to/albums,/path/to/compilations  
# les dossiers doivent être séparés par des virgules
```
ou :
```
GONIC_MUSIC_PATH=__DATA_DIR__/music,my albums->/path/to/albums,my compilations->/path/to/compilations 
# les dossiers doivent être séparés par des virgules
```
Le serveur doit ensuite être redémarré pour prendre les changements en compte : `sudo systemctl restart gonic`