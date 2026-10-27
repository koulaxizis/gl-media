# gl-media

Public media host for the social scheduling of [Ανεξάρτητες Εκδόσεις Γλαρόλυκοι](https://glarolykoi.net).

Buffer publishes our TikTok and YouTube Shorts posts by fetching the video from a public, direct, stable HTTPS URL at publish time. This repo, served through GitHub Pages, provides those URLs.

## Layout

- `videos/YYYY-MM-DD_<slug>.mp4` — the 9:16 video of each social post (1080×1920, H.264/AAC).
- `.nojekyll` — serve files as they are.

Public URL pattern: `https://koulaxizis.github.io/gl-media/videos/<file>.mp4`

## Rules

- Only material that is published on our social channels anyway goes here. Nothing private, no source files.
- A video is deleted 30 days after its post was published (the routine that adds videos also removes expired ones).
- Files are added by the Instagram/TikTok routine of the Γλαρόλυκοι Project; no manual edits needed.

© glarolykoi.net
