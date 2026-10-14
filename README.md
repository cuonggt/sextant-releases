# Sextant releases

Downloads and the Sparkle update feed for **Sextant** — a business's data warehouse native on the
Mac, with Claude as its analyst. The source lives elsewhere; this repository carries only the built
app and the feed that tells copies of it when there is a newer one.

- **Download** the latest DMG from [Releases](https://github.com/cuonggt/sextant-releases/releases).
- **The update feed** is [`appcast.xml`](appcast.xml), which the app reads at
  `https://cuonggt.github.io/sextant-releases/appcast.xml`.

Every build is signed with a Developer ID, notarized by Apple and stapled, and every appcast item
carries an EdDSA signature that the app checks before it will install anything.

Issues and questions: please use this repository's issue tracker.
