# Interpret ($INTERPRET)

Paste any pump.fun coin and get its live market data translated into plain words. The site has a colourful Y2K / Frutiger Aero look: a pixel landscape with rainbow bubbles, a rainbow, clownfish swimming through the sky, glossy aqua buttons and a retro "HELLO!!" dialog.

## Deploy
The site is a single `index.html` with no folders and no build step. Drop it into a GitHub repo or Vercel.

## Settings
Open `index.html` and find `CONFIG` near the top of the script:

```js
var CONFIG={xUrl:'',ca:'',buyUrl:'',chartUrl:''};
```

## How it works (live)
- **Translator:** tells you whether the coin is still on the pump.fun bonding curve or has graduated to PumpSwap, then reads its pools live from the public DexScreener API, with no key needed. It turns liquidity, buys vs sells (1h and 24h), age, price moves, market cap vs liquidity, volume turnover, socials and where it trades into plain sentences. It also gives a 0–100 vibe meter with a pixel mood face.
- **Honest limits:** the site says clearly what it can't read yet (holders, mint and freeze authority, bundles). If the API can't be reached, it shows a clearly labelled sample read.
- **Fresh coins:** the latest pump.fun coins (addresses ending in "pump"), marked on curve or graduated,, each with its own vibe score. Tap one to interpret it.
- **Phrasebook:** 22 memecoin and pump.fun terms translated into plain English.
- **Other sections:** what it reads, how it works, the $INTERPRET token section and an FAQ.

Not affiliated with SOLVET or DexScreener. Interpretations are automatic readings of market numbers, not safety checks or financial advice.
