# Direct Linker

Transforms public cloud links into direct links to files.

## Supported clouds

- Dropbox ([before](https://www.dropbox.com/scl/fi/lvd0d2ljm61sjfbgta7vw/diirect-linker-example-01.jpg?rlkey=xb3cfheiv5pmnd16kk73dbtas&st=rchblek3&dl=0) → [after](https://dl.dropboxusercontent.com/scl/fi/lvd0d2ljm61sjfbgta7vw/diirect-linker-example-01.jpg?rlkey=xb3cfheiv5pmnd16kk73dbtas))
- Google Drive ([before](https://drive.google.com/file/d/1ijGAbf2rpYILCoEs8X-MfIVFrFXY6kW6/view?usp=drive_link) → [after](https://drive.usercontent.google.com/download?id=1ijGAbf2rpYILCoEs8X-MfIVFrFXY6kW6&authuser=0))

## How to use

After `https://dl.xafiro.site/?link=`, paste a cloud link to your file and go to the resulting address.

### Example

[`https://dl.xafiro.site/?link=https://www.dropbox.com/scl/fi/lvd0d2ljm61sjfbgta7vw/diirect-linker-example-01.jpg?rlkey=xb3cfheiv5pmnd16kk73dbtas&st=rchblek3&dl=0`](https://dl.xafiro.site/?link=https://www.dropbox.com/scl/fi/lvd0d2ljm61sjfbgta7vw/diirect-linker-example-01.jpg?rlkey=xb3cfheiv5pmnd16kk73dbtas&st=rchblek3&dl=0)

## Explainer

The service was developed to serve as a shortcut in Google Chrome address bar:

<figure>
  <img src="https://dl.dropboxusercontent.com/scl/fi/n8lg12ylr8vn5im5gi19m/direct-linker-chrome.png?rlkey=vbibqkrw4gs46gv62vhth63y3" alt="Usage example." />
  <figcaption><i><code>chrome://settings/searchEngines</code></i></figcaption>
</figure>
