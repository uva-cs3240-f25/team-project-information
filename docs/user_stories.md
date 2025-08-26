# User Stories

# Base User Stories — Sustainability at UVA (CS 3240)

_Format: “As a [role], I should be able to [do something] because [reason].”_

## 1) Authentication & Accounts (Google Sign-In)
- As a student, I should be able to sign up and sign in with my **UVA Google account** because it simplifies access and verifies my affiliation.
- As a student, I should be able to **sign out** because I want to keep my account secure on shared devices.
- As a returning user, I should be **automatically recognized** after Google sign-in because I don’t want to create a new profile every time.
- As a user, I should be able to **delete my account** because I want control over my data.

## 2) Profiles & Media (Amazon S3)
- As a student, I should be able to **edit my profile** (name, short bio, sustainability interests) because teammates and peers need to know who I am.
- As a student, I should be able to **upload a profile image to S3** because visuals help others recognize me.
- As a student, I should be able to **attach images (proof, flyers, etc.) to posts/challenges stored in S3** because evidence and visuals make activities credible and engaging.
- As a privacy-minded user, I should be able to **control who can see my uploaded images** because not all content should be public.

## 3) In-App Messaging
- As a student, I should be able to **send a direct message** to another user because I may need to coordinate meetups or ask questions.
- As a student, I should be able to **receive message notifications** in-app because I don’t want to miss important replies.
- As a student, I should be able to **create a group conversation** because sustainability efforts often involve small teams.
- As a user, I should be able to **report or block abusive messages** because I want a safe, respectful environment.

## 4) Discoverability & Onboarding
- As a new user, I should be guided through a **first-time setup** (pick interests, review norms) because it helps me find relevant activities quickly.
- As a student, I should be able to **search for people, groups, events, and challenges** because I want to discover ways to participate.
- As a student, I should be able to **filter by topic** (e.g., food waste, transit, energy) because I want content aligned with my interests.

## 5) Core Sustainability Activities (Domain-Agnostic)
- As a student, I should be able to **create a sustainability activity** (event, challenge, initiative) because I want to mobilize the community.
- As a student, I should be able to **join or RSVP** to an activity because I want to coordinate participation.
- As a participant, I should be able to **log an action** (e.g., reused container, biked to class) because tracking progress motivates me.
- As a participant, I should be able to **attach photo proof to S3** when logging actions because verification builds trust.
- As a student, I should be able to **see impact metrics** (my streaks, team totals, CO₂ estimate) because feedback keeps me engaged.
- As a student, I should be able to **like or comment** on activities because social feedback fosters community.

## 6) Gamification & Recognition (Optional but Encouraged)
- As a participant, I should be able to **earn points/badges** for sustainable actions because recognition motivates continued behavior.
- As a student, I should be able to **view leaderboards** (personal, team, dorm) because friendly competition boosts participation.
- As a student, I should be able to **opt out of public leaderboards** because I value privacy.

## 7) Administration & Moderation
- As a moderator, I should be able to **review flagged content/messages** because I need to keep the space safe and relevant.
- As a moderator, I should be able to **edit or remove inappropriate content** because community standards must be enforced.
- As a moderator, I should be able to **suspend or reinstate users** because repeated violations require action.

## 8) Notifications
- As a participant, I should be able to **receive in-app notifications** for messages, event updates, and mentions because I want to stay current.
- As a user, I should be able to **configure notification preferences** because I don’t want alert overload.

## 9) Accessibility & Usability
- As a mobile user, I should be able to **use the app comfortably on my phone** because I’m often on the go.
- As a keyboard/screen-reader user, I should be able to **navigate all features accessibly** because inclusive design matters.

## 10) Data Stewardship & Consent
- As a user, I should be able to **view what personal data is stored** (profile, actions, images) because transparency builds trust.
- As a user, I should be able to **export my personal data** because I may want a copy for my records.
- As a user, I should be able to **opt in/out of analytics** because I want control over data use.

## 11) Course-Support Stories (for Teaching Context)
- As an instructor/TA, I should be able to **see team deployments and CI status** because I need to verify that required features are working.
- As an instructor/TA, I should be able to **access a demo account** because I need to evaluate functionality without disrupting student data.
- As an instructor/TA, I should be able to **view a basic audit log** (auth events, content changes) because it supports grading and debugging.

---

## Notes
- All authentication must use **Google Accounts**.
- All user media must be stored and retrieved via **Amazon S3**.
- **In-app messaging** is required (email does not count).
- These stories are intentionally **domain-agnostic** so teams can adapt them to specific sustainability problem areas (e.g., food waste, transit, energy, reuse).
