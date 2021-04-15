# facsimiles of Alfie - Tribute to the Triadex Muse

2021-04-15

This week I released an EP (well, a sub 30 min album) on Bandcamp that I titled facsimiles. The final track, titled (dedicated to alfie) is a 7 minute tribute to non-human collaborators. 

[facsimiles album by ExquisiteCorp](https://exquisitecorp.bandcamp.com/album/facsimiles) 

The entire album was composed on my modular synth, a system I've created as a generative music-making machine. I rely on the synth as a familiar and comfortable collaborator for extending my ideas, challenging me, or giving me something to respond to.

The final track is named for and dedicated to Alfie. In 1994 my family bought a computer for our home. I suppose they thought it was going to be increasingly important to have, and my mother was about to start going back to university so it would be useful for writing papers. We had a 2400 baud modem (240 characters per second) and I got a book out from my local library on how to connect to the internet. I connected to Mofo Ex Machina, the Penn and Teller bulletin board, as well as various social game-worlds (all in text, mind you.) such as various MUCKs, MOOs and MUSHes. These were all variations on MUDs or multi-user dungeons. Again, these were all text-only affairs. Usually a few dozen people would be logged in and exploring various rooms, leaving mail (in described mailboxes that you had to check), flying around, or mostly just chatting. 

I don't remember which one it was, but I do have a distinct experience of logging in for the first time and experiencing a bot. In this text world new players were spawned in a closet, again described in text. You could hear people outside I believe, but this closet area was meant to be a safe starting place. In addition to yourself there was a described simple robot, named Alfie. Alfie didn't say or do much, but it explained that you could control it with commands. The first one I tried was "Alfie, strike a pose!" and Alfie would contort or dance for the player.

Move ahead a few years to college. In 2001 I met the Triadex Muse at the Brandeis Electro-Acoustic Music Studio (BEAMS). The Triadex Muse is described with the obscure off-putting language that is de rigeur when I look for modular synth gear today:

> The Triadex Muse is a sequencer-based synthesizer, produced in 1972, and designed by Edward Fredkin and Marvin Minsky at MIT. It is an algorithmic, deterministic event generator, utilizing early digital integrated circuits to generate an audio output that can sound very musical.

![Triadex Muse logo displaying robotic head](images/computer-for-people.jpg)

I suppose that description isn't as bad as others I've read. Essentially it creates repeating and changing sequences of notes. Easy sliders on the instrument continuously change volume, note, tempo, themes, intervals. The sound is unmistakeably electronic and yet the generated rhythms have a swing to them, so it feels more pleasing to our ears and less robotic. 

At BEAMS I renamed the Triadex Muse Alfie. For a final concert in one of my electronic music 'laptopping' classes I proposed we perform an improvised work using the gear from the lab. My friend Daniel performed on the Buchla 100A synthesizer from the San Francisco Tape Music Center which was at BEAMS. We had to set up a video uplink stream (this was back in 2001) from the studio to the auditorium because the synth could not move out of the door. Alfie was so small and cute. I could just carry it into the concert hall, and of course I performed with it.

In reviewing the Wikipedia page for the Triadex Muse it mentions that it was used by the first wave of electronic musicians in Philadelphia. I knew some of the listed people there when I was active playing music and going to shows in that city (my hometown originally), so that's an interested personal reference for me as well, though I don't remember seeing it used live. It's certainly possible since sometimes everything and the kitchen sink was played.


In Tom Whitwell (of Music Thing Modular, DIY modular kit-maker)'s writing from 2004

> So what was the Muse? Well, not really a synth. It was a digital sequencer, which played melodic-sounding bleepy music through the internal speaker, based on a baffling set of algorithms. As you moved the sliders, the algorithms changed, and the music changed. Like the Chiclet DSP Music Box, it was designed to replace a radio - why listen to old music, when this neat-o box can make new music? There was an idea only a MIT professor could love.

Tom went on to create the Turing Machine module, a 'binary shift register' of repeating looping and slowly (or quickly) constantly drifting and shifting notes. He says its influenced by the Triadex Muse and as well the Buchla 266 Source of Uncertainty, which itself was a major inspiration for the MakeNoise Wogglebug.

- [Tom Whitwell 2004 article about the Triadex Muse](https://www.engadget.com/2004-11-27-music-thing-the-triadex-muse.html)
- [Music Thing Modular: 22 Things to Know About the Turing Machine](https://musicthing.co.uk/pages/turing.html)

### Album module details

I've attempted to build my own complex version of the Triadex Muse out of my own modular synth system. The two main modules that are the key to my system are the MakeNoise Wogglebug and the Monome Teletype.

At this point I have 3 different random generators for pitches, gates and triggers but on the album I made primary use of the Wogglebug. It puts out a continuous pulse and random voltages that I set up to generatively effect level, filtering and other facets of the sound. The random voltages it puts out are stepped (like pulling random integers), gradual (like perlin noise number generation), and woggle? (kind of a bouncy number generator. I'm not sure if there's a code equivalent).  

In addition, I use a Monome Teletype. Not the most hands-on, it requires a creator to pre-code the module using the Teletype language, a kind of simple Forth stack language. Incidentally, Monome's description of the Teletype mirrors the language about the Triadex Muse:

> a dynamic, musical event triggering platform. Scripts are assigned to each of the eight trigger inputs. Herein you can set CV values (four outputs) and trigger gates (four outputs) with extended functionality for pattern manipulation, slews, randomness, sequences, basic arithmetic, stacks, delays, and much more.

The Monome Teletype is capable of different behaviors. I use it rather simply as a complex experimental sequencer, attempting to code in approximations of the Triadex Muse. 

The other instruments on this album are the MakeNoise Morphagene which I use as a digital-analog tape machine. The oscillator is Mutable Instruments Plaits primarily in harmonic chord mode, with LFOs and Attack-Sustain-Decay-Release from Stages, and occasional use of excitation and resonance from Rings. Other modules with occasional use are the dual low pass gate from Siam Modular's Takaab and the VCF3 filter from Erica Synths' Pico line. 

In addition, I made use of the Cre8audio Cellz occasionally as a simple touch plate/keyboard for advancing notes or gates when I felt moved to respond to the rest of the system playing on its own. Lastly, the first few tracks on the album make use of Strymon Magneto for filtering, reverb and delay. I use a Takaab Nearness for panning.

Modules/instruments list

- MakeNoise Wogglebug, Morphagene
- Mutable Instruments Plaits, Stages, Rings
- Monome Teletype
- Siam Modular Takaab 2LPG, Nearness
- Erica Synths Pico VCF3
- Cre8audio Cellz
- Strymon Magneto

The album is Creative Commons CC BY SA Non-commercial
