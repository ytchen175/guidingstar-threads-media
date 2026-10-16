# guidingstar-threads-media

Public image host for GuidingStar's official Threads account.

`threads/<date>/` holds the overview card, `manifest.json` (thread parts) and `posted.json` (published media ids) for one day. Files are written by `scripts/stage-threads-post.mts` and the `post_threads_official` workflow in the main repo; do not edit by hand.
