# AMBY: competitor user flows

A single-page site showing how AMBY's four closest competitors actually work: **Tandem Health, K Health, OpenEvidence and Epic AI**. It accompanies the AMBY competitive strategy deck.

For each company the page shows:
- what they have shipped recently (dated timeline)
- a step-by-step user flow built from the company's own product screens
- design patterns worth noting
- what it means for AMBY

It ends with a side-by-side comparison and six UI patterns AMBY should borrow.

## View it

- **Locally:** open `index.html` in a browser.
- **Online:** in the repo on GitHub, go to **Settings → Pages**, set *Source* to "Deploy from a branch", choose `main` and `/ (root)`, then save. The site will appear at `https://sally03-h.github.io/AMBY/`.

## Structure

```
index.html          the page (no build step, no dependencies)
assets/tandem/      Tandem product screens + scribe demo video (tandemhealth.ai)
assets/khealth/     PatientGPT animation (khealth.com) + HHC 24/7 app screens (App Store)
assets/openevidence/ App Store screens + announcement images (openevidence.com)
assets/epic/        AI Charting launch image + Art/Emmie/Penny marks (epic.com)
```

## Notes

- Each company section opens with **Watch the real product**: official demo videos (click to play) and real screens taken from them. YouTube videos play via youtube-nocookie embeds; OpenEvidence's walkthroughs stream from OpenEvidence's own server; most K Health videos are locked to khealth.com, so those cards link out.
- HHC 24/7 is Hartford HealthCare's app, built on K Health's platform. K Health doesn't publish screens of its clinician-side Provider Co-Pilot, so that step is described in text.
- Epic publishes few real screen recordings; the best are its AI Charting launch image (cropped into three flow steps) and its Microsoft Ignite 2025 segment.
- All screenshots, videos and logos belong to their respective companies and are used for internal competitive analysis.
