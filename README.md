# Samguk Source Bank — source collection workspace

This repository contains the GitHub Actions workflow for collecting **10 pinned public upstream source archives** for the Samguk Jaengcheonrok (삼국쟁천록) Unity 6.3 LTS project.

- Upstream projects are not executed. They are downloaded, archive-validated and packaged.
- Sources may contain third-party art, audio and demos whose redistribution or commercial use must be checked independently.
- The archives remain separate from the game source. Do not automatically import all folders into Unity.
- See the **Actions** tab for `Samguk SourceBank — collect and verify`. A successful run publishes `Samguk-Full-SourceBank` as an artifact.
- Original GitHub commit hashes, license blob hashes, counts and byte lengths are locked in `tools/collect_sourcebank.py`.
- Never commit third-party archives or proprietary story files to this repository without a rights review.

**Important:** This repository is currently public. Switch to private under **Settings → General → Danger Zone → Change repository visibility** before uploading proprietary game assets.

This collector is a preparation step. It does **not** certify Unity 6.3 compatibility or game-release rights for each included asset.
