PPC E-SPORTS Tournament Website
================================
Files:
- index.html  -> public tournament website
- admin.html  -> localStorage admin panel

Deploy:
1. Upload both files to the same Netlify/site domain.
2. Open admin.html.
3. Login password: piyush@123
4. Add your WhatsApp number, UPI ID, QR image URL, group/social links.
5. Create an event.
6. Users register from index.html.

Important:
- This is a frontend-only/localStorage build. Data is stored in each visitor's browser.
- Registrations made by users are NOT automatically synchronized to the admin's browser across different devices. For cross-device persistent registrations, a backend/database or hosted service is required.
- Uploaded screenshots are stored as Base64 in localStorage and can hit browser storage limits with many registrations.
- The UPI button uses a standard upi://pay intent. Actual app behavior depends on the user's phone/browser.
