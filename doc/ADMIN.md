Other music folders can be added via the environment file  `__INSTALL_DIR__/.env`.
E.g. :
```
GONIC_MUSIC_PATH=__DATA_DIR__/music,/home/yunohost.multimedia/<user>/Music/,/home/yunohost.multimedia/share/Music/,/path/to/albums,/path/to/compilations  
# add comma separated folders
```
or
```
GONIC_MUSIC_PATH=__DATA_DIR__/music,my albums->/path/to/albums,my compilations->/path/to/compilations 
# add comma separated folders
```
Then restart the gonic server running `sudo systemctl restart gonic`