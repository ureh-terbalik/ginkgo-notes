## Ginkgo Notes

- A single page note taking application
- Made mostly with AI (95% of all code) https://chat.z.ai
- Use localStorage. Limited to 5mb data (depend on browser).
- Easy to self-hosted (you don't even need a server, just open index.html with a browser)
- Can export (download) and import (upload) backup in a compressed (gzip) json file
- Persistent light/dark mode
- Use [Ace Editor](https://ace.c9.io)
- Highly configurable via source-code :)

It have two panel, left for item explorer (user can create file and folder) and right panel for item preview. The preview support following format (recognized by file extension):

- Markdown
- CSV
- CSVC (it's a csv file with vertical table preview)
- HTML without any sanitization
- Hybrid Text, it's a text file that can embed image/sound/video in base64 format, there's a button in editor for inserting media (consider localStorage limitation)
- Any other file will be treated as hybrid text file

