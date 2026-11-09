# AQ for Mac: downloads

Signed, notarized builds of the AQ Mac app. This repository holds release
files only; the source lives elsewhere.

- Download: https://aq.dev/download/mac (the newest `AQ.dmg`)
- Update feed (Sparkle): https://aq.dev/mac/appcast.xml

Each nightly is its own release (`nightly-<build>`) carrying `AQ.dmg`. The
`appcast` release holds `appcast.xml`, which points at the newest build. The
app checks it at launch and daily, and from AQ ▸ Check for Updates…

Published by CI. Do not upload files here by hand.
