# MRI-CIA Documents

![blend2png](https://img.shields.io/github/actions/workflow/status/MontpellierRessourcesImagerie/mri-cia-documents/build_blend.yml?logo=blender&label=blend2png)
![odt2pdf](https://img.shields.io/github/actions/workflow/status/MontpellierRessourcesImagerie/mri-cia-documents/build_odt.yml?logo=libreoffice&label=odt2png)

-------------------------

- This repository contains some documents related to the MRI-CIA service.
- It allows you to have a unique and constant link to the latest version of each document.
- Files can be "built" ('odt' to 'pdf', ...) from the GitHub actions of the repository.
- Files are "built" only when a new release is created and stored in the release's assets.

## Add a new document (for example, with an ODT)

- Add the '.odt' file into this repository.
- Add a workflow (`.github/workflows/`) to "build" your document (ex: convert your '.odt' to '.pdf') on release.
- The "built" document will be part of the release's assets when you make a new release.
- Build your document's URL using the example URLs from the *Current documents* section (below).

## Handled extensions

- `.odt` → `.pdf`
- `.blend` → `.png`

## Current documents

- [MRI-CIA project form](https://github.com/MontpellierRessourcesImagerie/mri-cia-documents/releases/latest/download/mri-cia-project-form.pdf)
- [The MRI-CIA service](https://github.com/MontpellierRessourcesImagerie/mri-cia-documents/releases/latest/download/the-mri-image-analysis-service.pdf)
- [Open-desk poster](https://github.com/MontpellierRessourcesImagerie/mri-cia-documents/releases/latest/download/open-desk-poster.png)
- [Flash-tuto poster](https://github.com/MontpellierRessourcesImagerie/mri-cia-documents/releases/latest/download/poster-flash-tuto.png)


