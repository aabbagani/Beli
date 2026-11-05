# Verified Visit Reviews: a concept for Beli

**Concept prototype by Anvitha Abbagani, not a Beli product or screen. Made-up restaurants, people and data.**

**Live:** https://beli.abbagani.com

Diners use Beli to discover restaurants, then leave to double-check reviews elsewhere: every user I
interviewed trusted reviews on other platforms more than Beli's. Verified Visit Reviews lets people
prove a real visit, so readers can tell which reviews to trust.

**What the prototype does:**
- **Places you may have been:** visits matched from Google Calendar (simulated), ready to verify.
- **Write a review** is always one tap away at the bottom of a restaurant page. Once a visit is
  verified it becomes **Write a verified review**.
- **Verify Your Visit** on the restaurant page, below Go / Book / Call / Save: one tap with a calendar
  match, or a receipt upload. A clear receipt passes; a blurry one is flagged and the visit stays
  unverified. Receipts and photos are sample images, so nothing is uploaded.
- **New review:** Proof of Visit replaces the unused Add Labels field and never asks twice. Friend
  tags are social only. Photos are sample shots (the dish, drinks, the room). A skippable nudge asks for whatever is missing: a photo, a note, or both.
- **Profile:** progress to a Verified Reviewer badge at 15 verified reviews. Only verified reviews
  count. Turning off Google Calendar leaves receipt as the only option.
- Missing price or menu shows "Data unavailable" with similar places.
- A seven-step **Quick tutorial** (Back and Next, with the relevant part highlighted).

**What it doesn't do:** read a real calendar or receipt, AI summaries, reputation sorting, share
cards or a creator program (later phases in the PRD). State is kept in this browser only.

It is one HTML file with no build step. The only network request is for its Google Font.
