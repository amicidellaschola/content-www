# LaSchola

> Website [laschola.it](https://laschola.it)

## Colors

- **body background**: `#FDF4E6`
- **green**: `#8DC4B9`,  `#638986`,  `#478E88`,  `#408079`;
- **red**: `#E37679`,  `#CA8D91`,  `#80595B`,  `#BF6065`;
- **lilla**: `#C6B6E3`,  `#86829F`,  `#676287`,  `#4D4580`;
- **orange**: `#FBB069`,  `#B08549`,  `#CCB28F`,  `#BF9760`;
- **lightblue**: `#AAC2C9`,  `#77898D`,  `#488591`,  `#407680`;
- **pink**: `#EBB7BB`,  `#A48085`,  `#C68B93`,  `#80595F`;

## Image sizes

Original / source images formats

- **Photos and images** (`*.jpg`)
  - Dimensione file in pixel: `1440x810`
  - proporzione *16:9*
- **Cover** (`cover.jpg`)
  - Dimensione file in pixel: `1920x576` (300 dpi)
  - proporzione *10:3*
- **FB banner** (`ogimage.jpg`)
  - Dimensione file in pixel: `1200x628` (300 dpi)
  - proporzione *16:9*

## How to

### Extract an image from a video

where `ss` stands for the seconds at which grab the frame ([source](https://askubuntu.com/a/997328))

```bash
ffmpeg -ss 55 -i video.mp4  -t 1 -f image2 -qscale 0 img.jpg
```

## Misc

- Instagram widget feed with embedsocial.com, code:

```html
<div class='embedsocial-instagram' data-ref="c474c189fa07b229c1599a44edf274a3fd5bc6a2"></div><script>(function(d, s, id){var js; if (d.getElementById(id)) {return;} js = d.createElement(s); js.id = id; js.src = "https://embedsocial.com/embedscript/in.js"; d.getElementsByTagName("head")[0].appendChild(js);}(document, "script", "EmbedSocialInstagramScript"));</script>
```
