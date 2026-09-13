FIXED iPHONE OFFLINE DPR

Fixes in this version:
1. Save DPR now serializes the complete form, including dynamically added maintenance, generic-job and inventory cards.
2. Save is immediately verified after writing to localStorage.
3. Autosave runs after changes.
4. Share DPR now shares the COMPLETE DPR text, not only the first three lines.
5. Equipment status is now four mutually-exclusive choices:
   RUN | S/B | U/M
   U/M is one combined status button, not separate U and M buttons.
6. Existing saved data can be restored when the app is reopened.

Important for iPhone:
- Use normal Safari, not Private Browsing.
- Install/open the PWA from its HTTPS address.
- Open it once online so the service worker is cached.
- Then it can be used offline.
