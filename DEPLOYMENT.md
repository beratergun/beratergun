# SBE GitHub Motion Pack

## Deployment

1. Open `https://github.com/beratergun/beratergun`.
2. Upload **README.md** to the repository root, replacing the existing file.
3. Upload `assets/sbe-hero.gif`, `assets/sbe-hero-preview.png`, `assets/active-workstreams.gif`, `assets/active-workstreams-preview.png` into the existing `assets` folder.
4. **Do not remove** the already-existing `assets/system-matrix.svg`, `assets/telemetry-console.svg`, `assets/cyber-banner.svg` and other assets.
5. Check the rendered profile on desktop and mobile. GitHub may cache images temporarily.

## Design decisions

- Local looping GIF graphics reliably animate on GitHub without JS or Actions.
- Background, main profile content, stack and experience descriptions remain lightweight and readable.
- No animated statistics that fabricate or misrepresent real-time deployment state.
- Animated panels offer static PNG alternatives; meaningful copy remains HTML/Markdown and accessible.
- No third-party analytics/pixel tracking from the animations.

## Scope

The pack updates the GitHub **profile README**, not LinkedIn or sberatergun.com. TPIC is described conservatively as controlled internship activities; RadioTEDU remains active engineering and QA, not a falsely claimed published release.
