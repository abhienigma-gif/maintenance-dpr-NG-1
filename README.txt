FINAL VERSION — MAINTENANCE SHORT DPR iPHONE OFFLINE PWA

Features:
- New DPR
- Automatic DPR number
- Multiple DPRs stored offline in IndexedDB
- DPR History
- Open/Edit/Delete saved DPRs
- RUN / S/B / U/M mutually exclusive equipment status
- POL accepts text + numbers
- Grease accepts text + numbers
- Full DPR text sharing
- Word-compatible .doc export
- PDF creation through iPhone print preview
- PDF can be shared to WhatsApp using the iPhone Share sheet

PDF → WhatsApp workflow on iPhone:
1. Open Export.
2. Tap "Create PDF → Share to WhatsApp".
3. iPhone opens Print preview.
4. Pinch-out on the preview to open the PDF.
5. Tap Share.
6. Select WhatsApp.
7. Select the required person/group and send.

Deployment:
Replace index.html and service-worker.js in the same GitHub Pages repository and commit.
No new repository is required.

Important:
The PWA works offline after it has been opened online once and cached.
For production use with confidential operational information, host it on an organization-controlled/private HTTPS domain rather than a public GitHub Pages repository.
