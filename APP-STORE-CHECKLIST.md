# App-store legal checklist

## Before going live
- [ ] Replace all placeholders in the website.
- [ ] Put the privacy-policy link inside the app as well as in both store listings.
- [ ] Implement account deletion inside the iOS app.
- [ ] Provide a web account-deletion route for Google Play requirements.
- [ ] Confirm deleting an account also deletes corresponding Supabase records and revokes Apple/Google sign-in links where applicable.
- [ ] Add a separate Restore Purchases control.
- [ ] Confirm subscription cancellation instructions.
- [ ] Confirm RevenueCat products match App Store Connect and Google Play product IDs.
- [ ] Confirm the Apple Privacy Nutrition Label matches actual SDK behaviour.
- [ ] Confirm the Google Play Data Safety form matches actual SDK behaviour.
- [ ] Audit Firebase Analytics/Crashlytics collection and retention.
- [ ] Audit every Rork-connected service and data destination.
- [ ] Avoid collecting allergy/health details unless genuinely required; configure access controls carefully.
- [ ] Add company number and registered office to the website.
- [ ] Consider registering with the ICO and paying the data-protection fee if required.
- [ ] Keep dated copies of every published policy version.
