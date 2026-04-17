```
 ██████╗██╗      █████╗ ██╗   ██╗██████╗ ██╗███╗   ██╗ ██████╗
██╔════╝██║     ██╔══██╗██║   ██║██╔══██╗██║████╗  ██║██╔════╝
██║     ██║     ███████║██║   ██║██║  ██║██║██╔██╗ ██║██║  ███╗
██║     ██║     ██╔══██║██║   ██║██║  ██║██║██║╚██╗██║██║   ██║
╚██████╗███████╗██║  ██║╚██████╔╝██████╔╝██║██║ ╚████║╚██████╔╝
 ╚═════╝╚══════╝╚═╝  ╚═╝ ╚═════╝ ╚═════╝ ╚═╝╚═╝  ╚═══╝ ╚═════╝
                    // VERB_HUNTER v1.0
```

> _"While you were waiting for Claude to think, someone turned the spinner into a game."_

---

## `> WHAT IS THIS`

Claude Code shows **187 unique spinner verbs** while it's working — things like `Combobulating...`, `Flibbertigibbeting...`, `Clauding...`.

This is a game to **catch them all** — now with four deep, mechanically distinct missions, a synthesized cyberpunk soundtrack, a takeover screensaver, and a help system that speaks five languages.

One HTML file. Zero dependencies. Pure vibes.

---

## `> QUICK START`

```bash
# Just open the file. Seriously.
$ open index.html
```

That's it. Then:

```
1. Look at the spinning verb in the centre of the screen.
2. Press  SPACE  (or click  [ CATCH ]) when you see a word you want.
3. Press  H      to read the manual in 5 languages.
4. Press  M      to try the missions.
5. Press  C      to see what you've caught.
```

No install, no build, no network calls. Runs offline after first load.

---

## `> SCREENSHOT`

```
┌───────────────────────────────────────────────────────────┐
│  CLAUDING // VERB_HUNTER v1.0        CAUGHT 42/187   ♪  ? │
│                                                           │
│  · KERNEL PANIC   TIME 47.3   SCORE 820                   │
│  SYS ████████████████░░░░░░ 62%  ▣▣▢   GOAL 2/3 LEGEND    │
│                                                           │
│          ◂ TGT.ACQ · 0xAF3E ▸                             │
│    <       Discombobulating...       >                    │
│               [ LEGENDARY ]                               │
│                                                           │
│                 [ C A T C H ]                             │
│                                                           │
│  ● DUMP ▆▆▆▆▆▆▆▆▆▆▆▆▓░░░░░░░░░░░░░░  0x2A/0xBB · 22%      │
│         C ████████▓░░░░░ 28/151                           │
│         R ████░░░░░░░░░░  4/26                            │
│         L ███░░░░░░░░░░░  1/10                            │
│                                                           │
│  NORMAL  FAST  INSANE  COLLECTION  MISSIONS SCR.SAVER     │
└───────────────────────────────────────────────────────────┘
```

---

## `> FEATURES`

```
[■] Matrix digital rain background
[■] Four-beam CRT scanline rig — out-of-sync, multi-colour, with a
    step-jumping flicker beam for that "losing raster sync" feel
[■] Text-centric targeting HUD — subtle CLI-style guillemets
    (‹/ verb /›), call-sign tag that re-hashes each verb, animated
    scan pass, rarity underline — deliberately low-key so the verb
    reads first, the frame second
[■] Segmented "disk-dump" progress readout with quartile ticks,
    a blinking cyan write-head, and tier-split mini-bars
    (common/rare/legendary) + hex counts (0x2A/0xBB · 22%)
[■] Glitch text, vignette, particle burst FX on catch
[■] 3 rarity tiers — COMMON / RARE / LEGENDARY
[■] 3 speed modes — NORMAL / FAST / INSANE
[■] 4 missions, all mechanically distinct:
    · CLASSIC HUNT      — zen, collect-'em-all
    · KERNEL PANIC      — stability triage under core-dump pressure
    · REGEX GAUNTLET    — live /regex/ rotates every 10s
    · FORK BOMB         — :(){ :|:& };: — 1 → 4 spinners, don't panic
[■] Collection tracker (187 slots) — click any RARE or LEGENDARY
    to pop its codex entry inline, anchored to the card
[■] Magenta-tinted Collection panel to distinguish it from
    cyan MISSIONS and amber SCR.SAVER
[■] Synthesized cyberpunk ambient BGM (Web Audio, zero files)
[■] Screensaver mode — drifting verb storm + transmission tickers
[■] Mission state pauses while screensaver is up
[■] Auto-save to localStorage (collection + BGM + language + bests)
[■] i18n help panel — 5 polished languages, silky smooth switching
[■] Auto-shrinking verb typography — long verbs like
    "Flibbertigibbeting..." stay on one line at any viewport
[■] Respects prefers-reduced-motion
[■] Keyboard-driven gameplay
[■] Single HTML file, zero build step
```

