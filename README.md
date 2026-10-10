# LexiRead CDN

Public distribution files for the LexiRead IELTS reading app.

- Article entry: `Cdn/content/latest.json`; versioned JSON contains 163 graded article variants.
- Android player 1.2.0 updates: `Cdn/code/1.2.0/Android/DefaultPackage.version`.
- Files are served through `https://hesu15121.github.io/lexiread-cdn/Cdn/`.

The Android app includes offline resources and verifies article size and SHA256 before activation.
GitHub Pages deploys main; verify the version entry and every resource after deployment.
Do not upload API keys, learner data, APKs, or Unity project caches to this repository.
Publish all new resources and manifests in one commit; preserve previously released bundles.
