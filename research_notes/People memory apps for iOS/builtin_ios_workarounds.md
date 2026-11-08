# Built-in iOS / Apple-ecosystem (and Google Photos) workarounds for "selfie + name now, browse by name/date/category later"

Scope note: iPhone-focused, iOS 18 / iOS 26 era, as of 2026-11-08. Apple's live user-guide pages now default to iOS 27, and several Apple support pages returned only tables of contents when fetched, so a number of fine-grained UI steps below come from third-party how-tos and community threads rather than Apple's own text. Each finding is marked **[Apple doc]**, **[third-party/how-to]**, **[community/anecdotal]**, or **[inferred]**.

## Key Question 1: Can Apple Photos face naming be done right after the shot, or only after background indexing? How long does indexing take? Does naming a face create/require a Contact?

### Takeaway
Apple documents two naming paths (from a single photo via the Info panel, or from the People & Pets collection), and names are *suggested* from Contacts but are stored as Photos data, not as a Contact. Apple does not publish any timing guarantee for face detection; community reports range from "little by little" to weeks for large libraries, and the Info-panel "face with a question mark" only appears once the device has detected the face, so immediate naming right after the shutter is not guaranteed.

### Cited Findings
- **[Apple doc]** Naming from a photo: "Open the photo and tap the Info button. Tap the face with a question mark, then tap Edit Name and Photos. Tap Name This Person or Name This Pet, then type a name or tap a suggested one. If the person or pet was already recognized, tap Merge Photos. Tap Done, then tap Done again." — [Apple Support 108795, Find People and Pets in Photos](https://support.apple.com/en-us/108795)
- **[Apple doc]** Naming from the collection: "Open the People & Pets collection and tap the thumbnail. Tap Name This Person, then type or select a name. Tap Done." — [Apple Support 108795](https://support.apple.com/en-us/108795)
- **[Apple doc]** Photos "suggests names from your Contacts." The page does not say naming creates a contact. — [Apple Support 108795](https://support.apple.com/en-us/108795)
- **[third-party/how-to]** Cult of Mac confirms you can type a Contacts name to match, "You can also enter a custom name if the person isn't in Contacts." — [Cult of Mac, How to tag photos on iPhone](https://www.cultofmac.com/how-to/tag-photos-iphone)
- **[Apple doc]** Where to find it: "Open Photos, tap Collections, swipe up, then tap People & Pets. If no pets are identified, the collection is labeled People." Named people can be found "by tapping the Search tab and typing their name." — [Apple Support 108795](https://support.apple.com/en-us/108795)
- **[Apple doc]** Pets (dogs and cats) are recognized in iOS 17 / iPadOS 17 or later. — [Apple Support 108795](https://support.apple.com/en-us/108795)
- **[Apple doc]** "With iCloud Photos on, the people you favorite or name stay up to date across your Apple devices." — [Apple Support 108795](https://support.apple.com/en-us/108795)
- **[Apple doc]** Fixing errors: in a person's collection, Select wrong photos > More > "This is Not [This Person]"; merging via People & Pets > Edit > select > More > Merge > Merge Photos; "Don't Feature [Name]" with "Feature This Person Less" / "Never Feature This Person." — [Apple Support 108795](https://support.apple.com/en-us/108795)
- **[Apple doc]** The Apple support page lists no processing conditions (locked/charging) and no indexing time. — [Apple Support 108795](https://support.apple.com/en-us/108795)
- **[community/anecdotal]** Apple Community: "If you're using Low Power Mode, it can pause iCloud Photo uploads and prevent the People & Pets album from updating"; "Insufficient storage space on your iPhone can also impact the processing of the People & Pets album"; the album "may take time to fully update after a new photo library is created or after a reset"; one user reported no change after a month, another no updates for months on iPad. — [Apple Community thread 256039283](https://discussions.apple.com/thread/256039283)
- **[community/anecdotal]** One user with ~50,000 items reported roughly two weeks to finish scanning; another MacRumors post says iOS suggests locking the iPhone and connecting it to power to finish the remaining scan. — [MacRumors forums, getting the People album to scan remaining photos](https://forums.macrumors.com/threads/getting-the-people-album-to-scan-remaining-photos.2356633); [Apple Community 255917305](https://discussions-jp-prz.apple.com/thread/255917305)
- **[third-party/how-to]** Cult of Mac: an unidentified face "only appears as a person in People & Pets after many photos of them are found over time," and after resetting a face "it may take about a day" to reprocess. — [Cult of Mac](https://www.cultofmac.com/how-to/tag-photos-iphone)
- **[community/anecdotal]** A recent Apple Community thread titled "Photo app not recognizing all people's faces even when there's clear faces on the pictures" shows detection misses are a live complaint in the iOS 26 era. — [Apple Community 256221028](https://discussions.apple.com/thread/256221028)
- **[community/anecdotal]** An AppleVis user reported that in iOS 26 the naming option moved (found under Edit > more > Markup in their experience) — single report, unverified. — [AppleVis comment 196796](https://applevis.com/comment/196796)
- **[Apple doc]** Privacy: Photos "uses on-device analysis to recognize the faces of people in photos"; when you add a name, "their name and face will appear in Photos across all your iCloud-enabled devices"; iCloud encrypts photos and metadata in transit and at rest; Apple "does not access your photos or videos." The page does not use the term end-to-end encryption for face data. — [Apple, Photos & Privacy](https://www.apple.com/legal/privacy/data/en/photos/)
- **[news]** An Illinois BIPA suit report states that for iCloud Photos users, face crops and some metadata including user-supplied labels are uploaded to Apple's servers "in an end-to-end encrypted format," a claim the plaintiffs dispute; the court found E2E encryption does not stop Apple being in "control" of synced data. — [PPC Land, Apple loses bid to end Illinois suit over faceprints](https://ppc.land/apple-loses-bid-to-end-illinois-suit-over-faceprints-in-iphone-photos/)

### Inferences
- **[inferred]** Because the Info-panel path depends on "the face with a question mark" already being present, immediate naming works only if on-device face detection has already run on that photo. Users report new photos usually get a face box fairly quickly on modern iPhones, but Apple makes no commitment, so a "name it right now" flow is unreliable, especially under Low Power Mode or low storage.
- **[inferred]** Naming a face is a Photos-library label; it is suggested from Contacts but does not create a Contact. There is no bidirectional link (adding a Contact does not tag photos; naming a face does not store the photo on the Contact card).
- **[inferred]** Face data is on-device analysis; with iCloud Photos on, names (and per the lawsuit reporting, face crops) sync to Apple servers under iCloud encryption. For a privacy-sensitive user, "on-device only" is true only when iCloud Photos is off.

### Gaps
- No Apple-published figure for how long detection of a newly taken photo takes; only anecdotal library-wide scan durations exist.
- Apple's iOS 26-specific user-guide text for People & Pets could not be fetched (pages redirect to the iOS 27 table of contents), so the exact iOS 26/27 button labels could not be verified beyond the 108795 article.
- Could not verify whether there is any hard limit on number of named people or on multi-face handling beyond the documented per-face Info panel.

## Key Question 2: Photos captions/keywords, smart albums, and the iOS 18 / iOS 26 redesign (Collections, Pinned, Utilities) as a categorization tool

### Takeaway
Captions (iOS 14+) are the only free-text metadata field on iPhone and are searchable, so they double as keywords; there is no keyword field or Smart Album on iOS (Smart Albums are Mac-only). iOS 26's Photos splits into Library and Collections tabs, where People & Pets, Albums, Pinned and Utilities live, so "categories" must be hand-built as albums.

### Cited Findings
- **[third-party/how-to]** Add a caption: open the photo, swipe up, enter text in "Add a Caption"; available on iOS 14 or newer; search by typing caption words in the Search tab; captions sync via iCloud Photos. — [iPhone Life, How to Add a Caption to a Photo on iPhone](https://iphonelife.com/node/277553); [iPhone Life, Search with Photo Captions](https://iphonelife.com/node/277889)
- **[community/anecdotal]** Apple Community user: put search terms at the beginning of the caption or they may not get indexed (single report). — [Apple Community 255721593](https://discussions.apple.com/thread/255721593)
- **[community]** Apple Community user asks why iOS has a "caption" and "add a location" field but no "keywords" field — confirms no keywords field on iPhone. — [Apple Community 255398200](https://discussions-jp-prz.apple.com/thread/255398200)
- **[Apple doc]** iOS 26 Collections: "tap Collections, then tap Pinned"; default Pinned Collections are Favorites, Recently Saved, Map, Videos, Screenshots; Edit lets you add "Any Collection or Album" (examples: Recently Deleted, Selfies, Receipts, custom albums), remove, and drag to reorder; Albums via Collections > Albums; Media Types (Videos, Selfies) via Collections > Media Types; Utilities (Recently Deleted, Hidden) via Collections > Utilities; reorder Collections at the bottom via Reorder. — [Apple Support 121870, Find your Favorites and albums in Photos](https://support.apple.com/121870)
- **[third-party]** iOS 26 default Collections order: Memories, Pinned, Albums, People & Pets, Featured Photos, Shared Albums, Recent Days, Trips, Media Types, Utilities, Wallpaper Suggestions, Reorder. — [AppleInsider, Photos iOS 26 vs iOS 18](https://appleinsider.com/inside/ios-26/vs/photos-ios-26-vs-ios-18-small-changes-huge-impact)
- **[third-party]** iOS 26 gives Collections its own tab instead of the single-scroll iOS 18 view. — [switchingtomac, Collections/Albums/People & Pets explained](https://www.switchingtomac.com/iphone-photos-organization-collections-albums-favorites-people-pets/)
- **[Apple doc]** Mac Photos lets you name people directly from a photo or in People & Pets. — [Apple Photos for Mac guide](https://support.apple.com/guide/photos/phtad9d981ab)
- **[third-party]** A "Selfies" media type exists and can be pinned. — [Apple Support 121870](https://support.apple.com/121870)

### Inferences
- **[inferred]** A practical "category" scheme on iPhone is: caption with hashtag-like tokens (e.g., "#conference Jane Doe") plus a manual album per category; pin the album(s) and People & Pets in Pinned Collections for one-tap browsing. Browsing by date is inherent (Library grid; "Recent Days"), by name via People & Pets or Search, by category via albums or caption search.
- **[inferred]** Smart Albums are not available on iOS (only on Mac), so no automatic "all photos captioned #work" album exists on iPhone; Search is the substitute.

### Gaps
- No Apple support page found that documents the caption field on iPhone (only third-party guides); the caption-indexing quirk is a single-user report.
- Could not confirm whether iOS 26 search handles caption text plus person name in a combined query reliably.

## Key Question 3: Apple Contacts as the store (camera photo, notes, lists, Contact Posters, browse by date added)

### Takeaway
Contacts can hold a camera-taken photo and free-text notes, and Lists give manual categories, but Apple's iPhone guide text could not be retrieved to verify the exact current steps, and nothing found suggests Contacts can be sorted or browsed by date added.

### Cited Findings
- **[Apple doc, TOC only]** The Contacts user guide lists topics "Add or change contact pictures" and "Create and change lists and Smart Lists" (Mac guide). — [Apple Contacts User Guide TOC](https://support.apple.com/en-gw/guide/contacts/toc)
- **[Apple doc]** On iCloud.com, new contacts go into All Contacts, you can create lists, a contact can be in more than one list, deleting a list leaves contacts in All Contacts; add a photo via Add Photo. — [Apple iCloud User Guide, lists](https://support.apple.com/en-au/guide/icloud-web-only/mmfba737da/icloud)
- **[third-party]** On iPhone, tap the photo area to add a picture; groups/lists can be created and contacts added. — [Support.com how-to](https://www.techsolutions.support.com/how-to/how-to-add-contacts-on-iphone-ipad-or-ipod-touch-12477)
- **[third-party]** Contact Posters are set from My Card > Contact Photo & Poster; posters can be created for other people too; require iOS 17+. — [Make Tech Easier, Contact Posters](https://maketecheasier.com/set-up-contact-posters-iphone); [iPhone Life, Contact Poster](https://app.iphonelife.com/content/create-and-customize-contact-poster)
- **[Apple doc]** Shortcuts' Add to Contacts action "requires a first and last name"; the Apple page sets First Name, Last Name, Phone Number and mentions turning off Show Compose Sheet; it does not document a Photo or Notes parameter. — [Apple Shortcuts guide, Create contacts](https://support.apple.com/guide/shortcuts/create-contacts-apd9cf19a736/ios)
- **[third-party]** Contacts has Phonetic First/Last Name fields that help Siri recognize and pronounce names. — [Macworld, phonetic name field](https://www.macworld.com/article/1677730/how-to-siri-pronounce-names-contacts-app-phonetic-name-field.html)

### Inferences
- **[inferred]** Contacts covers "photo + name + category (List) + notes" in one record, and Siri can create a contact by voice, but it has no date-based browsing, so "who did I meet last week?" is not answerable from Contacts alone; the Photos date of the selfie would have to serve.
- **[inferred]** Smart Lists (criteria-based) appear in the Mac Contacts guide TOC; whether they exist on iPhone was not confirmed.

### Gaps
- Apple's iPhone-specific "Add and use contact information" page returned only the guide TOC on fetch; steps for Take Photo vs Choose Photo during contact creation, and current Lists UI, are unverified from Apple text.
- No source found on sorting Contacts by creation date (likely not possible, but unverified).

## Key Question 4: Apple Journal (iOS 17.2+) as a fit

### Takeaway
Journal adds photos and surfaces people-related suggestions, and iOS 18 added text search and a calendar/Insights view, but it has no tags, no people filter, and users report search unreliability; it is a diary, not a people index.

### Cited Findings
- **[news]** Journal shipped with iOS 17.2 (Dec 2023); suggestions are "intelligently curated from a user's recent activity, such as photos, people, places, and workouts." — [9to5Mac, iOS 17.2 Journal app](https://9to5mac.com/2023/12/11/ios-17-2-includes-all-new-journal-app-heres-how-it-works/)
- **[news/review]** At launch there was no search, no tags, no folders; filters only by media type (photos, places, bookmarks). — [AppleInsider, How to use Journal in iOS 17.2](https://appleinsider.com/inside/ios-17/tips/how-to-use-the-new-journal-in-ios-172-and-where-it-needs-work); [MacStories, Apple's Journal App review](https://www.macstories.net/reviews/apples-journal-app-journaling-for-all/)
- **[review]** iOS 18: "find past entries by typing text or selecting a supported category"; Insights view with streaks and a monthly calendar to browse entries by type, date, or place; "Always Use Moment Date" sets entry date to the photo's date; audio transcription; export/print. Journal remained iPhone-only in iOS 18. — [MacStories, iOS 18 review p.7](https://www.macstories.net/stories/ios-and-ipados-18-the-macstories-review/7)
- **[news]** Journal arrived on iPad and Mac with iPadOS 26 / macOS Tahoe. — [9to5Mac Apple Journal guide](https://9to5mac.com/guides/apple-journal)
- **[community/anecdotal]** Users report search broken after iOS 18.2 and, on iOS 18.5, "doesn't work for anything more than a few weeks ago." — [Apple Community 256010028](https://discussions.apple.com/thread/256010028); [Apple Community 256062485](https://discussions.apple.com/thread/256062485)

### Inferences
- **[inferred]** Journal can hold "selfie + typed name + where we met" as an entry dated to the photo, browsable by date via Insights calendar and searchable by typed name (iOS 18+), but there is no people-based filter and no category/tag system, so category browsing must be faked with search keywords in the text.

### Gaps
- Apple's Journal user guide for iOS returned 404 / Mac-only TOC, so Apple's own description of search filters on iOS 26 is unverified.
- No source confirms whether Journal's "people" suggestions use Photos face names or just Contacts/Messages activity.

## Key Question 5: Apple Notes with photos, tags and Smart Folders

### Takeaway
Notes is the most flexible built-in categorizer: a note can hold a camera photo, a typed or dictated name, and #tags; Smart Folders filter by tags and by created/edited date, giving name (search), date, and category browsing in one app, at the cost of no face recognition.

### Cited Findings
- **[Apple doc]** Add a tag by typing # followed by a continuous word (hyphens, numbers, underscores allowed), then space/Return; tags require iOS 15 or later. — [Apple Support 102288, Tags and Smart Folders in Notes](https://support.apple.com/en-us/102288)
- **[Apple doc]** Create a Smart Folder: New Folder > name > "Make Into Smart Folder" > choose filters > checkmark; filters include tags, "when a note was created, when it was last edited, and more"; existing folders can be converted (irreversible; not shared folders, folders with subfolders, or folders with locked notes). — [Apple Support 102288](https://support.apple.com/en-us/102288)
- **[Apple doc]** Tags browser below the Folders list; select two or more tags to show notes containing all or any of them; batch-tag notes via Select Notes > Tags. — [Apple Support 102288](https://support.apple.com/en-us/102288)
- **[Apple doc, Mac]** Mac Smart Folder filters include tags, mentions, date created/edited, locked, pinned, Quick Notes, "and more." — [Apple Notes Mac guide](https://support.apple.com/en-la/guide/notes/apdc88ed7f1d/4.9/mac/12.0)

### Inferences
- **[inferred]** A Notes-based flow: Notes > new note > camera button > Take Photo > type/dictate "Jane Doe #conference". Browse by category via tag browser or a Smart Folder per tag; by date via sort or a date-filtered Smart Folder; by name via Notes search. This is roughly 6-8 taps plus typing, and can be shortened by a Shortcut (see Q6).

### Gaps
- Apple's iPhone page does not enumerate every Smart Folder filter (e.g., "has attachments"); inferred from the Mac page.

## Key Question 6: Shortcuts recipe (camera > name by typing or voice > save), triggers, and known shared shortcuts

### Takeaway
All building blocks exist as native Shortcuts actions (Take Photo, Ask for Input, Dictate Text, Save to Photo Album, Create Note, Add New Contact), and the shortcut can run from the Action button, Lock Screen, Control Center or Siri. The hard gap is that no documented Shortcuts action sets a Photos caption or a People name on the saved photo, and no widely shared "remember this person" shortcut was found on RoutineHub or r/shortcuts.

### Cited Findings
- **[third-party action directory]** Take Photo: "Uses the camera to take photos"; parameters Number of photos (default 1), Camera (back/front), Show Camera Preview toggle; no input; outputs Images. With preview off it takes only one photo. — [Matthew Cassinelli, Take Photo action](https://matthewcassinelli.com/actions/take-photo/)
- **[Apple doc]** Save to Photo Album adds photos to a chosen album in the Photos app. — [Apple Shortcuts guide, share actions](https://support.apple.com/guide/shortcuts/apdaf74d75a5); [Cassinelli, Save to Photo Album](https://matthewcassinelli.com/actions/save-to-photo-album/)
- **[Apple doc]** Add to Contacts "requires a first and last name"; compose sheet can be hidden. — [Apple Shortcuts guide, Create contacts](https://support.apple.com/guide/shortcuts/create-contacts-apd9cf19a736/ios)
- **[community]** Dictate Text action has a Stop Listening setting: After Pause, After Short Pause, On Tap; one iOS 17 user reported On Tap behaving like After Pause; another reported Siri-launched runs truncating dictation (iOS 16.2). — [Apple Community 255582634](https://discussions.apple.com/thread/255582634); [Apple Community 253352290](https://discussions.apple.com/thread/253352290)
- **[third-party]** A shared "Capture a dictation" shortcut dictates until tapped to stop and then shows the Share sheet. — [Cassinelli, dictation folder](https://matthewcassinelli.com/shortcuts/folders/productivity/text/dictation/)
- **[Apple doc]** Shortcuts can be run with the Action button. — [Apple Shortcuts guide, Run shortcuts with the Action button](https://support.apple.com/guide/shortcuts/run-shortcuts-with-the-action-button-apdfea15680b/ios)
- **[developer forum]** A July 2023 Apple Developer Forums post asking how to add keywords/captions to newly taken photos via Shortcuts has zero replies. — [Apple Developer Forums thread 734360](https://developer.apple.com/forums/thread/734360)
- **[search result]** Searches for a RoutineHub or r/shortcuts "take photo + name + save contact/caption" shortcut returned only App Store apps (Name Reminder, Remember Names, Known Names, Quickness) and no shared shortcut; RoutineHub's search page returned HTTP 403 on fetch. — [App Store, Quickness: Add Contacts (works with Shortcuts)](https://apps.apple.com/us/app/quickness-add-new-contacts/id1449776813); [App Store, Known Names](https://apps.apple.com/us/app/-/id6751477026)
- **[third-party]** Existing shortcut tutorials pair Take Photo with OCR/Live Text or with ChatGPT captioning, not with people naming. — [Fstoppers, iOS shortcuts for photographers](https://fstoppers.com/mobile/five-exclusive-ios-shortcuts-every-photographer-needs-and-how-use-them-720359)

### Inferences
- **[inferred]** Feasible native recipe (no third-party apps): Take Photo (front camera) > Ask for Input (text) or Dictate Text > Save to Photo Album "People I Met" > Create Note with the photo and "Name #category" text (Notes action supports attachments) and/or Add New Contact with first/last name split from the text. Trigger via Action button or a Lock Screen/Control Center shortcut control. Estimated 2-3 taps plus speaking/typing after trigger.
- **[inferred]** Because no Shortcuts action writes the Photos caption or People name, the shortcut cannot make the saved selfie searchable by name inside Photos; name retrieval must go through Notes/Contacts, or via the album name/date correlation. Overlaying the name onto the image (Overlay Text action) is a possible but lossy workaround.
- **[inferred]** The Add to Contacts first+last name requirement means single-name entries ("Jane") need a placeholder last name.

### Gaps
- No Apple documentation page for the Take Photo or Dictate Text actions was found; parameters come from a third-party action directory.
- Whether the Add to Contacts action accepts a Photo parameter on iOS 26 is undocumented on Apple's page (Cassinelli's directory was not fetched for that action).
- No shared shortcut for this exact flow was located; RoutineHub could not be searched (403).

## Key Question 7: Google Photos on iOS as an alternative

### Takeaway
Google Photos offers face grouping with private name labels, name search, and albums as categories, but it is cloud-based, not available in all regions or account types (notably off in Illinois and Texas), and Google itself says face models "may be considered biometric data."

### Cited Findings
- **[Google doc]** iPhone: profile > Google Photos settings > Privacy > turn on Face Groups; name via Collections > People & pets > tap a face > Add a name; "only you can see the private face labels you create, even if you share the photos." — [Google Photos Help, Face grouping (iOS)](https://support.google.com/photos/answer/6128838?co=GENIE.Platform%3DiOS)
- **[Google doc]** Face grouping "isn't available in all geographic regions, all domains, or all account types"; People & pets section may be missing where unavailable; labeling individual photos "isn't available in all countries"; face models "may be considered biometric data in some jurisdictions"; turning off Face Groups deletes models, groups and labels; models kept until deleted or account inactive two years; grouping may also use time and clothing; merges cannot be undone. — [Google Photos Help, Face grouping](https://support.google.com/photos/answer/6128838)
- **[news]** Google confirmed Face Groups are not available in Illinois and Texas; Ask Photos and conversational editing depend on Face Groups and so are also unavailable there; reporters link this to BIPA and the Texas biometric law and Google's 2022 settlements. — [9to5Google, Ask Photos not available in some states](https://9to5google.com/2025/10/16/google-confirms-ask-photos-isnt-available-in-some-states); [Engadget](https://www.engadget.com/ai/googles-ask-photos-feature-isnt-available-in-texas-and-illinois-200536477.html)
- **[news]** Face grouping rolled out to Europe only in 2019 after earlier legal concerns. — [Android Police, face grouping Europe](https://www.androidpolice.com/2019/08/22/google-photos-face-grouping-europe/)

### Inferences
- **[inferred]** Google Photos does not let you name a face at capture time either; the photo must back up and be processed in the cloud first. Albums serve as categories; search by name/date works once labeled.
- **[inferred]** Google's help page does not state on-device vs cloud processing, but because grouping is tied to the account and to regional legal availability, processing is server-side; this is a privacy trade-off versus Apple's on-device analysis.

### Gaps
- No processing-latency figure for Google face grouping on new uploads.
- Google's official list of excluded regions is not published; Illinois/Texas confirmed via press.

## Key Question 8: Voice input reliability (Siri dictation for names; Live Captions / Voice Memos as alternatives)

### Takeaway
iOS Dictation handles unknown proper names unpredictably and biases toward names already in Contacts; there is no user-editable dictionary. Adding the person to Contacts (or a "fake contact") is the documented community workaround; a typed fallback is advisable.

### Cited Findings
- **[expert blog, 2026]** TidBITS (15 May 2026): Dictation recognizes names not in Contacts unpredictably; Contacts names often override similar-sounding common words ("ride" became "Ryd"); Apple provides no user-editable word list; creating "fake contacts" for special terms improves recognition, some immediately, some after corrections; "wrong words will still appear some of the time." — [TidBITS, How Fake Contacts Can Fix Dictation's Proper Noun Problems](https://tidbits.com/2026/05/15/tipbits-how-fake-contacts-can-fix-dictations-proper-noun-problems/)
- **[third-party]** Contacts Phonetic name fields improve Siri's recognition/pronunciation; dictation learning and Siri recognition are separate systems. — [Macworld, phonetic name field](https://www.macworld.com/article/1677730/how-to-siri-pronounce-names-contacts-app-phonetic-name-field.html); [CyberGuy, stop Siri misspelling names](https://cyberguy.com/iphone/stop-siri-misspelling-names/)
- **[community]** Reports of dictation failing to type contact names after a 2023 update, and of declining accuracy for non-English names (2025, thread closed without fix). — [Apple Community 254787717](https://discussions.apple.com/thread/254787717); [Apple Community 256056211](https://discussions.apple.com/thread/256056211)
- **[review]** Journal in iOS 18 added audio transcription for voice notes. — [MacStories iOS 18 review](https://www.macstories.net/stories/ios-and-ipados-18-the-macstories-review/7)

### Inferences
- **[inferred]** For a name you just heard, dictation will often misspell it; the most reliable voice flow is dictate, then show the text for one-tap correction before saving (Shortcuts "Ask for Input" with default value set to the dictated text).
- **[inferred]** Voice Memos transcripts (iOS 18+) and Journal audio transcription suffer from the same proper-noun weakness, so they are not better alternatives for capturing a name.

### Gaps
- No Apple documentation found on dictation accuracy for proper nouns; all sources are community/expert blogs.
- Live Captions as a name-capture tool: no relevant source found.

## Key Question 9: Fastest built-in path and hard limitations that justify a dedicated/custom app

### Takeaway
The fastest fully-native path is a Shortcut on the Action button (about 2-3 taps plus speaking), but it cannot write a name into Photos' People index, so name-based browsing of the selfie requires a second app (Notes/Contacts). Photos' People & Pets gives name browsing but only after unguaranteed face detection, has no category system, and faces that are not detected cannot be named.

### Cited Findings
- **[third-party/how-to]** Naming via People & Pets takes three taps plus typing; the single-photo route is a swipe plus two taps plus typing; unidentified faces may appear only after many photos over time. — [Cult of Mac](https://www.cultofmac.com/how-to/tag-photos-iphone)
- **[Apple doc]** Face naming requires tapping "the face with a question mark" in the Info panel, i.e., a detected face. — [Apple Support 108795](https://support.apple.com/en-us/108795)
- **[Apple doc]** Pinned Collections can hold People & Pets-adjacent items and custom albums for one-tap access. — [Apple Support 121870](https://support.apple.com/121870)
- **[Apple doc]** Notes Smart Folders filter by tag and created/edited date. — [Apple Support 102288](https://support.apple.com/en-us/102288)
- **[developer forum]** No answer exists for setting captions/keywords from Shortcuts. — [Apple Developer Forums 734360](https://developer.apple.com/forums/thread/734360)
- **[App Store]** Several third-party apps (Name Reminder, Remember Names, Known Names, Quickness) exist specifically for this niche, indicating the built-in gap. — [App Store, Name Reminder](https://apps.apple.com/us/app/-/id6450018987); [App Store, Known Names](https://apps.apple.com/us/app/-/id6751477026)

### Inferences
- **[inferred]** Tap-count comparison (estimates, not measured): Photos-only: open Camera (1), shoot (1), open photo (1), Info (1), tap face (1), Edit Name (1), type name (typing), Done x2 (2) = roughly 8 taps plus typing, and only if the face is already detected; adding a category means another 3-4 taps to add to an album or caption. Shortcut on Action button: press (1), shoot (1), speak or type name (1-2), optional category menu pick (1) = roughly 3-5 taps.
- **[inferred]** Hard limitations of the built-in stack: (a) no API/action to set Photos People names or captions; (b) face naming blocked until detection, which Apple does not time-bound; (c) no categories/tags in Photos People & Pets; (d) the data is split across Photos (face, date), Contacts (name, list), Notes (tag, note), with no single browse view; (e) dictation of unfamiliar names is unreliable; (f) Google Photos adds cloud/biometric privacy and regional availability constraints. A custom app using the Vision framework and PhotoKit (or its own store) can name at capture, keep tags, and browse by name/date/category in one place.

### Gaps
- Tap counts are estimates from documented steps, not timed trials.
- No source compared these built-in workflows head-to-head; the comparison is this researcher's synthesis.