---

## `> RARITY`

| Tier | Color | Count | Drop Rate |
|------|-------|-------|-----------|
| `COMMON` | `#00ff41` green | 151 | ~80.7% |
| `RARE` | `#ff00ff` magenta | 26 | ~13.9% |
| `LEGENDARY` | `#ffab00` gold | 10 | ~5.3% |

**Legendary verbs** — good luck catching these:

```
Clauding · Combobulating · Discombobulating · Recombobulating
Flibbertigibbeting · Prestidigitating · Whatchamacalliting
Hyperspacing · Quantumizing · Razzmatazzing
```

Each legendary (and every rare) ships with its own **codex entry** —
one-line tagline plus a short piece of pseudo-lore.

Reading is **on-demand from the Collection log** (it was previously
dumped on-screen during catch, which was noisy mid-hunt — the
celebration FX still fire, just without the wall of text):

```
> Press  C  to open COLLECTION
> Click any RARE (magenta) or LEGENDARY (gold) card
> A codex popover anchors itself to the card, smart-flipping
  above / below to stay on-screen
> Click outside or press the × to dismiss
```

---

## `> MISSIONS`

Press `M` to open the mission select. The previous six-mission grab-bag
was scrapped and replaced with **four mechanically distinct modes** —
one zen-hunt baseline and three hard-leaning programmer-meme challenges.

### `01 · CLASSIC HUNT`

> **The zen mode.** No timer, no score, no pressure — just catch all
> 187 spinner verbs at your own pace. The Collection grid and codex
> popovers are the whole point here.

### `02 · KERNEL PANIC  ·  "not syncing"`

