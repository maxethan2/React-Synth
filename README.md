# React Synth Using Tone.js
### Created by Max Haviv

![current_synth_photo-github](https://github.com/maxethan2/React-Synth/assets/38705345/b49b087b-17f2-4aa0-b610-952b98a45ba5)

### Check out the live app <https://react-synth.vercel.app/home>

This App aims to create a web-based synth created using Tone.js and React. It uses two Tone PolySynths acting as individual oscillators with three wave types to choose from. Next, the two oscillators can be adjusted in the Mixer section to change the precise tuning of an oscillator and its own individual volume. There is then a lowpass filter and and low frequency oscillator (LFO) that oscillates the cutoff of the filter. Then comes an Amp envelope which has full ADSR control. (The envelope is connected at the end of the chain after the filter and volume nodes so this Amp envelope doesn't act like a real Amp envelope but is close enough for this project) There is then a small preset bank that can hold nine presets a tiny sequencer to record sequences and then play them back, and a hold function that will hold the notes that you play until you release the hold button. Lastly, there is an on-screen keyboard that you can play with the click of your mouse. but there is also USB Midi support! (Currently, the Midi is a work in progress but is still useable to have some fun messing around.) All this together makes for a fun little project that you can use to make some really cool synth sounds!

## Midi Support
USB Midi is supported! But it is a work in progress...

⚠️ Be wary using USB Midi as it can and will bug out and get VERY loud ⚠️
