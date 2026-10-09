# StayExplorer

Expo + React Native + TypeScript demonstration of a multi-screen travel accommodation app, inspired by the general navigation patterns of Airbnb. This is an independent educational mockup, not an Airbnb product.

## Run

1. Install Node.js (LTS).
2. Run `npm install`.
3. Run `npx expo install --fix` to align package versions with your Expo SDK.
4. Run `npx expo start` and scan the QR code with Expo Go.

## Screens and functionality

- Explore: searchable list of stays.
- Details: stack navigation with route parameters, amenities, demo reservation.
- Wishlist: favorite toggle and filtered list.
- Bookings: mock reservation list.
- Profile: mock profile and dark-mode toggle.

## Code organization

- `App.tsx`: typed navigation, screens, state provider, and reusable StayCard.
- `src/data.ts`: typed data model and sample content.

## Notes

- No backend, payments, or authentication.
- Favorites and demo reservations are in-memory and reset when the app restarts.
- Sample photos are remote Unsplash images and require internet access.
- Reference screenshots from the actual chosen app must be captured and included separately by the student for submission. Do not claim exact 80% visual fidelity without comparing the reference screenshots.
- Test on iOS and Android before submitting.
