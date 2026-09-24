# Design

BirthdayVisualiser uses a warm birthday-book visual language across its entry screen and analysis views. This replaces the earlier violet utility dashboard look.

## Intent

Contact exploration should feel calm and personal while remaining fast to scan. The landing screen previews a sample calendar beside the import action. Inside the app, clear navigation and restrained surfaces keep dates and names central.

## System

- Warm ivory page, paper-white surfaces, deep evergreen text and actions, terracotta accents.
- Outfit for display and Inter for controls and body text. The landing headline adds a restrained serif emphasis.
- Rounded 12–16px surfaces, fine borders, and soft depth only where a layer needs separation.
- Simple calendar geometry and a four-part brand mark connect the landing preview to the app.
- Dark mode uses deep green surfaces and light mint emphasis.
- Exploration views share a title, brief guidance, a live result count, and consistent cards or rows. Shared dates, upcoming birthdays, and missing details use clear badges and person-first links.
- Statistics separates overview, temporal patterns, and the contact cloud. Charts align to a responsive grid; the heatmap scrolls across years on narrow screens while keeping month labels legible.

## Interaction

- Mobile opens on Calendar after importing contacts; Timeline remains one tap away.
- Bottom navigation exposes the four main views and a More sheet for secondary views and settings.
- Touch controls are at least 40px high; search and count share a row on small screens.
- Chart.js loads when Statistics is first opened. Contact initials are generated locally when no photo is available.
- Keyboard focus is visible and reduced-motion settings shorten decorative motion.
- Timeline opens around the contacts' birth years and pairs the canvas with a roster of people in the visible range. The cloud offers a contact list alongside the visual display.
- The cloud animation settles after a short entrance and resumes only for interaction. Long contact lists defer off-screen photo loading.
- The contact book opens as a portrait-led card with a birthday countdown, age when known, quiet zodiac and group pills, and direct email or phone actions. Missing dates and years have explicit states; the dialog keeps keyboard focus inside and returns it on close.
- Settings uses the same paper and evergreen surfaces, with labeled appearance and birthday-detail choices. The selected option is pressed semantically, and report metadata sits in an optional disclosure with a readable local timestamp.
