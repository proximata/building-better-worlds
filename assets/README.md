# Building Better Worlds – assets

Every image, logo and font used by the hackathon landing page, as standalone files.
The landing page (`../index.html`) keeps its own inlined copies, and the hall screen
(`../screen/`) keeps its own in `screen/assets/`, so changing a file here changes neither page.

| Folder | What is in it |
| --- | --- |
| `brand/` | Event wordmark in two layouts, favicon, touch icon, social preview image |
| `visuals/` | Backgrounds, illustrations, textures and ornaments from the page |
| `logos/organisers/`, `logos/sponsors/`, `logos/partners/` | Logos in the white versions used on the dark page |
| `icons/` | The three small interface icons |
| `fonts/` | Archivo Black and JetBrains Mono, Latin and Latin Extended subsets |
| `qr/` | QR codes for Discord onboarding and the proximata link page |

## Notes on single files

- `brand/wordmark-wide.svg` and `brand/wordmark-stacked.svg` are the flat wordmark in ice blue.
- `brand/wordmark-glass-wide.png` and `brand/wordmark-glass-stacked.png` are not on the page as files. They are stills of the animated "liquid glass" wordmark, rendered from the page's own effect onto a transparent background at double size. Like the rest of the identity they are made for dark backgrounds.
- `brand/og-image.jpg` is the social preview image the page links to on proximata.boldhack.at.
- `visuals/backdrop-shape.svg` is white here. The page shows it at 3.5% opacity.
- `visuals/hands.png` is 2880 px wide and meant to run edge to edge.
- `logos/sponsors/maritime-mark.png` and `logos/partners/hackathonhub-mark.png` are marks only. The page sets the names "maritime" and "Hackathonhub" next to them in JetBrains Mono, semibold.
- `visuals/grain.svg` and `visuals/noise.png` are tiling textures.
- `qr/` holds plain re-renders of the codes from the kickoff deck, with the same links.

## Colours and type

| Name | Value | Used for |
| --- | --- | --- |
| Ink | `#23201e` | Page background |
| Ice | `#c8f1ff` | Wordmark, ornaments, accents |
| Brand blue | `#202d85` | Buttons |
| Signal red | `#d82434` | Live marker, the Vienna pin on the globe |
| White at 60% | `rgba(255,255,255,.6)` | Secondary text |

Headlines are set in Archivo Black, everything else in JetBrains Mono.

## Credits and licences

- `visuals/athena.png` – Pallas Athene photo: Manfred Werner (Tsui), CC BY-SA 3.0, cropped, mirrored and recoloured.
  Source: https://commons.wikimedia.org/wiki/File:Pallas_Athene_Parlament_Wien_2015_nachts_a.jpg
  CC BY-SA requires this credit to travel with the image and adaptations of it to carry the same licence.
- `visuals/robonaut.png` – Robonaut 2 photo: NASA / Robert Markowitz.
  Source: https://commons.wikimedia.org/wiki/File:Robonaut_2.jpg
- `fonts/archivo-black-*.woff2` – Archivo Black, SIL Open Font License 1.1, Copyright 2017 The Archivo Black Project Authors (https://github.com/Omnibus-Type/ArchivoBlack).
- `fonts/jetbrains-mono-*.woff2` – JetBrains Mono, SIL Open Font License 1.1, Copyright 2020 The JetBrains Mono Project Authors (https://github.com/JetBrains/JetBrainsMono).
- Organiser, sponsor and partner logos belong to their owners and are here for use in connection with the event.
