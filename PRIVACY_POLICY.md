# NosoNotes — Privacy Policy

**Effective date:** 24 October 2026 (previous: 21 October 2026)
**Applies to:** the NosoNotes by Delfilical browser extension (Chrome / Edge), release v0.9.2 and the releases it supersedes (v0.9.1, v0.9.0, v0.8.0, v0.7.0, v0.6.2-beta). *v0.9.2 note: no change to data practices; still no network requests and nothing transmitted. The docked panel's position down the window is now remembered alongside its width, and the separate certificate import on the settings page is removed, so an imported certificate is no longer stored (any stored copy is deleted).* *v0.9.1 note: no change to data practices. A guidance pack may now carry a signing date and an expiry date set by the trust that made it; these are part of the pack file you load and are shown on screen, and nothing new is stored or transmitted.* *v0.9.0 note: no change to data practices — still no network requests and nothing transmitted. The release adds two locally stored preference items, described under Preferences below: a per-document count of how often you have opened a reference document online (used only to show you a one-time "consider downloading it" tip on your own screen) and whether you dismissed that tip. The counts never leave your browser.* *v0.8.0 note: no change to data practices — the release was user-interface only (search-term pills, result-view defaults). It stores strictly less than v0.7.0: result-band view choices are no longer saved between searches, and the extension suppresses the browser's own autofill dropdown on the site's search box (no data is read, written or transmitted by that change).*
**Developer contact:** Philip Taylor — Delfilical · pgt1980@outlook.com

## Summary

NosoNotes collects no data. Nothing you do in the extension is transmitted, uploaded, synced, or shared with the developer or any third party. Everything the extension stores stays on your computer, inside your own browser profile.

## What the extension stores, and where

NosoNotes is a reference search tool for clinical coders. It stores the following, all locally on your device:

**Personal coder notes.** Notes you write (title, text, associated codes, keywords) are stored in the browser's extension storage (`chrome.storage.local`) on your device. They are created by you, readable only by you, and never leave your browser. You can export them to a file, import them from a file, or delete them at any time from the extension's settings page.

**Reference PDFs.** Copies of the published coding standards documents that you load yourself are stored in the extension's local IndexedDB database on your device, so they reopen automatically. They are never uploaded anywhere. You can remove them at any time with the × button in the viewer.

**Local guidance packs.** If you load a trust's signed guidance pack, the pack (its coding guidance, including its licence certificate — public verification data only) is stored in the extension's local IndexedDB. Packs are loaded by you and never transmitted; you can remove them at any time from the settings page. The certificate contains no secret or identifying data — it is only the public material used to check, on your device, that a pack is genuinely your trust's.

**Reference documents (the guidance shelf, from v0.9.0).** If you load a signed shelf file indexing a published reference document, it is stored like a guidance pack. Attaching your own downloaded copy of such a document stores it like a reference PDF. Neither is transmitted anywhere.

**Preferences.** Display, search-layer and guidance-source settings are stored locally in extension storage and the page's local storage. From v0.9.0 this also includes the panel's width and whether it is open (from v0.9.2 also its position down the window), and your choice of panel or classic layout (the layout choice is mirrored into the page's local storage so it can be read before the extension draws). Also from v0.9.0: the NosoForge licence state, which is the name of the licensed trust and the certificate's expiry date, derived from a loaded signed pack (until v0.9.2 also from a trust certificate imported on the settings page; that import is removed in v0.9.2 and any stored copy deleted). Nothing about the licence is transmitted anywhere. One detail for completeness: the layout choice and the licensed trust's name are mirrored into the Classifications Browser page's own local storage (the layout so the panel can be drawn before the extension's storage is read), which means they are readable by that site's scripts in your browser, in the same way as anything else stored for that site. No other NosoNotes data is stored there. From v0.9.0 this includes, per reference document, a count of how many times you have opened it online and whether you dismissed the resulting "consider downloading a copy" tip — used only to decide whether to show you that tip, stored only on your device, and removable like any other stored data.

## What the extension does not do

- It does not collect, transmit, or share any personal information, health information, patient data, or staff data.
- It makes no network requests. The extension requests no host permissions and contains no code paths that send data to any server. There is no backend.
- It contains no analytics, telemetry, tracking, advertising, or crash reporting.
- It does not read pages other than the NHS Classifications Browser (classbrowser.nhs.uk), the only site it runs on.
- It does not use cookies and does not identify you in any way. The developer has no means of knowing who uses the extension or how.

## Data categories (store disclosure)

For the purposes of the Chrome Web Store and Microsoft Edge Add-ons privacy declarations: NosoNotes does not collect personally identifiable information, health information, financial information, authentication information, personal communications, location data, web history, user activity, or website content. All categories: **not collected**.

## Patient data

NosoNotes is a guidance reference tool only. It has no access to patient record systems and processes no patient data. If a coder chooses to type information into a personal note, that note exists only in their own browser; users should follow their organisation's information governance policies on what they record in notes.

## Your control

All data the extension stores is yours and is under your control: export or delete notes from the settings page, remove PDFs from the viewer, or remove the extension to delete its stored data entirely. Because the developer holds no copy of any of your data, there is nothing for the developer to access, correct, or erase on your behalf.

## Legal basis

Because NosoNotes collects and transmits no personal data, the developer does not act as a data controller or processor for any user data under UK GDPR. Data you store locally in your own browser remains within your (or your organisation's) control.

## Changes to this policy

If a future version of NosoNotes changes how data is handled (for example, optional shared note packs), this policy will be updated before that version is released, the version's changelog will say so, and the store listings will link to the updated policy.

## Contact

Questions about this policy or the extension: Philip Taylor — pgt1980@outlook.com
