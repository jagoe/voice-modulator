# Voice Modulator

Little script to automate the process of hooking up the SoX stream to any recording software.

## Requirements

* [SoX](http://sox.sourceforge.net/)
* [PulseAudio Control/pactl](https://linux.die.net/man/1/pactl)

## Usage

* `voice-modulator -h`
  Print a help text
* `voice-modulator -v`
  Verbose SoX output, useful to figure out why a set of effects isn't working
* `voice-modulator -e`
  Enable a pre-defined effect. Options: robot, dalek, none (for testing purposes)
* `voice-modulator -f`
  Specify a file containing effects, such as `pitch 800` (have fun sounding like a smurf)
