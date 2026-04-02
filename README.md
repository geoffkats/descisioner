*This is a submission for the [DEV April Fools Challenge](https://dev.to/challenges/aprilfools-2026)*

## What I Built
I built **Enterprise Coffee Decisioner™**, an intentionally useless April Fools web app that decides whether you should drink coffee using corporate nonsense and teapot drama.

- Neon “enterprise” UI with fake KPI dashboard (Synergy Index, Caffeine Half-Life, Jitter Probability, Board Alignment).
- 17-point strategic intake form with absurd entries (Lunar Influence, Manager Proximity, Last Git Commit).
- “⬡ FINALIZE DECISION ⬡” includes required repeated confirmation clicks.
- `HTTP 418` teapot path: the system explicitly returns “I’M A TEAPOT”.
- “Download PDF” path requires physical shake (or manual shake button), then shows comedic outcome (page 847 blank, antivirus quarantine, etc.).
- Local memo generator (no external API required), but concept idea came from Google Antigravity + Claude Sonnet style prompts in design.

## Demo
Run locally in browser:
- Open `enterprise_coffee_decisioner_april_fools.html` from repo.
- Fill inputs.
- Click “FINALIZE DECISION” until progress pipeline finishes.
- Read “Board Recommendation” result and generated memo text.
- Click “⬇ Download PDF”, shake twice / click “Manual Shake”, confirm passphrase.
- Use “↩ Waste More Time” to rerun.

No deploy required; works offline from file URL.

## Code
Repo: `https://github.com/geoffkats/descisioner`  
Primary implementation: `enterprise_coffee_decisioner_april_fools.html` (single-file HTML/CSS/JS).

Key logic:
- UI state transitions and animation overlays
- Teapot compliance pipeline + random verdict
- Local passphrase generation + physical shake verification
- Reset/ reiteration path

## How I Built It
- HTML + CSS (animated neon, grid layout, status ticks)
- JavaScript: controls, randomization, progressive step animation, local memo text.
- In early ideation, I used Google AI Antigravity + Claude Sonnet-style prompting to shape tone and jokes.
- Final product: no external dependencies, 100% local to keep judging stable.

## Prize Category
- Primary: **Best Ode to Larry Masinter**
  - RFC 2324 / HTTP 418 is central to the UI and messaging.
  - Many “teapot” references in status text, rulings, and failures.
- Secondary: **Best Google AI Usage**
  - Google Antigravity + Claude Sonnet style inspired design and naming.
  - Final mode is local and offline (robust judge-friendly deliverable).
- Bonus: **Community Favorite**
  - High absurdity + shareable meme-ability.

## Team
- Solo submission: `@geoffkats`

## Notes
- This intentionally solves zero real problems and is built to be delightfully ridiculous.
- 🤣 “Anti-value ranked by design.”
- The repo link above is the source code and demo.
