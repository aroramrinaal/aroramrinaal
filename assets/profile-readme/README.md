# Profile README assets

| Folder | Contents |
| --- | --- |
| [navigation](navigation/) | Header locations, navigation labels and social links |
| [biography](biography/) | Biography illustrations, company logos and project nameplates |
| [projects](projects/) | Project icons, page headings, link labels and the project deck |
| [news](news/) | News dates, headings and event artwork |
| [research-notice](research-notice/) | Research invitation pieces for each responsive layout |
| [layout](layout/) | Divider and transparent spacing image |
| [footer](footer/) | Last-updated date stamper, one drawing per layout |

Filenames keep their descriptive artwork name and content hash so GitHub refreshes
cached images when the artwork changes. Animation and poster files share the same
name and hash; a `-still.svg` is a vector poster. Unhashed SVGs are drawing masters.

[`manifest.json`](manifest.json) lists each generated image and its poster using
paths relative to this directory. Artwork can be shared across several pages.
