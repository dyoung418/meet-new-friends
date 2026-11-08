# Personal CRM / "people notes" apps on iOS, evaluated for a selfie-first capture workflow

Scope note: research conducted 2026-11-08 from official sites, App Store listings, vendor help docs, competitor roundups and community threads. Several App Store pages show update dates without a year (e.g. "Oct 30"); Apple omits the year only for the current calendar year, so these are inferred to be 2026 and flagged as such. No app was hands-on tested, so "taps from open to saved" counts could not be verified for any app (see Gaps).

## Key question 1: Inventory of candidates — name, developer, platforms, pricing (as of Nov 2026), status

### Takeaway
Of the ~20 named candidates, the actively maintained iPhone-native personal CRMs are Mesh (ex-Clay), Dex, Covve, Hippo, Dextr, Intriq, Cloze and Cardhop; Monica, folk and Nat are web-only (Monica usable in a phone browser); Garden is abandoned (last update June 2020); UpHabit is reported shut down in April 2026 by a competitor but its App Store listing was still live, so its status is contested; Plum Contacts has no findable App Store listing. A separate class of "remember names" apps (Remember Names, Appstar, FaceCards, Name Reminder, Memorio, Names to Remember) is built around photo + name + where-met and is closer to the stated workflow than the networking CRMs.

### Cited Findings

