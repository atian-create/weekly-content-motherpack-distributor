# Review And Release Contract

Use this reference when preparing a publish-ready weekly batch.

## Review Checks

For every platform version, check:

- title/platform fit
- reader pain and click reason
- image readiness
- public/private boundary
- risky claims
- missing files

For image packages, also check:

- image count
- dimensions if known
- whether images are final or only prompts
- whether any HTML screenshot or script rendering is being misrepresented as generated art

For WeChat public-account articles, also check:

- copy-ready HTML is treated as article layout only
- cover and in-article images exist as separate image files when images are promised
- the image pack has its own source notes or generation/design boundary
- HTML screenshots are not used as WeChat images unless the user explicitly requested screenshot-style images

If separate review agents or review threads are available, route text/HTML and images separately:

- text review: public Markdown, copy-ready HTML, title, risky claims, private-boundary checks
- image review: image pack existence, generation method, visual fit, dimensions, and HTML/script misuse

Release only when the required review sides pass. If an article has approved text but failed or missing images, keep it as `needs images` or `blocked`; do not mark it `ready`.

## Status Labels

Use simple labels:

| Status | Meaning |
| --- | --- |
| idea | selected but not drafted |
| draft | drafted but not reviewed |
| needs images | text is ready but images are missing |
| in review | waiting for final check |
| ready | publish-ready |
| blocked | missing input or failed review |
| skipped | intentionally not used |

## Release Page

If the user wants a dashboard, create a simple release page with:

- date anchors
- core delivery folders
- daily publishing entries
- platform sections
- copy buttons when practical

The release page should answer:

- What should be published on each day?
- Which folder contains images and captions together?
- Which podcast draft should be sent out?
- What is still missing?

## Delivery Folders

Recommended folder structure:

```text
weekly-content-pack/
  rednote-graphic-pack/
    YYYY-MM-DD-topic/
      images/
      caption.md
      caption.txt
  podcast-to-send/
    YYYY-MM-DD-topic.md
  wechat-image-pack/
    YYYY-MM-DD-topic/
      cover.png
      image-01.png
      image-02.png
  release-page.html
```

Keep public files clean. Do not include credentials, internal paths, internal thread IDs, or private notes in files meant to be shared.
