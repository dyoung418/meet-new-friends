# Dedicated iOS App Store apps for remembering names and faces (photo + name capture, later lookup)

Research date: 2026-11-08. Scope: native iOS apps only. Data below comes from live apps.apple.com listing pages fetched on this date unless stated otherwise. App Store pages omit the year for releases within roughly the past 12 months; where a date is shown as e.g. "Oct 23" with no year I have recorded it as 2026 and flagged it "(year inferred)". A 404 from apps.apple.com on multiple storefronts is treated as "not currently available" but could in rare cases be a regional-availability artifact.

Feature-checklist key used throughout: (a) in-app camera capture; (b) type a name; (c) voice/speech-to-text name entry; (d) multiple people per photo; (e) browse/search by name; (f) browse by date; (g) categories/tags/groups; (h) notes/context fields; (i) face recognition/matching; (j) quiz/flashcards; (k) storage model, privacy label, export/backup. "Y" = stated on the listing; "N" = listing explicitly says no; "NS" = not stated on the listing (unverified).

## Key Question 1: Which dedicated apps exist on the App Store today (Nov 2026), and what are their specs?

### Takeaway
There are roughly 30 live, small-developer iOS apps in this niche; most are either (A) photo-flashcard/quiz trainers or (B) "jot the name + where I met them" notebooks. Only a handful combine in-app camera capture, name entry, notes, grouping and later search; none has a large user base (the biggest review counts are Name Shark 160 ratings, NameVault 120, Remember Names: Name Reminder 24, NameKeeper 24, PeopleRecall 24).

### Cited Findings

#### Tier A — Best fit for "take photo → attach name → later browse by name/date/category" (all currently live)

