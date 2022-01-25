# PlayV Avatar Generator #

from [Multiavatar](https://multiavatar.com) is a multicultural avatar maker:
### Info ###

The initial unique 48 (16x3) avatar characters are designed to work as the source from which all 12 billion avatars are generated.

### API ###

To get an avatar as SVG code, add the avatar's ID to the URL:

```
https://api.multiavatar.com/Binx Bond
```
JavaScript API call example to get SVG code:

```
let avatarId = 'Binx Bond'
fetch('https://api.multiavatar.com/'
+JSON.stringify(avatarId))
  .then(res => res.text())
  .then(svg => console.log(svg))
```
To get an avatar as SVG file, add .svg to the end of the URL:

```
https://api.multiavatar.com/Binx Bond.svg
```
To get an avatar as PNG file, add .png to the end of the URL:

```
https://api.multiavatar.com/Binx Bond.png
```

### License ###

You can use Multiavatar for free, as long as the conditions described in the [LICENSE](LICENSE) are followed.

### Screenshots ###

<img src="https://github.com/bclabs-volta/playv-avatar-generator/blob/main/Avatars00.png?raw=true">
