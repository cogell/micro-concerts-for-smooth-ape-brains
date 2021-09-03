# Micro Concerts for Smooth Ape Brains

## the idea

**tl;dr** programmatic generated audio-visual solana(?) NFTs

I want to write a little code that makes some programmatic visuals -- think short, square gif maybe 7 seconds? -- that is synced to programmatic audio -- tidalcycles comes to mind, but really any midi package will do -- and then I want to package these little artfarts as NFTs, but eth gas is expensive right now, and solana is the hot thing, so lets mint them on that chain?

## why do this thing?

- make money? ❌
- it has utility? ❌
- take ourselves seriously? ❌
- try new technology? ✅
- collab with new people? ✅
- dip my toe into tech-art? ✅

## sound libraries

- https://github.com/Tonejs/Tone.js
- https://github.com/alemangui/pizzicato

### current challenges

- [ ] how to generate and save audio files?
  - the libs use a web audio api that doesnt seem to have a polyfill on node, maybeeee https://github.com/audiojs/web-audio-api
