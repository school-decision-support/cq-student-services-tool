# CQ Student Services Tool — Concept v5.1

A browser-based prototype for the Central Queensland Student Services engagement workflow.

## Publish with GitHub Pages

1. Create a new **public** GitHub repository (for example, `cq-student-services-tool`).
2. Upload `index.html` to the repository's root (the top level, not a subfolder). This README is optional.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, branch **main**, folder **/(root)**, then **Save**.
5. Once published, open `https://YOUR-USERNAME.github.io/cq-student-services-tool/`.
6. To publish updates at the same URL, replace `index.html` on the `main` branch.

## Important information handling

**Demonstration only. Use dummy/de-identified information.** GitHub Pages on a public repository serves the app publicly; it is not an approved Queensland Department of Education case-management environment. The app currently uses browser `localStorage` for working state and allows JSON file exports. Local storage is specific to the browser/device and can be lost or cleared; it is not secure central case storage. Do not use identifiable student records, confidential referral notes or personal information without departmental ICT/privacy approval and a security assessment.

## Technical notes

- The entry point is `index.html`.
- The application is a single-file HTML/CSS/JavaScript prototype; no build process or server is required.
- Save a copy of the previous `index.html` before replacing it with an update.
- Test navigation, JSON save/reopen, exports, and the embedded Word template after each update.
- GitHub Pages publication can take several minutes.
