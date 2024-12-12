# Direct Linker

Transforms public cloud links into direct links to files.

## Supported services

### Dropbox

Link examples:

- **Before:** [`https://www.dropbox.com/scl/fi/lvd0d2ljm61sjfbgta7vw/diirect-linker-example-01.jpg?rlkey=xb3cfheiv5pmnd16kk73dbtas&st=rchblek3&dl=0`](https://www.dropbox.com/scl/fi/lvd0d2ljm61sjfbgta7vw/diirect-linker-example-01.jpg?rlkey=xb3cfheiv5pmnd16kk73dbtas&st=rchblek3&dl=0)

	**After:** [`https://dl.dropboxusercontent.com/scl/fi/lvd0d2ljm61sjfbgta7vw/diirect-linker-example-01.jpg?rlkey=xb3cfheiv5pmnd16kk73dbtas`](https://dl.dropboxusercontent.com/scl/fi/lvd0d2ljm61sjfbgta7vw/diirect-linker-example-01.jpg?rlkey=xb3cfheiv5pmnd16kk73dbtas)

### Google Drive

Link examples:

- **Before:** [`https://drive.google.com/file/d/1ijGAbf2rpYILCoEs8X-MfIVFrFXY6kW6/view?usp=drive_link`](https://drive.google.com/file/d/1ijGAbf2rpYILCoEs8X-MfIVFrFXY6kW6/view?usp=drive_link)

	**After:** [`https://drive.usercontent.google.com/download?id=1ijGAbf2rpYILCoEs8X-MfIVFrFXY6kW6&authuser=0`](https://drive.usercontent.google.com/download?id=1ijGAbf2rpYILCoEs8X-MfIVFrFXY6kW6&authuser=0)

## How to use

After `https://dl.xafiro.site/?link=`, insert a link to your file and navigate to the resulting address.

For example, [`https://dl.xafiro.site/?link=https://www.dropbox.com/scl/fi/lvd0d2ljm61sjfbgta7vw/diirect-linker-example-01.jpg?rlkey=xb3cfheiv5pmnd16kk73dbtas&st=rchblek3&dl=0`](https://dl.xafiro.site/?link=https://www.dropbox.com/scl/fi/lvd0d2ljm61sjfbgta7vw/diirect-linker-example-01.jpg?rlkey=xb3cfheiv5pmnd16kk73dbtas&st=rchblek3&dl=0).

The service was created to be used as a shortcut in Google Chrome address bar:

![](https://dl.dropboxusercontent.com/scl/fi/n8lg12ylr8vn5im5gi19m/direct-linker-chrome.png?rlkey=vbibqkrw4gs46gv62vhth63y3)<br>
*`chrome://settings/searchEngines`*
