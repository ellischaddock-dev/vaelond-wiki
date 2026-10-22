# Image asset verification — 20 October 2026

**Method:** matched all image embeds in the uploaded `vaelond-wiki-reference(7).md` against the **49-line** supplied `image-files-relative.txt` inventory by asset basename. This checks **inventory coverage only**; it cannot prove a file does or does not exist in the live local `_Assets` folder, because the actual images were not provided for this audit.

| Image referenced in wiki | Referencing page | Inventory match | Verified on disk? |
|---|---|---|---|
| `Broken Fang Camp Sketch - Malt.png` | `06 Library/Letters and Documents/Broken Fang Camp Sketches.md` | **No** | **Not possible from supplied file list** |
| `Broken Fang Camp Sketch - Salla.png` | `06 Library/Letters and Documents/Broken Fang Camp Sketches.md` | **No** | **Not possible from supplied file list** |
| `Image1.png` | `06 Library/Ardynian Relics and Artefacts/Tace Nox scroll.md` | **No** | **Not possible from supplied file list** |
| `Image2.png` | `06 Library/Ardynian Relics and Artefacts/Tace Nox scroll.md` | **No** | **Not possible from supplied file list** |
| `Image3.png` | `06 Library/Ardynian Relics and Artefacts/Tace Nox scroll.md` | **No** | **Not possible from supplied file list** |
| `Image4.png` | `06 Library/Ardynian Relics and Artefacts/Tace Nox scroll.md` | **No** | **Not possible from supplied file list** |
| `Image5.png` | `06 Library/Ardynian Relics and Artefacts/Tace Nox scroll.md` | **No** | **Not possible from supplied file list** |

## Findings and recommended action

- **Seven distinct missing-from-inventory names:** the five numbered `Image1.png`–`Image5.png` embeds on the Tace Nox scroll page, and the two `Broken Fang Camp Sketch` images on the sketch document page.
- No image files have been fabricated, replaced or removed. The wiki embeds remain unchanged, since an asset not appearing on an **older listing** may still exist locally.
- Run a fresh recursive image-file inventory in `content/_Assets`, then compare again. If these files are not present, add the real images or update the embeds to actual filenames. Consider descriptive names for `Image1.png`–`Image5.png` once the corresponding files are located.
