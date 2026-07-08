# EDB-Orgel - Version [1.0]

Date: 2024-08-08

Name: Benjamin Dehli

Profile: [store.dehlimusikk.no][Gumroad profile]

## Included formats

- Decent Sampler

## Release notes

### Version 1.0 (2024-08-08)

- First version released

## Description

EDB-Orgel delivers the sound of four different digital synthesis types with the workflow of a drawbar organ combined with an analog synthesizer.

## Technical specification

|                       | Sample rate | Bit depth | Channels   | Number of files | File size |
|----------------------:|------------:|----------:|------------|----------------:|----------:|
|           **Samples** |      48 kHz |    24 bit | 1 (mono)   |             532 | 974.80 MB |
| **Impulse responses** |      48 kHz |    24 bit | 1 (mono)   |               8 |  85.00 KB |

## User Interface

The user interface offers precise control over every aspect of the instrument and effects.
Explore parameters to refine your sound, including volume control and sound source selection for the nine drawbars, ADSR envelope, amplitude modulation (tremolo) with LFOs, velocity sensitivity, different filter types, speaker simulation, stereo widener and vibrato controlled by the modulation wheel.

### Tabs

|![Mixer tab](/Screenshots/edb-orgel_mixer.png)|![Modulation tab](/Screenshots/edb-orgel_modulation.png)|![Patch dialog](/Screenshots/edb-orgel_load-patch.png)|
|:--------------------------------------------:|:------------------------------------------------------:|:----------------------------------------------------:|
|                  Mixer tab                   |                     Modulation tab                     |                     Patch dialog                     |

To accommodate all the controls, they are organized into two separate tabs and a dialog window.

|![Open patch dialog](/Screenshots/button_load-patch.png)|![Toggle between mixer and modulation tab](/Screenshots/button_mixer-modulation.png)|
|:------------------------------------------------------:|:----------------------------------------------------------------------------------:|
|                    Open patch dialog                   |                       Toggle between mixer and modulation tab                      |

The button with a floppy disk icon, opens a dialog window for loading predefined patches. The MIX/MOD button allows you to toggle between a mixer view with drawbars, and a modulation view with various modulation controls for further sound customization.

### Drawbars

|![Drawbar controls in the mixer tab](/Screenshots/drawbars.png)|
|:--:|
|Drawbar controls in the mixer tab|

Unleash the power of the nine drawbars to shape your organ's tone with precision. Each drawbar controls the amplitude of a specific harmonic overtone, offering you unparalleled control over the instrument's harmonic richness.

### Sound source

|![Sound sorce buttons in the mixer tab](/Screenshots/sound-source.png)|
|:--:|
|Sound source buttons in the mixer tab|

- 64 (Commodore 64)
  - The MOS Technology 6581 Sound Interface Device (SID) was used in devices such as the Commodore 64 and Elektron SidStation.
- PD (Phase Distortion)
  - Phase distortion synthesis is a technique that was used in Casio synthesizers from the CZ range, such as the Casio CZ-1 and the Casio CZ-101.
- FM (Frequency Modulation)
  - Frequency modulation synthesis is a widely used technique in various devices including AdLib and Sound Blaster sound cards, Sega Genesis (Mega Drive) video game consoles, and synthesizers like the New England Digital Synclavier and the Yamaha DX-7.
- LA (Linear Arithmetic)
  - Linear arithmetic synthesis is a method used in synthesizers such as the Roland MT-32 sound module and the Roland D-50 synthesizer.

### ADSR Envelope

|![Envelope controls in the modulation tab](/Screenshots/envelope.png)|
|:--:|
|Envelope controls in the modulation tab|

Shape your sound precisely with the Attack, Decay, Sustain, and Release parameters. Whether you desire a punchy, staccato tone or a smooth, lingering ambiance, the ADSR envelope allows you to tailor the dynamics to your liking.

- ATT (attack)
  - Individual attack time of the amplitude envelope for each drawbar
- DEC (decay)
  - Individual decay time of the amplitude envelope for each drawbar
- SUS (sustain)
  - Individual sustain level of the amplitude envelope for each drawbar
- REL (release)
  - Individual release time of the amplitude envelope for each drawbar

### Tremolo

|![Tremolo controls in the modulation tab](/Screenshots/tremolo.png)|
|:--:|
|Tremolo controls in the modulation tab|

The speed (SPD) and depth (DPT) controls enable you to modulate the amplitude of the drawbars with the desired speed and depth using the Low-Frequency Oscillator (LFO).

- SPD (speed)
  - Tremolo speed determines the speed at which the modulation occurs
- DPT (depth)
  - Adjust tremolo depth to introduce subtle or pronounced variations in volume

### Velocity sensitivity

|![Controls for the velocity sensitivity in the modulation tab](/Screenshots/velocity-sensitivity.png)|
|:--:|
|Controls for the velocity sensitivity in the modulation tab|

- VEL (velocity sensitivity): Determines whether the velocity should affect the volume of the drawbar

### Filters

|![Filter select buttons](/Screenshots/button_filters.png)|
|:--:|
|Filter select buttons|

EDB-Orgel features the different filter types you get from the SID chip. These are impulse responses (IR) of the filters in the MOS Technology 6581 chip. Cutoff frequency and resonance amount for each filter is set to a fixed value.

- OFF: Filter is disabled
- LPF: Low Pass Filter
- BPF: Band Pass Filter
- L/B: Low Pass Filter and Band Pass Filter
- HPF: High Pass Filter
- L/H: Low Pass Filter and High Pass Filter
- B/H: Band Pass Filter and High Pass Filter
- ALL: Low Pass Filter, Band Pass Filter and High Pass Filter

### Output

|![Buttons for the output settings](/Screenshots/button_direct-speaker.png)|
|:--:|
|Buttons for the output settings|

- DIR (Direct)
  - The direct sound of the line output
- SPK (Speaker)
  - The sound of a tiny computer speaker miced with a Shure SM57

### Mono/Stereo

|![Buttons for toggling between mono and stereo](/Screenshots/button_mono-stereo.png)|
|:--:|
|Buttons for toggling between mono and stereo|

- 1 speaker (mono): Stereo effect is disabled
- 2 speakers (stereo): Stereo effect is enabled

## Equipment used

|                    Name                    |                            Image                           |
| :----------------------------------------: | :--------------------------------------------------------: |
| [Elektron SidStation][Elektron SidStation] | ![Elektron SidStation](/Equipment/elektron-sidstation.jpg) |
|        [Casio CZ-101][Casio CZ-101]        |        ![Casio CZ-101](/Equipment/casio-cz-101.jpg)        |
|          [Yamaha DX7][Yamaha DX7]          |          ![Yamaha DX7](/Equipment/yamaha-dx7.jpg)          |
|         [Roland D-50][Roland D-50]         |         ![Roland D-50](/Equipment/roland-d-50.jpg)         |

[Gumroad profile]: https://store.dehlimusikk.no/
[Elektron SidStation]: https://www.dehlimusikk.no/equipment/instruments/elektron-sidstation/
[Casio CZ-101]: https://www.dehlimusikk.no/equipment/instruments/casio-cz-101/
[Yamaha DX7]: https://www.dehlimusikk.no/equipment/instruments/yamaha-dx7/
[Roland D-50]: https://www.dehlimusikk.no/equipment/instruments/roland-d-50/
