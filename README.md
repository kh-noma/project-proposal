# Ayga: A social café discovery platform

## What and Why?

We want to build **Ayga**, a social café discovery platform where people find new cafés through the taste of people rather than through anonymous star ratings.

Star-rating systems (Google Maps, Yelp) compress a café into a single number that tells you almost nothing about fit. A 4.3-star coffee shop could be a quiet study spot, a loud brunch scene, or a place with great coffee but nowhere to sit. Meanwhile, most people already discover restaurants and cafés the way they discover movies or music: through friends, curators, and people whose taste they trust.

Users follow people, leave notes and photos about places they've visited, save cafés to themed boards and collections, and discover new places through their social activity and curated picks. This is important because it affects a daily decision.

## For Whom?

Ayga is for **young, mobile-first urban café-goers** such as students, remote workers, and young professionals who treat cafés as a "third place" for studying, working, or socializing (the same audience that uses Letterboxd, Beli social products).

Concretely, our initial end-users are:
- **University students** in cities with a dense, fast-changing café scene, who need to find a place to study or meet.
- **Local café-goers in small-to-mid-size cities** currently underserved by other tools like in Mongolia.
- **Café owners and admins**, as a secondary user group, who want their listing to be accurately represented and want to see engagement.

We will validate design decisions by interviewing and testing with real students on campus and with the existing Mongolian user base, rather than designing for a hypothetical audience.

## How?

Ayga works as follows:

- **Discover.** A user opens Ayga and sees a feed of cafés found by people they follow, curated "Creator's Corner" collections ("Best late-night study spots").
- **Explore a café's page.** Each café has a profile page with photos, a short vibe description, menu photos, tags (e.g. "quiet," "good wifi," "outdoor seating"), and a feed of notes/photos/check-ins left by users.
- **Log and share.** A user can check in at a café, leave a short written note or photo about their visit.
- **Curate.** Users can save cafés to personal boards/collections.
- **Follow and connect.** Users follow other users (friends, or curators/tastemakers).
- **Contribute.** Users can add new cafés and suggest edits to existing listings, which are reviewed by admins to keep data accurate.
- **Manage (admin).** Café owners/admins can claim and manage their café's listing, respond to suggested edits, and see engagement (saves, check-ins) on their page.

## Scope

Ayga requires designing and implementing a social graph (follows, feeds, boards), a content-moderation/admin-review system for user-submitted café data, authentication, image handling, and a ranking/discovery feed. However, the core feature set is a set of features with precedent in existing consumer social apps. First, the scope can be around NYC or NYU campus community for the semester's MVP.
