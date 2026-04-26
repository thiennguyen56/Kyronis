# Firebase Deploy

1. Set your Firebase project id in `.firebaserc`:
   - Replace `your-firebase-project-id` with your real project id.
2. Login to Firebase:
   - `npm run firebase:login`
3. (Optional) Link/select project interactively:
   - `npm run firebase:use`
4. Deploy hosting:
   - `npm run deploy`
5. Connect custom domain in Firebase Console:
   - Hosting -> Add custom domain -> follow DNS instructions for `kyronis.cloud` or subdomain.
