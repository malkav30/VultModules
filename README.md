# Vult Modules for Rack

A set of modules for VCV Rack written in Vult. You can read more about the modules here: https://modlfo.github.io/VultModules/


![Modules](https://modlfo.github.io/VultModules/images/modules.png "Modules")

### Filters
- [Lateralus](https://modlfo.github.io/VultModules/lateralus/): Diode ladder Filter.
- [Tangents](https://modlfo.github.io/VultModules/tangents/): Steiner-Parker Filter.
- [Stabile](https://modlfo.github.io/VultModules/stabile/): State Variable Filter.
- [Unstabile](https://modlfo.github.io/VultModules/unstabile/): Circuit Bent State Variable Filter.
- [Rescomb](https://modlfo.github.io/VultModules/rescomb/): Resonant Comb Filter.
- [Julste](https://modlfo.github.io/VultModules/julste/): Low Pass Gate. Buchla model.
- [Tohe](https://modlfo.github.io/VultModules/tohe/): Tone Control.

### Effects
- [Debriatus](https://modlfo.github.io/VultModules/debriatus/): Wave Destruction. Wave Folder, Bit Crusher, Distortion and Saturation.

### Envelopes & VCA
- [Spank](https://modlfo.github.io/VultModules/spank/): Drum Envelope.
- [Julste](https://modlfo.github.io/VultModules/julste/): Low Pass Gate. Buchla model.

### Drums
- [Trummor](https://modlfo.github.io/VultModules/trummor/): Drums Synthesizer.
- [Trummor 2](https://modlfo.github.io/VultModules/trummor2/): Drum (Percussion) Synthesizer.

### Oscillators
- [Vessek](https://modlfo.github.io/VultModules/vessek/): Complex Analog Oscillator.

### Utilities
- [Splie](https://modlfo.github.io/VultModules/splie/): Buffer
- [HyperPower](https://modlfo.github.io/VultModules/hyperpower/): Infinite Power Supply.

## Donate

I’m glad to publish these modules for free so anyone can use them. But these modules don’t come cheap for me. Behind every module there are many hours of work (and many litters of coffee). If you enjoy these modules you can support the development by making a donation.

The suggested donation is 20 euro for the full pack, but of course you can donate as much as you want any donation help me buy more coffeeeeee :)

Here's the link: [DONATE](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=RRMY2QPYEZT2S) 

## Use

Download from the [releases page](https://github.com/modlfo/VultModules/releases) the file corresponding to the VCVRack version you have. Place the `VultModules` directory in the plugins folder.


## Build

First you need to build the latest release version of [Rack](https://github.com/VCVRack/Rack) following the instructions in its [README](https://github.com/VCVRack/Rack/blob/master/README.md).

Then clone this repository inside the `plugins` folder of Rack and use `make`.

```
$ cd plugins
$ git clone https://github.com/modlfo/VultModules.git
$ make
```

## Modify

To change the DSP code you need to have Vult installed. Vult can be installed by downloading it from the [Releases](https://github.com/modlfo/vult/releases) page or installed with [npm](https://www.npmjs.com/package/vult).

Once you have Vult installed you can regenerate the code with the following line:
```
$ vultc src/VultEngine.vult -ccode -o src/VultEngine
```

## License

The license is a BSD 3-Clause with the addition that any commercial use requires explicit permission of the author. That applies for the source code.

For the image resources (all SVG files), any use requires explicit permission of the author.
