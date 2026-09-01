# CRM, Follow-Up, Retention, and Relationship System

The relationship system is not a paid “VIP benefit.” It is the business moat. Normal follow-up should feel personal and tied to the actual tattoo journey.

## CRM record fields

### Identity
- client ID
- name
- email
- phone
- city/state/country
- time zone
- social handle
- source
- referring person or artist

### Order
- tier purchased
- amount paid
- date purchased
- consultation date
- status
- UTM source / campaign / ad group / creative
- discount or referral credit used

### Tattoo project
- project title
- placement
- approximate scale
- style direction
- core meaning
- primary subject
- existing artist? Y/N
- artist name
- studio
- artist city
- actual tattoo budget band
- actual tattoo date if known
- progress/healed photos received Y/N

### Relationship
- client clarity before / after
- testimonial received
- publication permission status
- referred others Y/N
- repeat project Y/N
- interested in membership Y/N
- artist feedback received Y/N
- artist relationship status
- next follow-up date
- personal notes

## Pipeline statuses

1. **Visited / unconverted** — analytics only, not CRM unless email captured.
2. **Paid / Intake Missing**
3. **Intake Complete**
4. **Consult Scheduled**
5. **Consult Complete / Brief Pending**
6. **Brief Delivered**
7. **Artist Consultation Pending**
8. **Tattoo Booked**
9. **Tattoo In Progress**
10. **Tattoo Completed / Healing**
11. **Healed / Case Study Eligible**
12. **Dormant Relationship**
13. **Repeat Project Active**

## Required operational triggers

### Immediately after purchase
Send booking confirmation and intake link.

**Message:**
“Your consultation is booked. Before we talk, send me the messy version of the idea through this form. You do not need to have it organized. The more honest you are about what you know, what you do not know, and what you are nervous about, the more useful the call will be.”

### 24 hours before call
If intake incomplete:
“Quick heads-up: I still need your intake before our call so I can spend the live time actually helping instead of collecting basic info. If you can get that over today, we’re good.”

### Immediately after call
Internal only:
- record clarity score before;
- record major breakthrough;
- generate draft brief;
- create follow-up date.

### Brief delivery
“Here’s your Tattoo Blueprint and the shorter artist-facing brief. Read it once and make sure it sounds like *you*. If I misunderstood something you actually said in the consultation, reply and point it out. This is not meant to lock your artist into a design; it is meant to make the important parts of the project clear.”

### 24–48 hours after delivery
Send feedback form.

“Did the Blueprint actually make the idea clearer? I’m especially interested in anything that feels off or over-specified. I’d rather tighten the process than fish for compliments.”

### 7–10 days after delivery
Only if no artist update is known:
“Have you had a chance to talk to an artist about the project yet? I’m curious what they thought of the direction and whether anything changed once you got their perspective.”

### After artist consultation
If client says it went well:
“That’s exactly what I hoped would happen. If you’re comfortable sharing, send me the artist’s name/IG. I’d love to see how they interpret it when it comes together.”

If client is uncertain:
Do not position Joker as judge against the artist. Ask:
“What part feels unresolved: the idea itself, something the artist changed, or the fact that you’re having trouble saying how you feel about it?”

### When tattoo is booked
“Hell yeah. Send me the date when you know it. I want to see this one come together.”

No automated aftercare sales pitch here.

### 3–7 days after tattoo date
“Checking in because I remembered your appointment was this week. How did it go? If you have a photo and feel like sharing it, send it over.”

Do not diagnose healing from photos.

### 4–8 weeks later
“Healed-photo request: I’d love to see how it settled in once it’s healed. If you and the artist are both comfortable with it, I may also ask separately about using the project as a before/Blueprint/final case study.”

### 6 months later
Personalized, not generic:
“Randomly thought about your [specific project]. How’s it looking now? And have you started getting the itch for the next one yet?”

Only send when there is a real project detail to reference.

## Case-study permission workflow

Never treat a testimonial, body-photo upload, or recording consent as publication consent.

Need separate permissions for:
1. client quote;
2. client name/handle;
3. intake/reference screenshots;
4. Blueprint excerpts;
5. final tattoo photos;
6. executing artist attribution;
7. artist permission if their imagery/work is being used in promotional content beyond ordinary credit/share norms.

## Referral system — launch after 20 clients

Keep it simple:
- existing client refers a new paid $99/$250 client;
- new client gets $10 off;
- referring client gets $20 account credit after the new client completes the consultation;
- credits can stack up to the price of a future consultation but are never cash redeemable.

Do not discount $47 tier.

## Repeat-client offer

Do not create a separate SKU at launch. A repeat client simply buys another applicable consultation.

After enough repeat behavior exists, test a “Next Tattoo” return-client price because intake time is lower. Candidate test: $79–$89 for returning clients who already have a profile and need another normal Blueprint conversation.

## Future membership trigger

Do not launch a subscription until at least 10 clients independently ask for continuing access or use Joker repeatedly between projects.

Potential membership must sell guaranteed access, not normal friendship/follow-up.

Candidate structure to test later:
- $24/month or ~$230/year (20% annual discount);
- one structured 15-minute planning check-in per quarter;
- priority booking for paid Blueprint calls;
- persistent project/collector record;
- member rate on future $99 Blueprint sessions;
- defined async-question limit, never unlimited texting.

## Artist relationship CRM

Every artist touched by a client project gets a record only after the client identifies them.

Fields:
- artist name / handle;
- studio / city;
- style specialties observed;
- how relationship started;
- number of shared clients;
- artist feedback on briefs;
- whether artist is open to future referrals;
- whether artist has referred a client;
- B2B interest;
- personal notes.

Relationship stages:
1. Mentioned by client
2. Brief received
3. Feedback received
4. Warm contact
5. Mutual referral relationship
6. B2B pilot candidate

## Relationship rule

Never contact an artist pretending to have a partnership because one client chose them. The opening is simply:
“Hey, I helped [client] organize the intent for the [project] they brought you. I’m the tattooer who put that short brief together. I’m not trying to tell you how to design it; I’m testing a process that helps clients get clearer before they sit down with their artist. If you have 30 seconds after dealing with it, I’d genuinely value blunt feedback on whether the brief helped or got in your way.”
