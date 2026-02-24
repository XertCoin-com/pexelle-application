## Pexelle App – Changelog


### v2.0.1 - 2026-02-23

### New Features

#### Path Builder

- Introduced Path Builder, allowing users to create fully personalized learning paths by typing any topic.

#### Advanced Search

- Added enhanced Discover search with new behavior and filters.

- Introduced global search overlays, enabling users to search across multiple sections of the app simultaneously.

- Improved YouTube video search experience.

- Added loading indicators for video thumbnails.

#### Profile & CV Automation

- Added automatic profile completion from uploaded CV documents and images.

- Improved Share Profile UI and behavior. ([26ad593](https://github.com/XertCoin-com/mobile-app/commit/26ad593fe1a5dc6258065be7d97bb6a05d8202dc))

- Updated default sharing behavior: sharing is enabled by default and includes all public evidences.

#### Security

- Added App Lock, allowing users to secure the app using:

- Fingerprint

- Face recognition

- Device pattern

- Device passcode

#### UX & UI

- Updated application menus for better clarity and usability.

- Improved language selection screen.

- Introduced a new toast design across the app.

- Search feed UI now adapts dynamically when fewer results are available.

### Improvements

#### Profile & Forms

- Improved profile update speed and upload performance.

- Added comprehensive form validations:

- - Identity fields

- - Education and employment fields

- - Email and website fields (regex-based)

- Added the ability to remove previously entered dropdown values.

#### AI Assistant (Pexi)

- Improved AI assistant performance for user biography completion.

#### Notifications

- Improved notification handling and error guidance.

- Firebase push notifications optimized and unnecessary payloads removed.

- Improved message notification delivery and display behavior.

#### Performance & Backend

- Improved API endpoint performance.

- Reduced errors and instability across multiple endpoints.

- Improved cache management refresh behavior in Discover.

### Bug Fixes

#### Discover / Explore / Search

- Fixed Discover search not responding or requiring retry.

- Fixed missing "No results found" state.

- Fixed duplicate content appearing in Discover.

- Fixed incorrect like and comment counters.

- Fixed Explore crashes and infinite loading states.

- Fixed search failures in Assessments and Community sections.

#### Paths / Roadmaps

- Fixed issues in My Paths.

- Fixed screen rotation issues while working with Paths.

- Fixed Paths list appearing greyed out.

- Fixed roadmap icon and private evidence attachment issues.

#### Profile & Identity

- Fixed profile update issues and crashes.

- Fixed scrolling and jump issues in Identity screens.

- Fixed inability to clear dropdown selections.

- Fixed duplicated profile data rendering.

Improved shared education and employment thumbnail styling.

#### Attestation & Evidence

- Fixed attestation request button not being clickable.

- Fixed attestation flow when no attester is nearby.

- Fixed attesting without an attester.

- Fixed issues attaching private evidence.

- Fixed assessment loading failures.

#### Sharing & Deep Links

- Fixed deep link issues across multiple app sections.

- Fixed mainnet profile sharing deep link bug.

#### Permissions & Platform Issues

- Fixed crashes when changing app language.

- Fixed app crash on Android locale change.

- Fixed language not applying correctly after reopening.

- Fixed camera, gallery, and keyboard permission issues.

- Fixed QR scan permission handling.

- Fixed gallery not opening and camera not activating in scan flows.

- Fixed Firebase-related issues.

#### Notifications & Misc

- Fixed inconsistent notification refresh behavior.

- Fixed AI assistant related bugs.

- Fixed missing loading indicators during evidence deletion.

- Fixed keyboard not opening and improper keyboard handling.

- Fixed crashes related to multi-language usage.

#### Removed

- Removed Apply Job section.
