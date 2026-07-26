# NosoNotes by Delfilical — Terms of Use

## What this tool does

NosoNotes is a coding guidance search extension for the NHS Classifications Browser. It allows clinical coders to search a structured index of national coding standards (ICD-10 and OPCS-4), view the relevant page in their own copy of the standards PDF, and keep personal notes anchored to their coding context.

## What this tool does not do

NosoNotes does not provide clinical advice, diagnostic recommendations, or coding decisions. It is a reference tool that makes existing published guidance easier to find. The tool does not replace professional judgement, local policies, or any trust's established coding procedures.

## Content

NosoNotes distributes a coding guidance index containing entry titles, references, page locations, related codes, and search keywords. It does not distribute the text of the national standards themselves. The coder provides their own copy of the standards PDF.

**Coding guidance index:** The index is derived from the National Clinical Coding Standards published by NHS England. It contains structured metadata (titles, page numbers, codes, keywords) to support search and navigation. It does not reproduce the guidance text. Responsibility for the accuracy and currency of the underlying standards rests with NHS England.

**Personal coder notes:** Created, stored, and owned by the individual coder. Notes are held in the browser's local storage and never leave the coder's machine. NosoNotes provides the creation and search capability. The coder is solely responsible for the content of their own notes.

## Limitation of liability

NosoNotes is provided as-is, without warranty of any kind. The developer does not accept liability for coding decisions made using the tool, for errors or omissions in any guidance content, or for any consequences arising from the use of the tool or the content it makes searchable.

Clinical coders remain professionally responsible for their coding decisions. This tool is an aid to finding guidance, not a substitute for professional competence or local governance.

## Data and privacy

NosoNotes processes no patient data, no staff data, and no personally identifiable information. It is a reference search tool only.

The extension operates entirely within the user's browser. No data is uploaded, transmitted, or stored externally. Specifically:

- Coder notes are stored in `chrome.storage.local`, sandboxed to the extension and the user's browser profile.
- PDFs are stored in IndexedDB via the extension's background service worker.
- The extension has no host permissions and makes no network requests after the content scripts load.
- A strict Content Security Policy (`script-src 'self'; object-src 'none'`) is enforced on all extension pages.

## Attribution

NosoNotes by Delfilical, developed by Philip Taylor.

NosoNotes is an independent project. It is not produced, sponsored, or endorsed by NHS England or the Terminology and Classifications Delivery Service.

## Licence

NosoNotes is proprietary software. It is licensed free of charge for NHS clinical coding use. See the `LICENCE` file for full terms, including permitted use, restrictions, and conditions for NHS organisations.

## Changes

These terms may be updated from time to time. The current version is always available within the extension (settings page or extension folder).