**1. PeopleRecall** — PEOPLERECALL LLC
- App Store: https://apps.apple.com/us/app/id6746344227 — Free, no IAP listed; Lifestyle; iOS 15.6+; rating 5.0 from 24 ratings — [App Store](https://apps.apple.com/us/app/id6746344227)
- Latest version 26.01.039 dated "Aug 29" (year inferred 2026): added home screen with recents/favorites, search improvements, image capture, Places and Things entry types, and tags. Prior 25.02.009 dated 11/18/2025; first release 25.01.001 on 07/02/2025 — [App Store](https://apps.apple.com/us/app/id6746344227)
- Checklist: (a) Y, photos "taken directly in the app or uploaded"; (b) Y; (c) Y, "speech-to-text" and notes "added by voice"; (d) NS; (e) Y, search by company, meeting place, interest or conversation (search bars present); (f) NS; (g) Y, groups and tags (default "No Group" group); (h) Y, key traits and notes fields, LinkedIn field; (i) NS; (j) NS (no quiz described); (k) local data only, manual backup export from an Admin screen that the developer tells users to run regularly because "only the user can access their data and the developer cannot restore it"; no iCloud sync stated — [App Store](https://apps.apple.com/us/app/id6746344227)
- Privacy label: Contact Info (email, name, phone) linked to you, for app functionality. All four excerpted reviews positive; no complaints — [App Store](https://apps.apple.com/us/app/id6746344227)

**2. Whodat? Remember Names & Faces** — tomople
- App Store: https://apps.apple.com/us/app/whodat-remember-who-you-met/id6756264879 — Free, no IAP listed, contains ads; Productivity; iOS 16.0+; English + Japanese; not enough ratings to display — [App Store](https://apps.apple.com/us/app/whodat-remember-who-you-met/id6756264879)
- Latest version 1.1.0 "Oct 5" (year inferred 2026) added "Today's Review" daily 30-second recall exercise with streaks and reminders, and a map of all meeting places; fixed a bug where photos could disappear. 1.0.0 released 12/17/2025 — [App Store](https://apps.apple.com/us/app/whodat-remember-who-you-met/id6756264879)
- Checklist: (a) Y, photos saved with each person; (b) Y; (c) partial — voice is described for *search*, not for name entry; (d) NS; (e) Y, search by name, company, place or tag; (f) Y, a calendar view shows entries by day; (g) Y tags (no "groups" term); (h) Y, name, company, title, tags, conversation notes, blanks can be filled later; (i) N — no automatic recognition, review is manual recall; (j) Y, spaced reminders at 1 day/3 days/1 week+, "memorized" rank; (k) description says data "stays on the device and isn't sent to the developer's servers"; no iCloud/export stated — [App Store](https://apps.apple.com/us/app/whodat-remember-who-you-met/id6756264879)
- Privacy label contradiction: label lists Identifiers, Usage Data and Diagnostics "used to track you" plus Device ID/Advertising Data linked to you for third-party advertising, which does not match the "stays on your device" claim — [App Store](https://apps.apple.com/us/app/whodat-remember-who-you-met/id6756264879)

**3. Remember Names: Name Reminder** ("Remember Names, People & Faces") — Chestwick Investments Inc (© Marc Estwick)
- App Store: https://apps.apple.com/us/app/remember-names-name-reminder/id6504533632 — Free with IAP; Productivity; iOS 17.0+, macOS 14+, visionOS 1+, watchOS 10.5+; 4.3 from 24 ratings; English + 13 languages — [App Store](https://apps.apple.com/us/app/remember-names-name-reminder/id6504533632)
- IAP list is confusing: "Remember Names Standard" at $1.99, $4.99 and $29.99, "Standard (50% off)" $29.99, "Lifetime" $79.99; periods not stated — [App Store](https://apps.apple.com/us/app/remember-names-name-reminder/id6504533632)
- Actively maintained: 5.15 on "Oct 23" (year inferred 2026) turns "a short description into suggested names, notes, and groups"; 5.14 (Jun) quiz achievements/streaks, "date added"; 5.11 (Apr) Contacts import, group sharing by link; 5.7 (09/09/2025) JSON import; 5.4 (08/08/2025) up to 10 photos per name, CSV/JSON export; 5.1 (06/13/2025) nested subgroups — [App Store](https://apps.apple.com/us/app/remember-names-name-reminder/id6504533632)
- Checklist: (a) NS (photos supported, in-app camera not stated); (b) Y; (c) NS — "name pronunciation recording" is audio playback, not speech-to-text input; (d) NS; (e) Y "easily search and find anyone"; (f) partial, a "Date Added" field exists but no date browse described; (g) Y groups + nested subgroups; (h) Y notes, plus location memory/map view and location reminders; (i) NS ("Photo Match" quiz is manual); (j) Y, Name Recall, Photo Match and multiple-choice modes; (k) iCloud sync; CSV + JSON import/export; Apple Watch, widgets, Siri Shortcuts — [App Store](https://apps.apple.com/us/app/remember-names-name-reminder/id6504533632)
- Privacy label: "Data Not Collected". One App Store reviewer (July 2025) called it the strongest of the name-remembering apps they tested; no complaints in the four excerpted reviews; developer reply says the app supplements, not replaces, Contacts — [App Store](https://apps.apple.com/us/app/remember-names-name-reminder/id6504533632); [search summary](https://apps.apple.com/us/app/remember-names-name-reminder/id6504533632)

**4. NameVault: Face & Name memory** (formerly listed as "Digital Yearbook: Name Tag" and "NameVault: Remember Face & Name") — Maxwell Kelly
- App Store: https://apps.apple.com/us/app/namevault-remember-face-name/id1525602410 — Free with IAP and ads; iOS 17.0+; 4.9 from 120 ratings (largest rating count among actively maintained apps) — [App Store](https://apps.apple.com/us/app/namevault-remember-face-name/id1525602410)
- Third-party listing shows the same app ID previously titled "Digital Yearbook: Name Tag", released 2020, 4.9 with 119 ratings — [appfelstrudel](https://appfelstrudel.com/id/1525602410/digital-yearbook-name-tag.html)
- IAP: 1-month $2.99, 3-month $2.99, "Digital Yearbook Full Access" $5.99, 1 week $1.99; version notes mention other prices ($24 full access, $9 holiday special) and conflicting free-face limits (2, 3 or 10) — [App Store](https://apps.apple.com/us/app/namevault-remember-face-name/id1525602410)
- Updated "3d ago" (≈Nov 5, 2026) version 556; 555 (Oct 24) "fixed the take a picture button"; 552 (Jul 23) fixed in-app purchases — [App Store](https://apps.apple.com/us/app/namevault-remember-face-name/id1525602410)
- Checklist: (a) Y, add from camera or Photos; (b) Y, tap face to name/rename; (c) NS; (d) NS; (e) NS on current listing (older listing text mentioned search); (f) NS; (g) NS; (h) NS (subtitle "People Notes" only); (i) N, manual tagging; (j) Y, 3-choice Name Quiz unlocked at 3 faces; (k) NS, older listing mentioned cross-device sync; no export (developer suggests screenshots) — [App Store](https://apps.apple.com/us/app/namevault-remember-face-name/id1525602410)
- Privacy label: Usage Data used to track you; Device ID, Usage/Advertising Data linked to you for third-party advertising. Complaint (11/28/2025): intro screen kept repeating and ads still showed after purchase — [App Store](https://apps.apple.com/us/app/namevault-remember-face-name/id1525602410)

**5. WhatsHisFaceAgain** — Quinn Robert Grieco
- App Store: https://apps.apple.com/app/id6770136593 — $2.99 one-time, no IAP; Productivity; requires iOS 26.4+ (very new); 1.6 MB; no ratings yet; © 2026 — [App Store](https://apps.apple.com/app/id6770136593)
- Checklist: (a) NS (photos supported); (b) Y; (c) NS; (d) NS; (e) Y, search by anything remembered; (f) NS; (g) Y custom groups (Work, School, Neighborhood); (h) Y rich notes, where met, contact info; (i) NS; (j) NS; (k) data "stays on your phone", syncs via user's own iCloud, save to Contacts; privacy label "Data Not Collected" — [App Store](https://apps.apple.com/app/id6770136593)

#### Tier B — Photo-flashcard / quiz trainers (store photo + name, practice recall; weak on notes/browse)

**6. Name Shark** — Awesome Geekness LLC — https://apps.apple.com/us/app/name-shark/id906531062
- Free; IAP Group Sharing 1-year $3.99, Remove Ads $0.99; iOS 7.0+; 3.5 from 160 ratings; last update 2.3.2 on 12/20/2017 (backend moved off Parse in 2017); privacy label "No Details Provided". Four quiz modes, group sharing/download. Complaints: lists lost when switching phones (2019, 2020), sharing broken and subscription un-renewable (09/08/2025), unresponsive support, iPad images shown at iPhone size — [App Store](https://apps.apple.com/us/app/name-shark/id906531062). Checklist: (a) NS on listing (a reviewer said the camera shortcut stopped working), (e) group search only, (g) groups, (j) Y, (k) cloud for shared groups — [App Store](https://apps.apple.com/us/app/name-shark/id906531062)

**7. FaceCards - Memorize People's Names** — Steven Edwards — https://apps.apple.com/us/app/facecards-memorize-peoples-names/id1218293600
- Free, IAP Unlimited People $0.99 (free demo up to 10 people); iOS 10.0+; no rating shown; last update 1.0.1 on 05/15/2017; privacy "No Details Provided". (a) Y take photo in app, multiple photos per person, GPS-tagged photos saved to Photo Album; (b) Y; (h) Y free-form notes + phone; (j) Y spaced-repetition with manual interval control; sort by name/due date/recall; share person to Contacts/text/email; no groups, no search, no cloud — [App Store](https://apps.apple.com/us/app/facecards-memorize-peoples-names/id1218293600)

**8. Remember Faces** — K N Padmavathamma — https://apps.apple.com/us/app/remember-faces/id6751904824
- Free; Monthly $2.99, Yearly $29.99, Lifetime $39.99; Health & Fitness; iOS 15.1+; no ratings; aimed at seniors/families; "wall of faces" with names and tags, Name Game quiz, free tier 5 faces and one game/day, family progress sharing; privacy "Data Not Collected"; version history not shown — [App Store](https://apps.apple.com/us/app/remember-faces/id6751904824)

**9. FaceTag: Memory Trainer** — Greg Lemoine — https://apps.apple.com/us/app/facetag-memory-trainer/id6756509803
- $0.99, no IAP; Education; iOS 26.1+; 16+ age rating; v1.2 on 12/21/2025 (first release 12/15/2025); practice with photos you already have (team directories, group photos); no social features; privacy "Data Not Collected"; everything else NS — [App Store](https://apps.apple.com/us/app/facetag-memory-trainer/id6756509803)

**10. NameDrill** — Manuel Pardo Gallego — https://apps.apple.com/us/app/namedrill/id6758942102
- Free; Premium $3.99 one-time (free: 1 group, 15 people); Education; iOS 13.0+; no ratings; groups (Work, Gym, School), Learn-mode flashcards, multiple quiz modes, spaced repetition, offline/on-device; privacy "Data Not Collected"; version history not shown — [App Store](https://apps.apple.com/us/app/namedrill/id6758942102)

**11. FaceRecall** — Sandcastle Software LLC — https://apps.apple.com/app/id6757681675
- Free, no IAP; iOS 16.6+; v1.1 "Aug 10" (year inferred 2026), 1.0 "Jan 14"; custom groups, smart flashcards, Speed Round and Scrambled Cards games; privacy: email + name linked to you; (a)(c)(e)(f)(h)(k) NS — [App Store](https://apps.apple.com/app/id6757681675)

**12. Friend Groups** (formerly "WhosWho") — SureProgramming LLC — https://apps.apple.com/pg/app/friend-groups/id6736708946
- $0.99; iOS 15.0+; v1.2 "4 Jan" (year inferred 2026) renamed app, 1.1 on 05/12/2025, 1.0 on 14/10/2024; unlimited groups, per-person notes, multiple-choice photo quizzes, CSV bulk import from Drive/Dropbox/OneDrive, export groups for sharing/backup, explicitly "no cloud sync", on-device; privacy "Data Not Collected" — [App Store](https://apps.apple.com/pg/app/friend-groups/id6736708946)

**13. Faces2Know** — Joachim Lindow / Lityd AB — https://apps.apple.com/us/app/faces2know/id6737505426
- Free; IAP 3 months $0.99, Unlimited $1.99; Business; iOS 18.0+; v1.2 on 11/08/2024; card-deck memory game with typed answers, progress stats, deck sharing; privacy "Data Not Collected" — [App Store](https://apps.apple.com/us/app/faces2know/id6737505426)

**14. Remember Me - to learn names** — Benjamin Zaiser — https://apps.apple.com/qa/app/remember-me-to-learn-names/id1171353699
- Free; IAP to exceed 4 cards and for import/export; iOS 12.0+; v3.1.0 on 26/08/2024 (Flutter rewrite 2024, original 2016); flashcards with spaced review and notifications, no account/backend; privacy "Data Not Collected" — [App Store](https://apps.apple.com/qa/app/remember-me-to-learn-names/id1171353699)

**15. Namester** — Interrobang Group (Bob Gordon) — https://apps.apple.com/sa/app/namester/id6444921353
- Paid (SAR 4.99 on Saudi storefront; USD not fetched); iOS 11.0+; v1.0.1.44 on 01/04/2023; "do-it-yourself flashcards for connecting names with faces", (a) Y "take a picture (right in the app)", (b) Y; privacy "Data Not Collected" — [App Store](https://apps.apple.com/sa/app/namester/id6444921353)

**16. Octoname** — Ben Polley (Germany) — https://apps.apple.com/de/app/octoname/id6747905410
- Free; IAP €5.99 listed, description says Pro $4.99/month; iOS 16.0+; 5.0 from 2 ratings; v1.4 on 11/07/2025 (first release 03/07/2025); flashcards with photo, personal notes and where met, groups (Work, Gym, Conference), Firebase cloud sync with Google sign-in; privacy label links purchases, email, photos/videos, IDs, usage to you — [App Store](https://apps.apple.com/de/app/octoname/id6747905410?l=en-GB); launch press release July 2025 — [Barchart/ABNewswire](https://www.barchart.com/story/news/33507895/octoname-helps-remember-names-effortlessly-and-solve-the-embarrassing-problem-of-forgetting-names)

**17. NameQuiz** — Roman Voglhuber — https://apps.apple.com/us/app/-/id6751534335
- Free, no IAP; Utilities; iOS 17+; 1.9 MB; no ratings; "Pick any photo, and NameQuiz automatically detects faces so you can add names in seconds" — the only app found with (d) multiple people per photo via on-device face *detection*; 4-choice quizzes; local storage; privacy "Data Not Collected"; version history not shown — [App Store](https://apps.apple.com/us/app/-/id6751534335)

**18. Who is it? -Let's learn Name** — Shigeru Araki — https://apps.apple.com/app/id1506645361
- Free; Education; iOS 13.5+; v1.8 on 06/27/2023; manually crop a face from a camera photo or saved image, register name, birthday, phone, email, memo, birthday-month filter, tap-to-reveal name game; privacy label: Location, Identifiers, Usage, Diagnostics used to track you (ad SDK) — [App Store](https://apps.apple.com/app/id1506645361)

**19. NameMemory** — Tomohisa Kasami (KasamiWorks) — https://apps.apple.com/us/app/namememory/id6756201292
- Free; Pro $9.99 one-time (free limit 20 people); iOS 15.5+; 5.0 from 1 rating; v1.0.11 "3d ago" (≈Nov 2026). Deliberately uses built avatars (hair, eyes, glasses, beard) instead of photos "if your school or workplace bans personal phone photos"; tags by class/team/club/event; search matches cue words and meeting place; SM-2 spaced repetition quiz + type-the-name; "no cloud, no sync"; privacy "Data Not Collected" — [App Store](https://apps.apple.com/us/app/namememory/id6756201292)

**20. NameMatch: Remember Names** — Armando Jr Pagkalinawan — https://apps.apple.com/in/app/namematch-remember-names/id6774898292
- Free with ads, Pro lifetime ₹299; iOS 15.1+; v1.2 "30 Sept" (year inferred 2026). A *game* with 150 AI-generated faces ("do not depict real people"); cannot add your own people — not a personal store — [App Store](https://apps.apple.com/in/app/namematch-remember-names/id6774898292)

**21. Name Skillz: Remember Names** — Neuro Skillz / Solutioning Inc — https://apps.apple.com/us/app/id1409162011
- $4.99; iOS 8.0+; 4.4 from 31 ratings; v1.0.2 on 08/09/2023; teaches mnemonic technique with 200+ built-in names and "virtual people"; reviewers (2018, 2025) complain they cannot add real people/custom flashcards and that the app "crashes sometimes"/"needs an update" — [App Store](https://apps.apple.com/us/app/id1409162011)

#### Tier C — Name-notebook apps (text/location first; photo optional or absent)

**22. Name Reminder: Remember Names** ("Friend Keeper") — Digital Palette LLC — https://apps.apple.com/us/app/name-reminder-remember-names/id6450018987
- Free; IAP Pro Monthly $5.99, Pro Annual $34.99, "Friend Keeper Pro" $89.99 (description mentions $9.99 one-time, not in IAP list); iOS 17.6+; 4.6 from 8 ratings; v2.4 "Sep 3" (year inferred 2026) added iCloud sync (Pro), "Name that face"/"Match the face" practice, JSON backup restore; 2.3 (Aug 20) face-first flashcards with spaced repetition, quick add of name+photo, search across nicknames/kids/pets/jobs/notes, JSON export. Groups, spouse/kids/pets fields, birthday reminders. Privacy: Usage + Crash data not linked. Complaint (02/12/2025): lacked flashcard quiz (since added) — [App Store](https://apps.apple.com/us/app/name-reminder-remember-names/id6450018987)

**23. NameKeeper - Remember Names** — TeaCapps GmbH — https://apps.apple.com/us/app/namekeeper-remember-names/id1148776555
- Free; Pro $1.99; iOS 9.0+; 4.5 from 24 ratings; last update 1.2 on 05/29/2018 (abandoned). Quick name entry, auto-suggested current address via GPS, optional description and photo, add multiple names in one step, search/filter by name, description or address, offline, optional iCloud sync; privacy "No Details Provided". Complaints: no grouping/categories (2019, 2020), face thumbnails too small (2023) — [App Store](https://apps.apple.com/us/app/namekeeper-remember-names/id1148776555)

**24. Known Names: Remember Everyone** — Jubulah Labs / Jubulah LLC — https://apps.apple.com/us/app/-/id6751477026
- Free, no IAP; iOS 17.0+; 5.0 from 1 rating; v1.1.1 "Apr 10" (year inferred 2026), 1.0 on 12/17/2025; 24 languages; note name + workplace, hobbies, family, pets; search by name, workplace, where met, all fields; timeline of recent meetings; strong accessibility list (VoiceOver, Voice Control etc.); privacy: Usage Data not linked; no photo capture mentioned — [App Store](https://apps.apple.com/us/app/-/id6751477026)

**25. Appstar - Remember Names** — APPSTAR PTY LTD — https://apps.apple.com/us/app/appstar-remember-names/id1508216230
- $1.99 base plus $0.49 Quiz, Power Search and "All features" IAPs; iOS 13.0+; 5.0 from 1 rating; v1.3.2 "Sep 9" (year inferred 2026), 1.3.1 on 07/28/2024; profiles with photos, notes, birthdays, memorable facts; colour-coded tags; flashcards; paid quiz; follow-up Actions/agenda; "securely stored and synced to your account"; privacy links name/email/purchases to you — [App Store](https://apps.apple.com/us/app/appstar-remember-names/id1508216230)

**26. NameRoll – Name reminder** — Samuel Jusaitis — https://apps.apple.com/ee/app/nameroll/id1592445145
- Free; IAP Unlimited Groups €2.99, Unlimited Names €2.99; iOS 15.1+; v1.2.4 "11 Sept" (year inferred 2026); groups by where met, partner/pets/children/address/trivia fields, in-group and global search, iCloud sync (added 1.2.1, Apr), export/import since 1.0.8 (Oct 2023); no photo, no quiz described; privacy: crash data not linked — [App Store](https://apps.apple.com/ee/app/nameroll/id1592445145)

**27. NameMe - Remember Names** — Nichita Russu — https://apps.apple.com/us/app/id6761031851
- Free, no IAP; Utilities; iOS 15.0+; v1.0.7 "Oct 22" (year inferred 2026), 1.0 "Mar 25"; name + custom tags (appearance, personality, context), tag-based search, "Mutual Connections" linking; no photo/quiz mentioned; privacy "Data Not Collected" — [App Store](https://apps.apple.com/us/app/id6761031851)

**28. NameTag App** — Jason Price / Reason Creations LLC — https://apps.apple.com/us/app/id6739509205
- Free; Business; iOS 15.1+; no ratings, no version history shown; tag a name to a location, search/organize; no photo, voice or quiz mentioned; privacy "Data Not Collected" — [App Store](https://apps.apple.com/us/app/id6739509205)

**29. Nametag AI: Remember Names** — Rodrigo Gomez-Palacio / Honey Wolf LLC — https://apps.apple.com/us/app/nametag-ai-remember-names/id6794499133
- Free; IAP Pro Yearly $19.99; iOS 16.4+; 110 MB; no ratings; v1.0.0 "Sep 5", 1.0.1 "Sep 13", 1.0.2 "Oct 13" (year inferred 2026); also on Android — [App Store](https://apps.apple.com/us/app/nametag-ai-remember-names/id6794499133)
- Core: save names "by voice or typing", pinned to where you met; "tap, speak, save" with example "Mark, tall, glasses, plays Rugby" parsed by AI into descriptors, mutuals, fun facts; "Here now" view of people met at current location; search by name, place or mutual; "people flashcards" before an event; voice recording, automatic place recognition and smart search are Pro-only; cloud backup optional and off by default — [App Store](https://apps.apple.com/us/app/nametag-ai-remember-names/id6794499133); [nametagai.com](https://nametagai.com/); [chatgate.ai](https://chatgate.ai/post/nametag)
- Photos are not mentioned anywhere on the listing or website. Privacy label lists email, name, precise location, user content, IDs, purchases linked to you, despite the "data stays on your device" claim — [App Store](https://apps.apple.com/us/app/nametag-ai-remember-names/id6794499133)

**30. Namey ("Namie") – Your Social Memory Assistant** — William Misiaszek — https://apps.apple.com/pe/app/namey/id6449910626
- Free; iOS 14.0+; v1.4.1 on 12/11/2024; jot a name + memorable detail, location-based reminder pings when near where you met; live location sharing with friends; background location; privacy links precise location, address, email, name and Contacts to you; no photo/quiz mentioned — [App Store](https://apps.apple.com/pe/app/namey/id6449910626?l=en-GB)

**31. Connections: Remember People** — HEKSAKOD D.O.O.E.L. — https://apps.apple.com/us/app/id6575368930
- Free; $1.99/month or $19.99/year, 14-day trial; Social Networking; iOS 26.0+; 5.0 from 1 rating; v1.5.0 on 12/09/2025; event-based tagging, notes, "return to the date you met", search/filter by tags, iCloud Drive sync, Contacts import; no photo capture or quiz mentioned — [App Store](https://apps.apple.com/us/app/id6575368930) (borderline personal-CRM)

**32. Bename** — rwtemple.com — App Store page not located
- French directory lists it as free, iOS 18.6+, v1.3.2 dated 04/01/2026, location-based name recall with place tags, name suggestions while typing, reminders on return to a place; no photo mentioned — [iPhoneAddict](https://iphoneaddict.fr/apps/reseaux-sociaux/bename-remember-names.html). I could not find the apps.apple.com page by search; availability unverified.

#### Tangential (face recognition, but not for personal contacts)
- **Name Vision** — sVision Corporation — https://apps.apple.com/mw/app/name-vision/id1395206987 — free, iOS 11+, last update 2.1.4 on 08/09/2020; matches camera faces against 300+ historical/notable people, links to Wikipedia; users can add faces not in the database; privacy "No Details Provided" — [App Store](https://apps.apple.com/mw/app/name-vision/id1395206987)

### Inferences
- The market is fragmented among solo developers; version-history cadence suggests most "live" apps are side projects. Apps with the fullest feature set for the target workflow (in-app camera + name + notes + groups/tags + search) are PeopleRecall, Whodat?, Remember Names: Name Reminder and WhatsHisFaceAgain; only Whodat? also has an explicit date (calendar) browse.
- Many listings omit whether the camera can be opened in-app; "add photos" wording usually means Photos-library picker, so (a) should be verified by install for Remember Names: Name Reminder, WhatsHisFaceAgain, Remember Faces, NameDrill, FaceRecall, Friend Groups and Octoname.

### Gaps
- USD prices for Namester (SAR 4.99 shown) and NameMatch (₹299 shown) were not fetched from the US storefront.
- Version history is not shown on the listings for PeopleRecall's exact date format, Remember Faces, NameDrill, NameQuiz, NameTag App and WhatsHisFaceAgain, so their last-update dates are unknown.
- Reddit could not be searched (reddit.com is blocked for the search tool), so no community-sentiment threads are cited.
- No independent reviews from MacStories, iMore, 9to5Mac, Cult of Mac or Lifehacker were found for any of these apps in two targeted searches; only older roundups (Fox News, American Express OpenForum) mention Namerick.

## Key Question 2: Which candidate apps are still maintained vs. abandoned/defunct?

### Takeaway
Of the candidate names supplied, most either never existed as dedicated iOS apps under that name or have been pulled; Name Shark (2017), NameKeeper (2018), FaceCards (2017) are live but abandoned, while Namerick, Who's Who, Rememorate, Nameorize and Namerize are no longer on the App Store (or could not be found).

### Cited Findings
Status of supplied candidates:
- **Namerick** — described in press/roundups as an iPhone app using repetition and mnemonics, notes, categories (Work/Friend/Family) and spaced-repetition reminders ([Newswire press release](https://www.newswire.com/news/bad-with-names-finally-an-iphone-app-that-can-help-88687); [AmEx roundup](https://americanexpress.com/us/small-business/openforum/articles/8-apps-help-remember-peoples-names); [Fox News](https://www.foxnews.com/tech/3-everyday-useful-apps-to-download-today)). Three searches found no apps.apple.com listing; namerick.com returned HTTP 403 when fetched. Status: appears discontinued (unverified).
- **Who's Who: Remembering Names and Faces** — developer page still live with features (import from Contacts/LinkedIn/camera roll, spaced-repetition notification reminders, searchable detail fields, hint field for quiz) and links to App Store id972384752 ([shiresmith.github.io](https://shiresmith.github.io/projects/whos-who/)); that App Store ID returns 404 on both US and GB storefronts (fetched 2026-11-08). Status: removed from App Store.
- **Rememorate | Remembering Names** — Rememorate, LLC; released Aug 2018, last update Dec 12, 2024; "take a photo" as first step, business-card scan, search by photo/map location/date-time met/keywords, three memory games, Dropbox backup, Contacts sync; AppGoblin states it "was removed from the US App Store and is no longer live" ([AppGoblin](https://appgoblin.info/apps/1262203399)). US and MR/NP storefront pages returned 404; a DE listing with Networker/Socialite €10.99 subscriptions appeared in search but was not fetched ([search](https://apps.apple.com/de/app/rememorate/id1262203399)). Status: discontinued in US.
- **Name Shark** — live but last updated 12/20/2017; declares iOS 7.0 minimum; privacy label never supplied; 2025 reviewer says sharing is broken — [App Store](https://apps.apple.com/us/app/name-shark/id906531062). Status: abandoned but downloadable.
- **NameKeeper** — live, last update 05/29/2018 — [App Store](https://apps.apple.com/us/app/namekeeper-remember-names/id1148776555). Status: abandoned but downloadable.
- **FaceCards** — live, last update 05/15/2017 — [App Store](https://apps.apple.com/us/app/facecards-memorize-peoples-names/id1218293600). Status: abandoned but downloadable.
- **Nameorize - Remember Names!** (id662735152, 2013-era) — redirected URL returns 404 — [App Store](https://apps.apple.com/id/app/nameorize-remember-names/id662735152). Status: removed.
- **Namerize** (id6747360993) — search snippet described saving when/where you met someone and linking names to physical features and relationships, free with IAP ([search](https://apps.apple.com/ca/app/namerize/id6747360993)); US, CA and TO storefront pages all returned 404 on 2026-11-08. Status: appears removed.
- **names2faces** (id6762665278), **NUU PPL** (id1372622202), **WhosZat** (id1506398703), **Remet – Remember People** (id6757997989; snippet: quizzes on faces, import up to 10 photos at once) — all returned 404 on fetch. Status: unavailable/unverified.
- **Nametag** — two different live apps carry this name: "NameTag App" by Jason Price (location name-tagging, no photos) and "Nametag AI" by Honey Wolf LLC (voice capture) — see Q1 #28–29.
- **Faces** — a 2011-era MacRumors forum thread "Never forget a name or face by using Faces" exists but returned 403; no current App Store listing found ([MacRumors thread](https://forums.macrumors.com/threads/never-forget-a-name-or-face-by-using-faces.1168189)). Status: unverified, likely defunct.
- **Remember Me** — matched to "Remember Me - to learn names" (Benjamin Zaiser), live, v3.1.0 Aug 2024 — [App Store](https://apps.apple.com/qa/app/remember-me-to-learn-names/id1171353699).
- **Known** — matched to "Known Names: Remember Everyone", live, 2026 updates — [App Store](https://apps.apple.com/us/app/-/id6751477026).
- **Name Recall / FaceFile / Faceback / Face Memory / Memorize Names / NameTrix / People Keeper / Hello Again / Introduce / Humans / Remember Their Name / Namely / Reconnect / Nametagger / Monikers** — no App Store listing under these names surfaced in any of six searches; "Nametrix" and "Namely" results were baby-name apps ([search](https://apps.apple.com/us/app/id884932597)); closest matches are FaceRecall (Name Recall), FaceCards "Memorize People's Names", NameVault "Face & Name memory".
- **Humin** (2014 "social search engine" contacts app covered by VICE) was iOS, organized contacts by where/when met and required Facebook login — [VICE](https://www.vice.com/en/article/an-app-for-remembering-faces-if-you-meet-enough-people-to-forget-them). No current listing found.

Maintained within the last ~2 years (update dated 2025 or 2026 on listing): Remember Names: Name Reminder, NameVault, Whodat?, PeopleRecall, Known Names, Name Reminder (Digital Palette), NameRoll, NameMe, Nametag AI, FaceRecall, Friend Groups, NameMatch, NameMemory, Appstar, FaceTag, Octoname, Connections, Remember Names – FaceMemo (3.1 on 08/08/2025 — [App Store](https://apps.apple.com/us/app/remember-people-names-faces/id6480523691)), Faces2Know (Nov 2024), Remember Me (Aug 2024), Namey (Dec 2024).
Stale (no update in 2+ years): Name Shark (2017), FaceCards (2017), NameKeeper (2018), Name Vision (2020), Namester (Jan 2023), Who is it? (Jun 2023), Name Skillz (Aug 2023).

### Inferences
- Apple's periodic removal of outdated apps has probably already culled several candidates (Who's Who, Nameorize); Name Shark, FaceCards and NameKeeper survive but declare iOS 7–10 minimums and lack privacy labels, so they are at risk of removal and may misbehave on iOS 26.

### Gaps
- Could not confirm Namerick's removal date or developer statement (site blocked).
- Rememorate's status outside the US (DE listing) is unverified.

## Key Question 3: Which apps come closest to "open app → take selfie with person → type or speak name → later browse by name, date, or category"?

### Takeaway
No single app verifiably does every step. Whodat? (in-app photo, typed name, tags, calendar-by-date, voice search, on-device) and PeopleRecall (in-app photo, typed or dictated text, groups + tags, search, export) are the closest; Remember Names: Name Reminder is the most feature-rich and best-rated but does not state in-app camera capture or a date browse.

### Cited Findings
- Whodat?: photos saved per entry, search by name/company/place/tag, "calendar showing notes from each day", tags, conversation notes, map pins, voice search, spaced "Today's Review" — [App Store](https://apps.apple.com/us/app/whodat-remember-who-you-met/id6756264879)
- PeopleRecall: "photos can be taken directly in the app or uploaded", speech-to-text, groups and tags, key traits and notes, search by company/meeting place/interest/conversation, backup export — [App Store](https://apps.apple.com/us/app/id6746344227)
- Remember Names: Name Reminder: up to 10 photos per name, groups + nested subgroups, notes, "date added", search, iCloud sync, CSV/JSON export, three quiz modes, Apple Watch — [App Store](https://apps.apple.com/us/app/remember-names-name-reminder/id6504533632)
- NameVault: camera or Photos add, tap-to-name, quiz — but no groups/search/notes/date stated — [App Store](https://apps.apple.com/us/app/namevault-remember-face-name/id1525602410)
- FaceCards (2017): in-app photo, name, notes, GPS-tagged photos, spaced quiz; no groups/search — [App Store](https://apps.apple.com/us/app/facecards-memorize-peoples-names/id1218293600)
- Namester: "Enter the name and take a picture (right in the app)" then flashcards — [App Store](https://apps.apple.com/sa/app/namester/id6444921353)
- Who is it?: crop a face from a camera photo, name/birthday/memo, tap-to-reveal game — [App Store](https://apps.apple.com/app/id1506645361)
- Rememorate (removed in US): photo first, search by photo/location/date-time met/keyword — [AppGoblin](https://appgoblin.info/apps/1262203399)
- WhatsHisFaceAgain: photo, notes, where met, custom groups, search, iCloud; iOS 26.4+ — [App Store](https://apps.apple.com/app/id6770136593)

### Inferences
- "Browse by date photo taken" is essentially only served by Whodat?'s calendar (and Rememorate historically). Others expose at most a "date added" field or sort by due date.
- A selfie *with* the person (two faces in one frame) is a use case none of the listings address; only NameQuiz detects multiple faces in a picked photo.

### Gaps
- Hands-on verification of in-app camera flow and date-browse UI for the top apps was not possible from listing text.

## Key Question 4: Which apps offer voice input of names?

### Takeaway
Only Nametag AI explicitly offers spoken capture of the person's name/description (AI-parsed, voice recording is a Pro feature); PeopleRecall offers generic speech-to-text for notes; Whodat? offers voice *search* only. No photo-centric app pairs a camera capture with voice name entry.

### Cited Findings
- Nametag AI: "save names by voice or typing"; "voice capture with AI parsing"; voice recording, automatic place recognition and smart search are Pro-only ($19.99/yr) — [App Store](https://apps.apple.com/us/app/nametag-ai-remember-names/id6794499133); "tap, speak, save" example "Mark, tall, glasses, plays Rugby" — [nametagai.com](https://nametagai.com/)
- PeopleRecall: "speech-to-text" listed in V2 notes; notes "can be added by voice" — [App Store](https://apps.apple.com/us/app/id6746344227)
- Whodat?: voice input described for search — [App Store](https://apps.apple.com/us/app/whodat-remember-who-you-met/id6756264879)
- Remember Names: Name Reminder: records *pronunciation* audio of a name (playback aid, not speech-to-text); 5.15 converts a typed "short description" into suggested name/notes/groups — [App Store](https://apps.apple.com/us/app/remember-names-name-reminder/id6504533632)
- Known Names lists Voice Control (iOS accessibility) support, which is OS-level dictation/control, not an app feature — [App Store](https://apps.apple.com/us/app/-/id6751477026)

### Inferences
- Because iOS supplies system dictation in any text field, most apps rely on the keyboard mic rather than building a dedicated voice flow; only Nametag AI markets voice as the primary input.

### Gaps
- Nametag AI does not mention photos at all; whether a photo can be attached is unknown.

## Key Question 5: Do any apps do face recognition/matching, and have any been removed over Apple face-recognition/privacy rules?

### Takeaway
No live app in this niche offers face *matching* to identify a saved person later; the closest is NameQuiz's on-device face *detection* in group photos. I found no evidence that any name-memory app was removed for face-recognition reasons; Apple's documented enforcement (Clearview AI, 2020) was about enterprise-certificate misuse, and Guideline 5.1.2 bars using facial-mapping data to identify people.

### Cited Findings
- NameQuiz: "automatically detects faces so you can add names in seconds", group-photo detection, data local — [App Store](https://apps.apple.com/us/app/-/id6751534335)
- Name Vision (2020, stale): camera face matching against 300+ notable people, not personal contacts — [App Store](https://apps.apple.com/mw/app/name-vision/id1395206987)
- Every other listing reviewed (Remember Names: Name Reminder, NameVault, Whodat?, PeopleRecall, FaceCards, Name Shark, FaceRecall, etc.) describes manual tagging and manual recall quizzes; none claims recognition — e.g. [Whodat?](https://apps.apple.com/us/app/whodat-remember-who-you-met/id6756264879), [NameVault](https://apps.apple.com/us/app/namevault-remember-face-name/id1525602410)
- Apple App Store Review Guideline 5.1.2 (added Sept 2017) prohibits using "data gathered from... depth and/or facial mapping tools (e.g. ARKit, Camera APIs, or Photo APIs)" to identify anonymous users or reconstruct user profiles — [App Store Review Guidelines History](https://www.appstorereviewguidelineshistory.com/articles/2017-09-15-face-id-arkit-privacy-policies/)
- Apple disabled Clearview AI's developer account in Feb 2020 for violating enterprise developer agreement terms (app distributed outside the App Store to 2,200+ organizations) — [MacRumors](https://macrumors.com/2020/02/28/apple-disables-clearview-ai-dev-account); [AppleInsider](https://appleinsider.com/articles/20/02/28/apple-disables-facial-recognition-firm-clearview-ais-ios-app-for-violating-developer-rules)
- A developer-forum thread shows a 5.1.2 rejection for an app collecting data about third parties "without the knowledge or consent of those parties" (license plates), illustrating how Apple applies the third-party-consent rule — [Apple Developer Forums](https://developer.apple.com/forums/thread/116944)
- Rememorate's US removal is reported by AppGoblin without a reason — [AppGoblin](https://appgoblin.info/apps/1262203399)

### Inferences
- Developers in this niche appear to avoid face matching of real acquaintances, consistent with 5.1.2's third-party-consent and facial-mapping clauses; on-device detection (Vision framework) for cropping/tagging is the practical ceiling.

### Gaps
- No source attributes any specific name-memory app's removal to face-recognition policy; absence of evidence, not evidence of absence.

## Key Question 6: Ratings, review counts and notable complaints

### Takeaway
Review volumes are tiny across the category; the recurring complaints are data loss / failed sync when changing phones (Name Shark), ads persisting after purchase (NameVault), lack of grouping (NameKeeper), inability to add real people (Name Skillz), and privacy-label claims that contradict "on-device" marketing (Whodat?, Nametag AI).

### Cited Findings
- Name Shark 3.5★/160: lists did not transfer to a new phone despite paid sharing (2019, 2020), no support response, sharing broken and subscription un-renewable (09/08/2025) — [App Store](https://apps.apple.com/us/app/name-shark/id906531062)
- NameVault 4.9★/120: purchase not recognized, ads continued (11/28/2025); label shows third-party advertising tracking — [App Store](https://apps.apple.com/us/app/namevault-remember-face-name/id1525602410)
- Remember Names: Name Reminder 4.3★/24: no negative excerpts; confusing IAP tiers ($1.99–$79.99) — [App Store](https://apps.apple.com/us/app/remember-names-name-reminder/id6504533632)
- NameKeeper 4.5★/24: requests for groups/categories (2019, 2020); thumbnails too small (2023) — [App Store](https://apps.apple.com/us/app/namekeeper-remember-names/id1148776555)
- PeopleRecall 5.0★/24: all positive; developer warns it cannot restore lost data — [App Store](https://apps.apple.com/us/app/id6746344227)
- Name Skillz 4.4★/31: cannot add real people, crashes, "needs an update" — [App Store](https://apps.apple.com/us/app/id1409162011)
- Name Reminder (Digital Palette) 4.6★/8: earlier lack of quiz (02/12/2025), since added — [App Store](https://apps.apple.com/us/app/name-reminder-remember-names/id6450018987)
- Whodat?: label lists tracking identifiers/advertising data despite "stays on your device" description — [App Store](https://apps.apple.com/us/app/whodat-remember-who-you-met/id6756264879)
- Nametag AI: label links precise location, email, name, user content despite "data stays on your device" — [App Store](https://apps.apple.com/us/app/nametag-ai-remember-names/id6794499133)
- Who is it?: label says Location, Identifiers, Usage and Diagnostics are used to track you (ads) — [App Store](https://apps.apple.com/app/id1506645361)
- "Data Not Collected" labels: Remember Names: Name Reminder, Remember Faces, FaceTag, NameDrill, NameMemory, NameMatch, Namester, Faces2Know, Remember Me, Friend Groups, NameQuiz, NameMe, NameTag App, WhatsHisFaceAgain (each cited on its listing above).
- "No Details Provided" (never supplied a privacy label): Name Shark, FaceCards, NameKeeper, Name Vision (each cited above).

### Inferences
- Rating counts under ~30 for nearly every app mean star averages are not statistically meaningful; version-history cadence and privacy labels are better maintenance/quality signals.

### Gaps
- No Reddit or independent-press reviews could be retrieved for sentiment beyond App Store excerpts.
- Review counts for apps shown as "not enough ratings" are unknown (likely <5).
