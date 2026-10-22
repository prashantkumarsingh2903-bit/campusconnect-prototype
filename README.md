# CampusConnect · v3.1 prototype

A clickable prototype of **CampusConnect**, a club discovery and campus community app for IIT Guwahati students.

**Open it:** https://prashantkumarsingh2903-bit.github.io/campusconnect-prototype/

On a phone, open the link and use **Add to Home Screen** to launch it like an app.

**Android app:** download `CampusConnect-v3.1.apk` from the [v3.1 release](https://github.com/prashantkumarsingh2903-bit/campusconnect-prototype/releases/tag/v3.1) on your phone and open it. Android will ask you to allow installs from your browser, because the app isn't from the Play Store. The prototype is bundled inside, so it works offline and opens full screen. The app is built by GitHub Actions from the `android/` folder.

## What's new in v3.1

- **Welcome:** "Find your club at IITG", with a grid of club illustrations on warm charcoal. Sign-up starts with one "Get started" button.
- **Explore:** search is an icon in the top bar. The four boards fold open and closed, starting closed. Club cards show just the name. Events show this week and what's coming, with no status pills or "going" counts.
- **Event page:** reads like the club's announcement email: subject, from, when and where, the poster, a short message and Register. The same message goes to IITG Outlook, so clubs write it once.
- **Plans:** a month calendar opens on today. Tap a date to see its events, and set a reminder (1 hour before, the evening before, or the morning of).
- **Club pages:** one paragraph about the club, with Apply or Request to join beside the name, plus Instagram, an open WhatsApp group and email.
- **Rooms:** Trending now, With people you know and Open to everyone, each folding open and closed.
- **Interests:** each one has its own line icon.
- **Profile:** Edit beside your name, one Connections row and, for club members, "Your clubs" with Team space, Team chat, WhatsApp and Instagram.
- **Settings → Manage clubs** (club members): the team list and roles. The head adds people, changes roles and sets how many votes a change needs before it's published.
- **Composer:** a simpler "New post" screen that keeps drafts.

## What came in v3

- **Shorter onboarding:** a short splash (first launch only), one Welcome screen, then sign in → interests → Explore. No role picker or intro slides.
  - The code fills itself in, like a phone autofilling a code from a text message. You can still type it yourself.
  - If your email is on a club roster, you see **"You're on a club team"** and can open your team space.
- **Feed laid out like the Substack app:** a strip of clubs at the top, posts on full-width blocks, club updates as big image cards with a headline, and a "People you may know" row. A floating **+** opens a simple composer with a choice of Thought, Idea, Question or Looking for.
- **People:** connections only (no followers). Report, hide, mute and block from the "…" menus. **Privacy and safety** in Settings.
- **Events:** "Meera and 17 others going", filters for Today, This weekend and Next week, directions, and the deadline next to Register.
- **Rooms:** private rooms don't show who is inside until you're let in. Room cards show the place.
- **Club pages:** size and weekly time at the top, "Ask a question", and applying is a single screen.
- **Plans** (was "My plans"), a reminder prompt after your first registration, and Team space opens from Profile and the club page (4 tabs for everyone).
- **Easier to use:** tap targets of 44px, text of at least 12px, stronger contrast on avatars, and no club colours in buttons or progress bars.

## Trying it

- Sign in with any `@iitg.ac.in` email. The code fills itself in, or type any 6 digits.
- To try the club member path, use task 02 in the side panel or **Put next sign-in on a club roster**.
- The event check-in code is **4827**.
- On a computer, the side panel has test tasks, "play the organizer" buttons and links to every screen.

## Prototype limits

- All data is sample data held in the page. Nothing is saved to a server or sent anywhere.
- Codes, voice and video calls are simulated. The mic and camera are not used.
- Photos and videos you add to a post stay on your device and are gone when you reload.

Version history: [v1](https://github.com/prashantkumarsingh2903-bit/campusconnect-prototype/releases/tag/v1) · [v2](https://github.com/prashantkumarsingh2903-bit/campusconnect-prototype/releases/tag/v2) · [v3](https://github.com/prashantkumarsingh2903-bit/campusconnect-prototype/releases/tag/v3) · [v3.1](https://github.com/prashantkumarsingh2903-bit/campusconnect-prototype/releases/tag/v3.1)
