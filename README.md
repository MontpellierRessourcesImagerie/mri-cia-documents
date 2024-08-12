# MRI-CIA Documents

- This repository contains the documents related to the MRI-CIA service.
- It allows you to have a unique and constant link to the latest version of each document.
- Files can be "built" ('odt' to 'pdf', ...) from the GitHub actions of the repository.
- Files are "built" only when a new release is created and stored in the release's assets.

## Add a new document (for example, with an ODT)

- Add the '.odt' file into this repository.
- Modify the workflow (.github/workflows/on-release.yml) to "build" your document (ex: convert your '.odt' to '.pdf') on release.
- Make your modifications as you wish and push them.
- When you will make a new release, the PDF will be part of the assets.
- Build your document's URL as described in the next session.

## Handled extensions

- `.odt`
- `.blend`

## Access a document

You can access the latest version of the document simply with this URL; you simply need to change the name at the end:
`https://github.com/MontpellierRessourcesImagerie/mri-cia-documents/releases/latest/download/{NAME_OF_THE_DOCUMENT}`

## Current documents:

- [MRI-CIA project form](https://github.com/MontpellierRessourcesImagerie/mri-cia-documents/releases/latest/download/mri-cia-project-form.pdf)
- [The MRI-CIA service](https://github.com/MontpellierRessourcesImagerie/mri-cia-documents/releases/latest/download/the-mri-image-analysis-service.pdf)
- [Open-desk poster](https://github.com/MontpellierRessourcesImagerie/mri-cia-documents/releases/latest/download/open-desk-poster.png)
- [Flash-tuto posters](https://github.com/MontpellierRessourcesImagerie/mri-cia-documents/releases/latest/download/poster-flash-tuto.png)


