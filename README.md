# sound-synth-final-project
my final electronics piece


NOTE:
A MIDI KEYBOARD AND SCORE IS REQUIRED TO PERFORM. Otherwise, you'll just hear some samples. 

Performance Notes:
- next EVENTS are cued using the spacebar
- "CUES" will appear in the Max Console, and correspond to the timing of musical events in the score
- timing is very free, generally allow the sounds to settle and fade away before proceeding onto the next event


temple bowl and whispering samples taken from freesound.org

packages used: spat, bach

things i did:
- turned sfplay into a poly~, allowing for multiple audio files to be played back simultaneously
- created "noisy.synth" which uses a couple overtones and a phi multiplier to create some spacey sounds, including parameters for noise, random blooping, low-pass filters, and etc. THIS CAN ONLY BE PLYED WITH THE MIDI KEYBOARD.
- created a ring-modulator which takes the auddio file output from sfplay and ring modulates it with the noisy.synth output.
- utilizes a polyphonic sampler with the keyboard to allow for midi keyboard control of pitch shifted samples in the media folder
- handled directory structure, etc.
- created a score and wrote an experimental piece inspired by a Buddhist meditation, where temple bowls puncuated the ends of long, long, periods of silent seated meditation or chanting. 