**Mesh (formerly Clay, clay.earth → me.sh)**
- Clay personal CRM was acquired by Automattic in June 2025 and renamed Mesh; the old domain redirects; "Same team, same product, new name." It is distinct from Clay.com, the B2B enrichment platform — [lemlist](https://www.lemlist.com/blog/personal-crm)
- Mesh's own announcement of the rename is dated 26 March 2026 — [me.sh](https://me.sh/stories/mesh)
- App Store: "Mesh: Contacts + CRM", seller Clay Software, Inc., © 2026 Automattic; version 2026.7.3 released Oct 30 (year not shown; inferred 2026); iOS 17.0+, also iPadOS/macOS/visionOS; 4.4 stars from 766 ratings; IAP "Mesh Membership" $19.99/mo or $119.99/yr; "Mesh Personal" free, limited to 1,000 contacts — [App Store](https://apps.apple.com/us/app/mesh-contacts-crm/id1463073824)
- Official pricing page: Personal free up to 1,000 contacts; Pro $10/month (shown with a 50% discount badge; annual price not extracted); Team $40/seat/month; 14-day Pro trial requires a credit card; platforms listed as "macOS, web, Windows & iOS apps"; no Android — [me.sh/pricing](https://me.sh/pricing)
- Privacy labels (developer-reported): data linked to you includes Contact Info, Contacts, User Content (emails/texts), Search History, Identifiers, Usage Data — [App Store](https://apps.apple.com/us/app/mesh-contacts-crm/id1463073824)
- Mesh is SOC 2 Type 2 certified and can provide a HIPAA BAA — [me.sh/pricing](https://me.sh/pricing)

**Dex (getdex.com)**
- App Store: "Dex - Rolodex and Personal CRM", developer Dana HQ, Inc.; version 3.83.0 updated "2d ago" at fetch time; requires iOS 18.0+; 4.4 stars from 266 ratings — [App Store](https://apps.apple.com/app/id1472132715)
- Official pricing: Premium $12/user/mo annual or $20 monthly; Professional $20 annual or $34 monthly; both have 7-day trials requiring a card; Team $40/user/mo; Premium includes mobile, browser extension, web and desktop and "two-way contact sync" — [getdex.com/pricing](https://getdex.com/pricing)
- App Store IAP list shows higher monthly figures: Premium $19.99/mo, $143.99/yr; Professional $39.99/mo, $239.99/yr — [App Store](https://apps.apple.com/app/id1472132715) (conflicts with web pricing above; likely App Store markup, unverified)
- Privacy labels: linked to you — Contact Info, Name, Contacts, Usage Data — [App Store](https://apps.apple.com/app/id1472132715)

**Monica (monicahq.com)**
- Official site: Monica v3 "is coming before the end of 2026", "Rebuilt from scratch", still open source; v3 ships a responsive web app first, then native iOS and Android apps ("real applications, not a website in a shell"); the current web app "works on a phone today"; self-hosted is free; hosted is a paid subscription but registration is currently closed and no price is shown — [monicahq.com](https://monicahq.com/)
- Third-party pricing for hosted: $9/mo or $90/yr; hosted free tier capped at 10 contacts — [lemlist](https://www.lemlist.com/blog/personal-crm); same figures at [getdex.com list](https://getdex.com/blog/personal-crm-list/)
- Competitor review: on mobile Monica "loads in a browser. The layout is only partially responsive, and manipulating data on a phone is difficult" — [getdex.com Monica review](https://getdex.com/blog/monica-review/) (competitor source, biased)

**Covve**
- App Store: "Covve: Personal CRM & Contacts", seller Covve Visual Network Limited; version 29.8, Oct 31 (year not shown; inferred 2026); iOS 17.0+; 4.5 stars from 626 ratings; Covve PRO IAPs listed at $12.99 and $4.99 monthly and $119.99/$79.99/$49.99 annual (tiers/regions not labelled) — [App Store](https://apps.apple.com/us/app/-/id958935377)
- Third-party: free for up to 20 contacts; Pro $9.99/mo annual or $12.99 monthly; iOS and Android only, no web/desktop; notes a 2020 data breach — [getdex.com list](https://getdex.com/blog/personal-crm-list/)
- Privacy labels: linked to you — purchase history, email, name, contacts, user ID, device ID, product interaction, crash data — [App Store](https://apps.apple.com/us/app/-/id958935377)

**Hippo (Studio Skipper)**
- App Store: "Hippo – Personal CRM", seller Roel van der Kraan / Studio Skipper; version 2.2.0 released Oct 27 (inferred 2026); iOS 18.4+; free to try with up to 25 contacts; IAPs: Monthly $1.99, Yearly $13.99–$14.99, Lifetime $29.99; 3.0 stars from 8 ratings; no account needed; developer states the app "has no servers" and data is kept "on your devices and in your iCloud" — [App Store](https://apps.apple.com/app/id1458330948)
- Lemlist lists Hippo at $1.49/mo or $14.99/yr with a 1-month trial, iOS only — [lemlist](https://www.lemlist.com/blog/personal-crm) (conflicts slightly with App Store $1.99)

**UpHabit — status contested**
- Dex's list says UpHabit "shut down its personal CRM apps in April 2026" after shifting to sales-focused work in 2022 — [getdex.com list](https://getdex.com/blog/personal-crm-list/)
- The US App Store listing was still retrievable via search snippets in Nov 2026, requiring iOS 18.0+, with Professional and Super Connector tiers at $19.99/mo or $119.99/yr — [App Store](https://apps.apple.com/us/app/id1335632832); the listing itself returned HTTP 404 on direct fetch and uphabit.com returned HTTP 503 during this research
- No independent shutdown notice was found; a search for "UpHabit shutting down April 2026" surfaced only old material — [search results](https://www.producthunt.com/products/uphabit)

**Garden: Stay in Touch — effectively abandoned**
- App Store: seller Meaning Labs, Inc.; version 1.1.8 released 06/04/2020; iOS 10.0+; free, no IAP; 3.9 stars from 50 ratings; reminder-style app with per-contact notes — [App Store](https://apps.apple.com/us/app/id1230466454)
- Dex's list: "iOS-only app by a solo founder. It has not been updated since mid-2020" — [getdex.com list](https://getdex.com/blog/personal-crm-list/)

**Dextr (Hidden Spectrum, LLC)**
- App Store: "Contacts + CRM by Dextr"; version 3.6.4, updated ~1 day before fetch; requires iOS 26.0+; Pro $2.99/mo or $14.99/yr; free tier with limited advanced search; 5.0 stars from 49 ratings; files/photos/videos attachable to contacts, events and journal entries; Contact Journals log "how, when, and where" interactions occurred; labels/groups with bulk tagging; on-device AI that "never sends data to third-party services"; privacy labels show nothing linked to identity — [App Store](https://apps.apple.com/us/app/-/id6462423477)
- Described as syncing bi-directionally with iPhone native contacts — [search result summary citing App Store](https://apps.apple.com/app/id6462423477)

**Intriq (Fang Ventures Private Limited, Singapore)**
- Shipped on the App Store in May 2026 — [SaaSHub](https://www.saashub.com/intriq-app)
- Vendor blog (updated Aug 15, 2026): iPhone app plus web app; "Capture a note in a sentence or by voice" and Intriq files it under the right person; free plan, "Plus is an optional upgrade" with no price listed; "Private by design", never scrapes public profiles; photo capture not mentioned — [intriq.app](https://www.intriq.app/blog/best-personal-crm-apps-for-iphone/)

**Cloze**
- App Store: "Cloze Relationship Management", Cloze, Inc.; version 2026.5 released May 18, 2026; iOS 16.0+; 4.7 stars from ~2.9K ratings; business/sales and real-estate focus; free tier = contact management and basic email; Cloze Pro $19.99 (monthly) / $199.99 (annual, billing not labelled); Business Silver $24.99/mo–$249.99/yr up to Platinum $49.99/mo–$499.99/yr; privacy labels link contacts, email content, identifiers to you — [App Store](https://apps.apple.com/us/app/-/id596927802)
- Cloze has no native business card scanner; its help doc describes scanning via Evernote, available on Premium/Personal/Professional/Teams — [Cloze help](https://help.cloze.com/article/2142-can-i-scan-a-business-card-with-evernote-and-have-it-automatically-import-into-cloze)

**Cardhop (Flexibits)**
- Official: natural-language contact entry; can scan a business card or printed address with the iPhone/iPad camera to create a contact; per-contact notes with a timestamp button to log interactions; relationship chart; birthday/anniversary reminders; integrates with device contact accounts (iCloud, Google, Exchange); Mac/iPhone/iPad/Vision Pro; "Start for Free" with premium features via Flexibits Premium subscription (prices not on page) — [flexibits.com/cardhop](https://flexibits.com/cardhop)
- Cardhop 2.0 is free; premium features require Flexibits Premium — [Flexibits blog, May 2021](https://flexibits.com/blog/2021/05/cardhop-2-0-and-flexibits-premium/)
- Flexibits Premium annual pricing reported as $56.99 from Jan 2023 (dated) — [MPU forum](https://talk.macpowerusers.com/t/fantastical-cardhop-price-increase/31738)

**folk**
- Web only, no mobile app; Standard $24/member/mo, Premium $48/member/mo (annual); free tier capped at 100 contacts; imports Google contacts, not iOS Contacts; tags supported — [getdex.com list](https://getdex.com/blog/personal-crm-list/); lemlist: "priced for teams" — [lemlist](https://www.lemlist.com/blog/personal-crm)

**Contacts+ (ex-FullContact consumer app)**
- Web, iOS, Android, Mac; free for one account; Premium $9.99/mo; notes and tags, advanced search, built-in business card scanner, two-way contact sync, dedupe; lemlist reports "user-reported bugs" — [lemlist](https://www.lemlist.com/blog/personal-crm); "not a full CRM" — [getdex.com list](https://getdex.com/blog/personal-crm-list/)

**Nat.app**
- nat.app homepage footer reads © 2022; web login at contacts.nat.app; works via Gmail/Google Calendar integration "On your computer and smart phone"; no dedicated iOS app; notes taken inside Gmail; no shutdown notice but no 2023+ content — [nat.app](https://nat.app/)
- Founder's last Medium post found is Jan 2021 and the Product Hunt launch was March 30, 2022 — [Product Hunt](https://www.producthunt.com/p/nat-ai/nat)

**Plum Contacts**
- Launched on Product Hunt Nov 11, 2019; reminders to message contacts on a schedule, "berries" indicate relationship strength; no current App Store listing was found — [Product Hunt](https://www.producthunt.com/products/plum-contacts)

**Circleback** — meeting-notes AI tool; not researched further because it is meeting-transcription oriented, not a people-capture app (no source consulted; see Gaps).

**Name-memory apps (photo + name + where met)**
- *Remember Names: Name Reminder* — Chestwick Investments Inc; v5.15 released Oct 23 (inferred 2026); iOS 17.0+, watchOS, macOS, visionOS; free with IAPs ($1.99/$4.99/$29.99 Standard; $79.99 Lifetime); up to 10 photos per name via photo picker; record name pronunciation; groups with nested subgroups; records where you met with map and location-return reminders; search; notes; iCloud sync; CSV/JSON import/export; Apple Watch add/search; privacy label "Data Not Collected"; 4.3 stars from 24 ratings; v5.15 note: "Adding people is easier through suggested names, notes, and groups from a short description" — [App Store](https://apps.apple.com/us/app/id6504533632); feature list also at [remembernames.app](https://www.remembernames.app/)
- *Appstar – Remember Names* — APPSTAR PTY LTD; v1.3.2 (Sep 9, year not shown); iOS 13.0+; profile per person with photos, "notes on where you met", colour-coded tags, search, actions/reminders; "All features $1.99"; data "securely stored and synced to your account"; 1 rating; camera capture not mentioned — [App Store](https://apps.apple.com/us/app/appstar-remember-names/id1508216230)
- *FaceCards – Memorize People's Names* — Steven Edwards; last updated v1.0.1 May 15, 2017; iOS 10+; take a picture in-app or add photos from album; photos taken in-app saved to Photo Album with GPS tags; spaced-repetition quizzes; notes and phone number; import/export to Contacts; sort by name/due date/recall; $0.99 unlock (demo 10 people); no privacy details provided; no ratings — [App Store](https://apps.apple.com/us/app/facecards-memorize-peoples-names/id1218293600)
- *Name Reminder: Remember Names* — Digital Palette LLC; v2.4 (Sep 3, year not shown); iOS 17.6+; custom groups, notes, search across nicknames/kids/pets/jobs/notes; face-first flashcards; JSON backup/restore; iCloud sync is Pro; IAP Pro Monthly $5.99, Annual $34.99, "Friend Keeper Pro" $89.99 (listing also mentions one-time $9.99, inconsistent); 4.6 stars from 8 ratings — [App Store](https://apps.apple.com/us/app/name-reminder-remember-names/id6450018987)
- *Names to Remember* — official site: iOS/iPadOS; add photos, location tracking and address search, map view by city, custom tags, "group by date met", search by name/location/tags/any detail, notes; Pro features: iCloud sync, CSV export, export to iOS Contacts, Face ID lock, colour-coded lists; developer and prices not stated — [namestoremember.app](https://www.namestoremember.app/)
- *Memorio / People Journal: Memorio* — developer Tomohiro Suzuki; free with IAPs; iOS 15.6+; record each person's photo, name, birthday, address, family/client details and conversation notes; a reviewer says it can import contacts, add photos to contacts and sync between iOS devices; launched July 2020 — [App Store JP listing](https://apps.apple.com/jp/app/id1508929510?l=en-US), [App Store US](https://apps.apple.com/us/app/id1508929510)
- *Known Names: Remember Everyone* — free; built around jotting a name down quickly after meeting someone, with details like workplace, hobbies, family — [App Store](https://apps.apple.com/app/id6751477026)
- *Rememorate* — Rememorate, LLC; iOS and Android; "helps you remember people's names" for networking events; no pricing or feature detail on the site — [rememorate.com](https://rememorate.com/)

**Apple built-ins**
- Photos People & Pets: open a photo, tap Info, tap the face marked "?", tap "Edit Name and Photos" → "Name This Person"; Photos suggests names from Contacts but you can type one manually; unrecognized faces appear with a question mark — [Apple Support](https://support.apple.com/en-us/HT207103)
- Community reports: faces that are backwards or obscured "may not be identified at all so no option to name them might appear" — [Apple Discussions](https://discussions.apple.com/thread/255832826)
- Journal (iOS 18) added state-of-mind logging, insights, improved search and widgets; Journal suggestions can draw on Contacts/Photos (toggleable in Settings); no manual people-tagging feature was described — [Tom's Guide](https://tomsguide.com/phones/iphones/ios-18-journal-whats-new-in-the-iphones-diary-app)

### Inferences
- Pricing for the networking-oriented CRMs clusters at $10–20/month (Mesh, Dex, Covve, Cloze, folk, Contacts+), while the iPhone-native "people notes" apps (Hippo, Dextr, Remember Names, Appstar, Name Reminder) are $1–6/month or one-time purchases under $30.
- The App Store IAP prices for Dex ($19.99/mo) and Mesh ($19.99/mo) exceed the web prices ($20 and $10 monthly respectively, with cheaper annual rates); buying via the web is likely cheaper, though no source states this explicitly.
- UpHabit should be treated as "likely discontinued, unconfirmed": the only shutdown claim is from a competitor, but the company site was down (503) during research.

### Gaps
- Could not fetch the Names to Remember App Store listing (apps.apple.com/app/names-to-remember returned 404; no app ID found), so developer, price and last-update date are unknown.
- Intriq Plus pricing not published anywhere found.
- Monica hosted plan price is not on the official site in Nov 2026 (registration closed); the $9/mo figure is third-party.
- Cardhop/Flexibits Premium current price not retrieved from Flexibits directly.
- Circleback, Obsidian/Craft/Bear/Notes templates were not individually researched for this workflow; the only template-style evidence is Nat Eliason's Airtable personal CRM tracking "how we met" — [nateliason.com](https://www.nateliason.com/blog/personal-crm) and Dex's Obsidian comparison — [getdex.com](https://getdex.com/blog/dex-vs-obsidian.md).

## Key question 2: Which apps support camera capture at the moment of adding a person, and the per-app feature checklist (a)–(k)

### Takeaway
Only one app found explicitly documents an in-app camera for a *face* photo when creating a person (FaceCards, last updated 2017). Mesh, Dex, Covve, Cardhop and Contacts+ have in-app cameras but for *business cards*, not selfies. Every actively maintained CRM either does not document how photos are attached or uses the photo library picker (Remember Names, Dextr). Hippo, Remember Names and Dextr are the strongest on on-device/iCloud privacy; Mesh, Dex, Covve and Cloze store data in vendor clouds and read your contacts/email.

### Cited Findings

Feature-checklist evidence per app (where a cell is "not documented", no source found states it either way):

**Mesh**
- (a) Business card scanning can save scans to the Photo Library (v2026.4.2); a Photo Library integration was previewed (v2026.3); contact cards have profile photos; no selfie/camera-on-create documented — [App Store](https://apps.apple.com/us/app/mesh-contacts-crm/id1463073824)
- (c) "dictation and note taking" listed; competitor notes "iOS Dictate and OCR in notes" — [App Store](https://apps.apple.com/us/app/mesh-contacts-crm/id1463073824); [getdex.com list](https://getdex.com/blog/personal-crm-list/)
- (e) Natural-language search ("Just type what comes to mind") — [App Store](https://apps.apple.com/us/app/mesh-contacts-crm/id1463073824)
- (g) Groups, plus #labels in notes — [App Store](https://apps.apple.com/us/app/mesh-contacts-crm/id1463073824); [getdex.com list](https://getdex.com/blog/personal-crm-list/)
- (h) Notes per card with reminders — [App Store](https://apps.apple.com/us/app/mesh-contacts-crm/id1463073824)
- (j) Vendor cloud; privacy labels link Contacts, email/text content, search history to identity; export not documented — [App Store](https://apps.apple.com/us/app/mesh-contacts-crm/id1463073824)
- (k) iCloud/iOS Contacts is an import source; lemlist: "requires broad access to your email and calendar" — [lemlist](https://www.lemlist.com/blog/personal-crm)
- User reviews complain contacts cannot be deleted (only archived), missing notes, failed iMessage import, missing iPhone contacts — [App Store](https://apps.apple.com/us/app/mesh-contacts-crm/id1463073824)

**Dex**
- (a) "Fully reworked Business Card scanner flow" (v3.61.0); photos of people not mentioned — [App Store](https://apps.apple.com/app/id1472132715)
- (c) "Improved voice-to-text note dictation" (3.61.0) and "New 'Talk to Dex' mode" (3.77.0); Professional plan includes "Voice mode" — [App Store](https://apps.apple.com/app/id1472132715); [getdex.com/pricing](https://getdex.com/pricing)
- (e) Search notes in one place — [App Store](https://apps.apple.com/app/id1472132715)
- (g) Groups, custom tags and views — [App Store](https://apps.apple.com/app/id1472132715)
- (h) Timeline notes — [lemlist](https://www.lemlist.com/blog/personal-crm)
- (j) Vendor cloud; iOS app offers offline support per a review site; Dex says it will "never sell or give your data to third parties" — [getdex.com/pricing](https://getdex.com/pricing)
- (k) Two-way contact sync on Premium; reviews report slow saves, sync delays, LinkedIn sync problems (2023–2025) — [App Store](https://apps.apple.com/app/id1472132715)

**Covve**
- (a) "Scan business cards straight into your contacts"; can scan a paper card or QR code, or import a card photo from the gallery; contact (face) photo not documented — [App Store](https://apps.apple.com/us/app/-/id958935377); [Covve help](https://help.covve.com/doc/business-card-scanning-scan-business-cards-and-get-all-the-details-straight-into-your-address-book)
- (h) "add a note in seconds right after a meeting or call"; post-call note prompts — [App Store](https://apps.apple.com/us/app/-/id958935377); [getdex.com list](https://getdex.com/blog/personal-crm-list/)
- (g) Tags for categories such as clients, investors, mentors, friends — [App Store](https://apps.apple.com/us/app/-/id958935377)
- (k) Starts with contacts already on your phone; a 2023 review says sync created duplicates and wiped nicknames — [App Store](https://apps.apple.com/us/app/-/id958935377)
- (j) Vendor cloud; privacy labels link contacts, IDs, purchase history to identity — [App Store](https://apps.apple.com/us/app/-/id958935377)

**Hippo**
- (a) Not documented; version notes say "Imported photos keep their orientation" (2.1.1) and contact photos appear in Siri/Shortcuts (2.2) — [App Store](https://apps.apple.com/app/id1458330948)
- (c) Siri and Shortcuts: add notes and reminders by voice; search notes/reminders by person, text or date; Siri with Apple Intelligence features require iOS 27 — [App Store](https://apps.apple.com/app/id1458330948)
- (f) Search by date via Shortcuts; events per contact — [App Store](https://apps.apple.com/app/id1458330948)
- (g) Tags added in 2.1 with filter by tag — [App Store](https://apps.apple.com/app/id1458330948)
- (h) Notes, events and reminders per contact; link contacts to each other — [App Store](https://apps.apple.com/app/id1458330948)
- (j) On device + iCloud; "no servers"; no account; export not documented — [App Store](https://apps.apple.com/app/id1458330948)
- (k) No Contacts access required — [App Store](https://apps.apple.com/app/id1458330948); [Product Hunt](https://www.producthunt.com/products/hippo-2)
- Reviews cite crashes and that notes must be written manually — [App Store](https://apps.apple.com/app/id1458330948)

**Dextr**
- (a) Files, photos and videos attach to profiles, events and journal entries (method not documented) — [App Store](https://apps.apple.com/us/app/-/id6462423477)
- (e) In-Depth Search, Advanced Search (3 filters free), Saved Searches (Pro) — [App Store](https://apps.apple.com/us/app/-/id6462423477)
- (g) Labels/groups by any criteria; bulk tagging — [App Store](https://apps.apple.com/us/app/-/id6462423477)
- (h) Contact Journals log "how, when, and where" interactions occurred — [App Store](https://apps.apple.com/us/app/-/id6462423477)
- (j) On-device AI, "never sends data to third-party services"; nothing linked to identity in privacy labels; "full backup file" mentioned — [App Store](https://apps.apple.com/us/app/-/id6462423477)
- (k) Built on iPhone Contacts with bi-directional sync and cleanup tools — [App Store](https://apps.apple.com/us/app/-/id6462423477)

**Remember Names**
- (a) Photo picker with multiple selection, up to 10 images per name (camera not documented) — [App Store](https://apps.apple.com/us/app/id6504533632)
- (c) Record how names are pronounced; v5.15 suggests names/notes/groups "from a short description" — [App Store](https://apps.apple.com/us/app/id6504533632)
- (e) Search; (g) groups and nested subgroups; (h) notes + where you met with map and location-return reminders; (j) iCloud sync, CSV/JSON export, "Data Not Collected"; (k) Contacts integration not mentioned; developer says it is meant to supplement, not replace, Contacts — [App Store](https://apps.apple.com/us/app/id6504533632)

**FaceCards**
- (a) "take a picture of a person in the app, or add multiple photos from your Photo Album"; in-app photos saved to Photo Album with GPS tags; (f) sort by due date; (h) notes + phone; (k) import from and save back to address book; last updated 2017 — [App Store](https://apps.apple.com/us/app/facecards-memorize-peoples-names/id1218293600)

**Cardhop**
- (a) Camera scanning of business cards/printed addresses; adding from a photo not mentioned; (h) notes with timestamp button; (k) uses device contact accounts (iCloud, Google, Exchange) — [flexibits.com/cardhop](https://flexibits.com/cardhop)

**Monica**
- (h) Notes and journal entries; a "How you met" field is shown on the sample record; custom fields in v3; (j) full export anytime, vCard/CSV import, "Private by design", no model training; self-hostable — [monicahq.com](https://monicahq.com/)
- (k) No automated contact imports; "requires a lot of manual input" — [lemlist](https://www.lemlist.com/blog/personal-crm)

**Apple Photos**
- (a) Camera is native; (e) naming via People & Pets; (i) face recognition is the mechanism; names suggested from Contacts; unrecognized faces show "?" — [Apple Support](https://support.apple.com/en-us/HT207103)

**Face recognition (i)**: no personal CRM or name-memory app found documents automatic face recognition; Apple Photos is the only product in scope that does — [Apple Support](https://support.apple.com/en-us/HT207103)

**Multiple people per photo (d)**: not documented by any app found.

### Inferences
- For the literal workflow "open app → camera → selfie with stranger → name", no actively maintained app is a documented fit. The closest actively maintained options require a photo-library round-trip (take selfie in Camera, then pick it in the app): Remember Names, Dextr, Appstar, Memorio, Hippo.
- A two-app pattern — Apple Camera + Apple Photos People naming — gives camera capture plus face recognition for free, but only when Photos detects the face, and it has no "where met"/tag/notes fields.
- Sorting by date added/met (f) is weakly supported across the category: Names to Remember claims "group by date met"; Dextr journals record when; FaceCards sorts by due date; Hippo exposes date search via Shortcuts. None of the big CRMs (Mesh, Dex, Covve) document a date-met sort.

### Gaps
- Tap counts (b) for any app could not be verified without hands-on testing; no review or help doc gives them.
- Whether Mesh, Dex, Covve, Hippo, Dextr or Intriq open the camera (vs. photo library) when adding a person's photo is undocumented in every source consulted.
- Export for Mesh, Dex, Covve, Hippo, Intriq is not documented in the sources found.

## Key question 3: Which apps are closest to "remember strangers I just met" vs. "nurture existing network"?

### Takeaway
Mesh, Dex, Covve, Cloze, folk, Contacts+ and Nat are built around importing and nurturing an existing network (email/calendar/LinkedIn sync, keep-in-touch reminders). The "remember strangers" use case is served by the name-memory apps (Remember Names, Appstar, FaceCards, Name Reminder, Known Names, Names to Remember, Memorio), by Hippo and Dextr (lightweight notes without importing a network), and by newer voice-first capture apps (Intriq, Recall People, RapportBuddy).

### Cited Findings
- Dex is "best for LinkedIn-heavy networking" and its browser extension does most of the capture work — [igeeksblog/search summary](https://www.igeeksblog.com/best-iphone-crm-apps/); [lemlist](https://www.lemlist.com/blog/personal-crm)
- Mesh auto-imports contacts from email, calendar, LinkedIn and Twitter and enriches them; iMessage and WhatsApp sync — [lemlist](https://www.lemlist.com/blog/personal-crm); [getdex.com list](https://getdex.com/blog/personal-crm-list/)
- Covve automatically logs calls, texts and emails and prompts for post-call notes — [getdex.com list](https://getdex.com/blog/personal-crm-list/)
- Nat identifies "who they're losing touch with based on their data" via Gmail/Calendar — [nat.app](https://nat.app/)
- Garden and Plum are reminder-to-reach-out apps — [App Store](https://apps.apple.com/us/app/id1230466454); [Product Hunt](https://www.producthunt.com/products/plum-contacts)
- Hippo: "a quick glance at their profile before a meeting helps them recall details"; no account, no Contacts access — [App Store](https://apps.apple.com/app/id1458330948)
- Intriq (vendor): built for "fast memory capture" and pre-meeting briefs; says Dex "may feel more LinkedIn and desktop oriented" and Covve is "less focused on private memory" — [intriq.app](https://www.intriq.app/blog/best-personal-crm-apps-for-iphone/) (vendor claim)
- Appstar: "create a profile for someone you just met, add a photo, and jot a note" — [App Store](https://apps.apple.com/us/app/appstar-remember-names/id1508216230)
- Known Names: built around jotting a name down quickly after meeting someone — [App Store](https://apps.apple.com/app/id6751477026)
- Remember Names: records where you met, maps where you usually see someone, reminds you when you return — [App Store](https://apps.apple.com/us/app/id6504533632)
- Recall People: "record a quick voice note describing who you met, their role, company, and what you discussed" — [recall-people-2026.vercel.app](https://recall-people-2026.vercel.app) (early-stage product page)
- RapportBuddy: "Quick Add mode to capture key info in seconds during an event and works offline" — [App Store MX](https://apps.apple.com/mx/app/rapportbuddy/id6749875036)
- Octograf: "just take a photo of a business card to capture a contact" — [Product Hunt](https://www.producthunt.com/p/octograf-professional-relationship-os/octograf)
- Intriq's blog: most comparisons "overemphasize desktop features", and "needing a laptop or filling in many fields causes users to lose context" — [intriq.app](https://www.intriq.app/blog/best-personal-crm-apps-for-iphone/) (vendor claim)

### Inferences
- The networking CRMs' value lies in auto-import and enrichment, which presumes the person already exists in your email/LinkedIn graph; a stranger met in person has none of that, so those apps add friction (and cost) without benefit for this workflow.
- The name-memory apps match the intent almost exactly but are mostly tiny-developer products (1–50 ratings each), so longevity and polish are uncertain.

### Gaps
- No independent (non-vendor) review was found that evaluates Intriq, Recall People, RapportBuddy or Known Names.

## Key question 4: What do users say about friction for fast capture in the field?

### Takeaway
Community consensus is that capture must take under ~5–10 seconds or the habit dies; voice notes with automatic transcription are the method people report actually sticking; photographing business cards is a commonly reported failed habit; and heavy-sync CRMs draw complaints about slow saves, duplicates and broken imports rather than about capture speed per se.

### Cited Findings
- r/indiehackers thread (captured May 20, 2026): capture should take under 5 seconds (name, one line about the conversation, one tag such as "hiring" or "collab"); another commenter put the limit at ~10 seconds; typing during a conference "won't happen"; conference wifi unreliable so offline-first matters; business card photos were "a common failed habit" ("photographed cards and never looked at them again"); voice note plus automatic transcription was "the only approach they'd seen stick"; suggestion to save a badge photo as optional visual context; a follow-up reminder ~48 hours later — [Reddit snapshot](https://reddit.sentinel-team.org/posts/1tgrxga/snapshots/2026-05-20T21%3A16%3A21.161297Z)
- r/ExecutiveAssistants (July 2025): an EA logging people the executive meets; commenters suggested Outlook contact notes searched by event keyword, a Plaud recorder to capture interactions by voice, and business-card scanning apps; Dex and Notion named without detail — [Reddit snapshot](https://reddit.sentinel-team.org/posts/1rqfehx/snapshots/2026-03-11T07%3A40%3A11.988054Z)
- Dex App Store reviews (2023–2025) report slow saves, sync delays, contact import checkbox problems and LinkedIn sync issues; developer says app was rebuilt — [App Store](https://apps.apple.com/app/id1472132715)
- Mesh reviews: notes missing, contacts not deletable, failed iMessage import, no duplicate resolution — [App Store](https://apps.apple.com/us/app/mesh-contacts-crm/id1463073824)
- Covve 2023 review: contact sync created duplicates and wiped nicknames — [App Store](https://apps.apple.com/us/app/-/id958935377)
- Hippo reviews: crashes, cannot reorder reminders, notes must be written manually — [App Store](https://apps.apple.com/app/id1458330948)
- Remember Names reviews (2024–2025) praise Apple Watch access and the location feature; developer frames it as a supplement to Contacts — [App Store](https://apps.apple.com/us/app/id6504533632)
- Product Hunt commenter wanted "a quick-add widget for mobile with a single note field and automatic timestamps" — [Product Hunt](https://www.producthunt.com/products/remember-your-people)
- Monica is "setup-heavy" and "requires a lot of manual input"; on a phone "manipulating data... is difficult" — [lemlist](https://www.lemlist.com/blog/personal-crm); [getdex.com Monica review](https://getdex.com/blog/monica-review/) (competitor)

### Inferences
- The field evidence favours voice-first capture (Dex dictation/Talk to Dex, Hippo Siri Shortcuts, Intriq voice notes, Remember Names' description-to-fields) over photo-first capture; a selfie-first app would be differentiated but also runs against the "card photos never get looked at" pattern unless the photo is paired with a name/tag at capture time.
- Offline capability matters at events; only Dex (per a third-party review site) and RapportBuddy explicitly claim offline support, and Hippo/Dextr/Remember Names are local-first by design so likely work offline (inferred from their on-device storage claims, not stated).

### Gaps
- The Indie Hackers thread "have you paid for a personal CRM app" returned HTTP 403 and could not be read.
- No Hacker News thread specifically on photo-based people capture was found via search.
- No App Store review for any app explicitly discusses how many taps adding a person with a photo takes.

## Key question 5: 2025–2026 AI "people memory" apps and wearable companions — do they produce people summaries, and do they do photos?

### Takeaway
Wearable companions (Limitless, Bee, Omi, Plaud) identify speakers by voice and generate conversation summaries, and Limitless now auto-tags speaker names from introductions, but none found offers a photo of the person, a camera, or a browsable people directory as a core feature; accuracy complaints about speaker identification are common. Phone-only AI "people memory" apps (Intriq, Recall People) are voice/text-first and also do not advertise photos.

### Cited Findings
- Limitless announced it "now automatically tags speakers in your notes. When someone introduces themselves or is referenced in a conversation, AI will assign their name in the transcript and summary"; Speaker Identification was the top-voted feature request — [Limitless feedback board (search summary)](https://feedback.limitless.ai/announcements/your-limitlessrewind-round-up-ai-speaker-tagging-more-shipments-in-february)
- Limitless users report voice recognition "seems to forget who people are the next day", the same person split across two labels, and request "a list of all remembered names, with the ability to merge, edit, or delete them" — [Limitless feedback](https://feedback.limitless.ai/board/remember-everyones-name-if-it-recognizes-a-voice-display-the-speakers-name-in-the-app)
- A "personal CRM" feature request exists on Limitless's board (contents could not be fetched; board returned an error page) — [Limitless feedback](https://feedback.limitless.ai/b/kvj1nlve/feature-ideas/personal-crm)
- A competitor blog claims the Limitless Pendant is discontinued "as of late 2026" — [umevo.ai](https://www.umevo.ai/blogs/ume-all-posts/smartphone-companions-plaud-note-vs-notta-memo-vs-limitless-pendant) (competitor; unverified)
- Amazon's Bee launched Bee Frontier wearable ($74.99) and Bee Eclipse phone attachment ($99.99) in October 2026; Bee Pro is $11.99/month — [TechCrunch](https://techcrunch.com/2026/10/15/amazons-bee-launches-two-new-personal-ai-devices-starting-at-75/); [About Amazon](https://aboutamazon.com/news/devices/amazon-personal-ai-bee-frontier-bee-eclipse)
- Bee can access calendar, contacts, emails, location, photos and reminders; hands-on: "Bee doesn't necessarily know who the people around you are, but it can discern different speaking voices" — [TechRadar](https://www.techradar.com/computing/artificial-intelligence/i-cant-decide-if-i-love-or-hate-this-always-listening-ai-assistant-from-ces-2025)
- Omi: "You can create different Speech profiles for people you talk to" so it can recognize who is speaking; Omi acknowledges diarization "is a very hard problem today... No system is perfectly accurate yet" — [Omi help](https://help.omi.me/en/articles/13153540-using-the-omi-app)
- Plaud: automatic speaker diarization, then "Name speakers" per recording; renaming after a summary exists does not update the summary — [Plaud support](https://support.plaud.ai/hc/en-us/articles/50635937755161)
- Intriq: typed or spoken notes become person profiles and pre-meeting briefs; shipped May 2026; no photo capture mentioned — [intriq.app](https://www.intriq.app/blog/best-personal-crm-apps-for-iphone/); [SaaSHub](https://www.saashub.com/intriq-app)
- Recall People: voice-note description of who you met → profile — [recall-people-2026.vercel.app](https://recall-people-2026.vercel.app)
- Dex: "Talk to Dex" mode and AI pre-meeting briefs — [App Store](https://apps.apple.com/app/id1472132715); [lemlist](https://www.lemlist.com/blog/personal-crm)
- Mesh: "Nexus" AI navigator — [getdex.com list](https://getdex.com/blog/personal-crm-list/)
- Monica v3 will include an MCP server to connect your own assistant; Monica does not send relationships to a model on its own — [monicahq.com](https://monicahq.com/)

### Inferences
- Wearables solve "what did we talk about" rather than "what did they look like"; combining a wearable summary with a separate photo-first app would require manual linking, since none of the wearable apps documents photo attachment to a speaker.
- Speaker-name tagging depends on the person introducing themselves audibly; a selfie + typed/spoken name is a more deterministic identifier, which suggests room for a photo-first capture app to complement rather than compete with wearables.

### Gaps
- Could not read the Limitless announcement or feature-request pages directly (Frill board returned an error), so the date and exact behaviour of speaker tagging are from search summaries only.
- No source found describes a "People" directory view in Bee, Omi or Plaud apps.
- Omi, Bee and Plaud photo/camera capability: no evidence either way.
