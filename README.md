# LexiRead CDN

Public distribution files for the LexiRead IELTS reading app.

- Article entry: `Cdn/content/latest.json`; versioned JSON contains 163 graded article variants.
- Android player 1.2.0 updates: `Cdn/code/1.2.0/Android/DefaultPackage.version`.
- Files are served through `https://cdn.jsdelivr.net/gh/hesu15121/lexiread-cdn@main/Cdn/`.

The Android app includes offline resources and verifies article size and SHA256 before activation.
Updates to the branch can take up to 12 hours to propagate through jsDelivr caches.
Do not upload API keys, learner data, APKs, or Unity project caches to this repository.
Publish all new resources and manifests in one commit; preserve previously released bundles.
