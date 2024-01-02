
# Abstractions List

A curated list of many of my Max-abstractions available on github

[![](https://img.shields.io/static/v1?label=Support%20on%20Ko-Fi&message=%E2%9D%A4&logo=Kofi)](https://ko-fi.com/I2I3SV7FX)
[![](https://img.shields.io/static/v1?label=Support%20on%20Patreon&message=%E2%9D%A4&logo=Patreon)](https://www.patreon.com/bePatron?u=9649817)
[![](https://img.shields.io/static/v1?label=Support%20on%20Gumroad&message=%E2%9D%A4&logo=Gumroad)](https://tmhglnd.gumroad.com/)

# About

Over the years I've created various abstractions and projects that I've shared via Patreon, Gumroad and Github. Below is a selection from the repositories on github. With the commandline code below you can download all the repositories sequencially into the Max folder (for example `~/Documents/Max 8/Library/`). You can also scroll through the list (sorted alphabetically) and navigate to a specific repo to download it.

```
echo chatgpt-n4m codevember-2019 emoji4max gl-pix-shaders gl.check gridshape-raymarcher image-scraper-n4m jit.underworld list-objects max-pd-converter mc-utilities misc-max-abstractions motion-silhouette n4m-p5 pass-comparators poly-recursion reverb-yafr-mods risset-rhythm-effect sample-scatter-scrubber simplex-noise-loop soularis strange-attractor-synth strange-attractors th.clave th.clockwarp th.comp th.cross3 th.euclid th.getkey th.gl.commandline th.gl.cornerpin th.gl.texteditor th.gl.texturefolder th.gl.videogrid th.lfo th.linden th.midiglide th.pitchshift th.scala total-serialism-n4m vectorfield-particles wave-terrain-synthesis | xargs -n1 | xargs -I{} git clone https://github.com/tmhglnd/{}
```

Total size: `1.43GB`

# Navigate

The list is sorted alphabetically and every entry has a few tags to help search for specific things. Used tags are: `n4m` (node for max), `visual`, `audio`, `data`, `example`, `package` (place in package folder), `abstractions` (place in Max library folder), `generative`, `machine learning`, `tool` (not necesarily used inside max)

## chatgpt-n4m

An example using OpenAI's GPT API with NodeJS in MaxMSP

https://github.com/tmhglnd/chatgpt-n4m

`n4m` `machine learning` `example`

## codevember-2019

A package filled with patches & code from the codevember 2019 challenge.

https://github.com/tmhglnd/codevember-2019

`visual` `audio` `generative`

## emoji4max

Probably the least useful package for Max8, but lots of fun.

https://github.com/tmhglnd/emoji4max

`emoji` `package`

## gl-pix-shaders

A small package of various pixel shaders for processing textures in the Jitter OpenGL world.

https://github.com/tmhglnd/gl-pix-shaders

`visual` `abstractions`

## gl.check

A small abstraction that checks which GL engine is currently used when opening a patcher in MaxJitter (gl2/gl3) and prompts with the question to switch to the other engine if necessary.

https://github.com/tmhglnd/gl.check

`visual` `abstractions`

## gridshape-raymarcher

In this repository you'll find an example on how to use a ray marcher as shading for a jit.gl.gridshape and have it be part of the jitter world using the same camera as the other objects.

https://github.com/tmhglnd/gridshape-raymarcher

`visual` `example`

## image-scraper-n4m

Scrape images from Google and use them as textures on multiple gridshapes in Jitter

https://github.com/tmhglnd/image-scraper-n4m

`visual` `n4m` `example`

## jit.underworld

Gateway to non-realtime HiRes rendering with jit.world in Cycling74's Max

https://github.com/tmhglnd/jit.underworld

`visual` `abstractions`

## list-objects

A small package containing various abstractions for list processing and statistical analysis

https://github.com/tmhglnd/list-objects

`data` `abstractions`

## max-pd-converter

A Node.JS script that converts MaxMSP patches to PureData or vice versa.

https://github.com/tmhglnd/max-pd-converter

`tool`

## mc-utilities

This package contains small abstractions to use with the MC domain in Max8.

https://github.com/tmhglnd/mc-utilities

`audio` `abstractions`

## misc-max-abstractions

A variety of max abstractions that can be helpful during patching but don't really fit any category.

https://github.com/tmhglnd/misc-max-abstractions

`abstractions` `audio` `visual` `data`

## motion-silhouette

An OpenGL jitter patch that transforms the webcam input to a black and white motion image.

https://github.com/tmhglnd/motion-silhouette

`visual` `data`

## n4m-p5

A small example for sending osc between Node4Max and p5.js

https://github.com/tmhglnd/n4m-p5

`data` `n4m` `example`

## pass-comparators

Max abstractions that pass a value to the output if the condition is true, else the output is blocked.

https://github.com/tmhglnd/pass-comparators

`data` `abstractions`

## poly-recursion

Dynamically build a chain of DSP with poly~ objects inside poly~ objects.

https://github.com/tmhglnd/poly-recursion

`example` `abstractions` `audio`

## reverb-yafr-mods

Various modifications to the classic yafr2 reverb such as freeze, glissando and pitchshifting

https://github.com/tmhglnd/reverb-yafr-mods

`audio` `abstractions`

## risset-rhythm-effect

This is a version of the endlessly speeding drumloop, also known as the Risset Rhythm Effect.

https://github.com/tmhglnd/risset-rhythm-effect

`audio` `example`

## sample-scatter-scrubber

Plot and scrub through a set of samples in 3D space organized based on their spectral description

https://github.com/tmhglnd/sample-scatter-scrubber

`audio` `machine learning` `example` `visual`

## simplex-noise-loop

In this repository you'll find a few examples on how to create a Simplex Noise Loop with the [jit.bfg] object within Max Jitter.

https://github.com/tmhglnd/simplex-noise-loop

`visual` `example`

## soularis

A 3-dimensional sequencer analogues to a solar-system.

https://github.com/tmhglnd/soularis

`visual` `audio` `abstractions`

## strange-attractor-synth

This patch uses the xyz coordinates of a Strange Attractor chaotic system to modulate parameters from an FM synthesizer with resonant lowpass filter and flanger effects.

https://github.com/tmhglnd/strange-attractor-synth

`audio` `visual` `tool`

## strange-attractors

Strange Attractor Particle Systems in OpenGL through a glsl vertex shader with transform feedback.

https://github.com/tmhglnd/strange-attractors

`visual` `example`

## th.clave

Generate random clave patterns for algorithmic composition. Outputs a binary list as rhythm, where 1's represent onsets and 0's represent rests.

https://github.com/tmhglnd/th.clave

`generative` `abstractions`

## th.clockwarp

Create rhythms, subdivisions, probabilities and warping out of a single phasor~.

https://github.com/tmhglnd/th.clockwarp

`audio` `generative` `abstractions`

## th.comp

A mono Dynamic Range Compressor (DRC) with a softknee, makeup-gain and a Side-chain Detection functionality.

https://github.com/tmhglnd/th.comp

`audio` `abstractions`

## th.cross3

A Max Abstraction to get the average amplitude values from an audio signal over 3 different frequency bands.

https://github.com/tmhglnd/th.cross3

`audio` `visual` `abstractions`

## th.euclid

Two Max abstractions that generate euclidean musical rhythms. One outputs as a list of zeroes and ones, the other one is driven by a phasor~ and outputs clicks at signal rate.

https://github.com/tmhglnd/th.euclid

`audio` `generative` `abstractions`

## th.getkey

return a bang or bool on keydown or keyup strokes of a specified character

https://github.com/tmhglnd/th.getkey

`data` `abstractions`

## th.gl.commandline

A commandline text-editor in the Max Jitter OpenGL window for interaction with your patch in a Livecoding-like style.

https://github.com/tmhglnd/th.gl.commandline

`visual` `abstractions`

## th.gl.cornerpin

jit.gl.cornerpin wrapped in an abstraction that automatically exposes corner coordinates to pattrstorage

https://github.com/tmhglnd/th.gl.cornerpin

`visual` `abstractions`

## th.gl.texteditor

A basic texteditor in the Max Jitter OpenGL window for interaction with your patch in a Livecoding-like style.

https://github.com/tmhglnd/th.gl.texteditor

`visual` `abstractions`

## th.gl.texturefolder

This abstraction allows you to load an entire folder of images into named jit.gl.texture objects.

https://github.com/tmhglnd/th.gl.texturefolder

`visual` `abstractions`

## th.gl.videogrid

Display a video/texture in the jit.world on a fixed grid.

https://github.com/tmhglnd/th.gl.videogrid

`visual` `abstractions`

## th.lfo

A small lfo abstraction with selectable waveshapes

https://github.com/tmhglnd/th.lfo

`audio` `abstractions`

## th.linden

Generate lindenmayer system string expansions with custom rules for algorithmic composition

https://github.com/tmhglnd/th.linden

`generative` `abstractions`

## th.midiglide

A Max Abstraction that keeps track of currently held midi-notes and glide the midi-pitch back to previous note on release of latest pressed midi-note.

https://github.com/tmhglnd/th.midiglide

`data` `abstractions`

## th.pitchshift

A mono time domain pitch shifter abstraction for Max based on the tempophon.

https://github.com/tmhglnd/th.pitchshift

`audio` `abstractions`

## th.scala

Explore alternative and microtonal tuning systems with this small package of abstractions for Max

https://github.com/tmhglnd/th.scala

`audio` `data` `abstractions`

## total-serialism-n4m

A node-for-max example using the total-serialism package

https://github.com/tmhglnd/total-serialism-n4m

`n4m` `generative` `data` `example`

## vectorfield-particles

The jit.gl.bfg object is used to generate a 2 dimensional noise pattern used as the vectorfield. The pixel value determines the direction of the flow when a particle moves over that position in the field.

https://github.com/tmhglnd/vectorfield-particles

`visual` `generative` `example`

## wave-terrain-synthesis

A package of abstractions for polar & cartesian wavetable lookup from a jit.matrix and wavetable generator with jit.gl.bfg

https://github.com/tmhglnd/wave-terrain-synthesis

`audio` `abstractions` `generative`

# License

Licenses differ per project. Please see the repository.

These programs are distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the License for more details.
