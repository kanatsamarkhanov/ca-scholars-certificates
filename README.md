# CA Scholars — verification site

1. Create a public repository named ca-scholars-certificates.
2. Upload index.html, certificates.json and .nojekyll to its root.
3. Settings > Pages > Deploy from a branch > main > / (root) > Save.
4. Open the site address shown by GitHub Pages.
5. Test ?id=DEMO-001. This is a demo, not a real certificate.

certificates.json is a PUBLIC registry. Publish names only with appropriate permission. Do not upload private CSV files, patronymics, contact data or PDF certificates by default.

Records are keyed by unique certificate number. Supported statuses: valid, revoked, demo. Missing/unknown status is not treated as valid. Maintain the existing records when adding a new batch; keep a separate backup. Remove DEMO-001 after testing. An empty registry is {}.

The QR must point to the deployed site with ?id=CERTIFICATE_NUMBER. It is a lookup, not a cryptographic signature. Compare the record with the document.
