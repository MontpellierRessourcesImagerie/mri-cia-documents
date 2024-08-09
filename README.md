# MRI-CIA Documents

- The repository contains the documents relative to the MRI-CIA version.
- It allows to have a unique and constant link to the latest version of documents.
- Files can be "built" ('odt' to 'pdf', ...) from the GitHub actions of the repository.

## Add a new document, example with an ODT

- Add the '.odt' file into this repository.
- Modify the workflow (.github/workflows/on-release.yml) to "build" your document (ex: convert your '.odt' to '.pdf') on release.
- Make your modifications as you wish and push them.
- When you will make a new release, the PDF will be part of the assets.
- You can access the assets of your latest release with the URL: github.com/MontpellierRessourcesImagerie/mri-cia-documents/releases/latest/my-document.pdf


**Note:** The ODT to PDF conversion is already insured for any ODT document at the root of this repo, you don't need to edit the workflow.

## Access a document

You can access the latest version of the document simply with this URL, just change the name of the document:
`https://github.com/MontpellierRessourcesImagerie/mri-cia-documents/releases/latest/download/mri-cia-project-form.pdf`