> **Triage under core-dump pressure.** Your system stability starts
> at 100% and drains **−3%/s**. Every catch moves the needle:
>
> - `COMMON` = **−20%** (it's noise in the dump — poisons you)
> - `RARE`   = **+15%** (stabilises)
> - `LEGENDARY` = **+40%** (hot-patches the kernel)
>
> Catch **3 LEGENDARY** before the bar flatlines to win. 0% = segfault,
> core dumped, mission failed. **The fun:** you have to actively
> *refuse* easy commons and hunt the risky big-value targets — the
> opposite instinct from the classic loop. Legendaries score huge.
> 90-second clock as a safety net.

### `03 · REGEX GAUNTLET  ·  "now you have two problems"`

> **Live pattern-matching reflex test.** A JS regex displays at the
> top of the HUD and **rotates every 10 seconds** through a deck of
> 8 patterns (each progressively meaner), e.g.:
>
> ```
> /ing$/            -ING terminal
> /^(.)\1/i         doubled opening letter
> /[aeiou]{3,}/i    vowel run of 3
> /^[^aeiou]{3,}/i  consonant cluster
> /(.).*\1.*\1/i    same letter ×3
> ```
>
> Matching verbs *glow* on the main HUD. Catching a match scores
> `base × rarity` (legendaries are worth 400!); catching a non-match
> costs score and **−4s** from the clock. Actually teaches your
> regex-brain to read patterns at speed. 75-second run, score-based.

### `04 · FORK BOMB  ·  :(){ :|:& };:`

> **Multitasking chaos with the internet's most famous one-liner.**
> You start with one parent spinner. At **60 / 45 / 30 seconds
> remaining**, a child process forks into existence — up to 4
> simultaneous spinners, each cycling on its own independent timer.
>
> - Click a child *or* press `1`-`4` to focus it
> - `SPACE` catches the focused process
> - Missed cycles raise a **heat meter**
> - **100% heat = kernel panic, game over**
>
> Survive 75 seconds juggling processes. Pure chaos mode — maximum
> points come from rapid-fire catching across all 4 threads. Perfect
> for showing off.

All missions end on a debrief screen with per-mission stats, score,
personal best tracking, and one-key **retry** (`R`).

---

## `> KEYBINDINGS`

```
╔═══════════╦════════════════════════════════════════╗
║   SPACE   ║  Catch (current verb / focused fork)   ║
║     C     ║  Toggle collection drawer              ║
║     M     ║  Open mission select                   ║
║     B     ║  Toggle ambient BGM                    ║
║     S     ║  Enter screensaver mode                ║
║     R     ║  Retry mission (on results screen)     ║
║     H     ║  Toggle help panel                     ║
║  ENTER/SP ║  Open codex for focused RARE/LEGEND    ║
║    1-3    ║  Switch speed mode (outside forkBomb)  ║
║    1-4    ║  (FORK BOMB) Focus parent / child proc ║
║    ESC    ║  Close any open panel                  ║
╚═══════════╩════════════════════════════════════════╝
```

---

## `> HELP PANEL · i18n`

The in-game help panel (`H` or `?`) speaks **five languages** with
smooth blur-fade transitions between them — no reload, no flicker.

```
┌─ LANG · EN · 中 · RU · ES · DE ──┐
│  English  · Full English manual  │
│  中文      · 中文手册              │
│  Русский  · Отполированный текст │
│  Español  · Manual pulido        │
│  Deutsch  · Poliertes Handbuch   │
└──────────────────────────────────┘
```

- Language preference is **persisted to `localStorage`**.
- First visit: auto-detects from `navigator.language`, falls back to `en`.
- Click any code in the `LANG` strip to switch — content blurs, swaps,
  and fades back in within ~180ms.
- Each translation is hand-tuned for a hacker/cyberpunk tone — UI terms
  like `COMMON` / `RARE` / `LEGENDARY` / `SPACE` / `CATCH` stay in English
  on purpose, so they match the live on-screen labels.

---

## `> AUDIO`

The ambient track is **synthesized live** with Web Audio oscillators —
no `.mp3`, no `.ogg`, nothing to download. Click `♪` in the header or
press `B` to toggle. Your preference is saved to `localStorage`.

---

## `> SCREENSAVER`

Press `S` or click `SCR.SAVER` to let the page take over the screen:
drifting verb storm, random codex flashes, scrolling transmission
tickers, a live clock, a "hex dump" panel, and auto-fullscreen.

Any key or click resumes the hunt.

---

## `> RUN`

```bash
# option A: just open it
open index.html

# option B: local server if you're fancy
python3 -m http.server 8080
# then → http://localhost:8080

# option C: npx
npx serve .
```

No `npm install`. No `webpack`. No `node_modules` black hole.

---

## `> TECH`

```
Language ······ HTML + CSS + Vanilla JS
Lines ········· ~6520 (single file)
Dependencies ·· 0 — no fonts, no CDNs, no network calls
Build step ···· none
Font ·········· System monospace stack (ui-monospace, Cascadia,
                SF Mono, Roboto Mono, Menlo, Consolas, …)
Audio ········· Web Audio API (synthesized, no files)
Rendering ····· 2D canvas (matrix rain, rAF-driven)
                · auto-pauses when the tab is hidden
                · debounced resize via rAF
CRT effects ··· Pure CSS — 4 overlapping scan-beams with
                prime-ish periods, a stepping flicker beam,
                a raster grid and a radial vignette
Collection ···· Click-to-pop codex popover, smart-flipping
                above/below, re-positions on scroll/resize
Storage ······· localStorage
                · clauding_caught        — caught verbs
                · clauding_bgm           — BGM on/off
                · clauding_help_lang     — help panel language
                · clauding_last_mission  — last mission played
                · clauding_best_<mission> — per-mission best
Framework ····· willpower
```

---

## `> CONTROL ROW PALETTE`

The main action bar uses four diegetic colour channels so each
control reads distinctly at a glance:

```
NORMAL · FAST · INSANE    →  green   (speed / hunt)
COLLECTION                →  magenta (echoes RARE drops)
MISSIONS                  →  cyan
SCR.SAVER                 →  amber
```

Active panels light up their own button with a matching glow,
so the current "mode" of the UI is always unambiguous.

---

## `> CREDITS`

- Inspired by [clauding.fyi](https://clauding.fyi/)
- Verb list sourced from [Claude Code's leaked spinner verbs](https://deepakness.com/raw/claude-spinner-verbs/)
- Built with one HTML file and questionable life priorities

---

## `> LICENSE`

MIT — do whatever you want. Catch responsibly.

```
$ echo "happy hunting" | sha256sum
> e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855
```
