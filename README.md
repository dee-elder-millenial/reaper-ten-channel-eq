# REAPER Ten Channel EQ

A simple 10-band graphic equalizer for [REAPER](https://www.reaper.fm/), packaged as a native JSFX effect.

This plugin is intentionally small, readable, and dependency-free. It uses ten fixed peaking EQ bands with familiar octave-spaced center frequencies, plus input and output trims.

## Features

- Native REAPER JSFX plugin, no VST/AU build step required
- Horizontal graphic-EQ interface with ten draggable bands
- 10 fixed EQ bands from 31 Hz to 16 kHz
- +/-15 dB gain per band
- Input and output trim controls
- Plain-text source that can be copied, modified, and shared
- MIT licensed

## Download

Download the plugin file directly:

[Effects/Ten Channel EQ.jsfx](Effects/Ten%20Channel%20EQ.jsfx)

Or download the repository as a ZIP from GitHub:

`Code > Download ZIP`

## Install

1. In REAPER, choose `Options > Show REAPER resource path in explorer/finder`.
2. Open the `Effects` folder.
3. Copy `Effects/Ten Channel EQ.jsfx` into that folder.
4. In REAPER, open the FX browser.
5. Choose `FX > Scan for new plugins`.
6. Search for `Ten Channel EQ` under `JS`.

Important: JSFX files go in REAPER's `Effects` folder, not `UserPlugins`. `UserPlugins` is for REAPER extension binaries.

More detailed installation notes are in [INSTALL.md](INSTALL.md).

## Bands

The custom JSFX interface arranges these bands left-to-right like a classic graphic equalizer. Drag a band up to boost or down to cut.

| Band | Center frequency |
| --- | --- |
| 1 | 31 Hz |
| 2 | 63 Hz |
| 3 | 125 Hz |
| 4 | 250 Hz |
| 5 | 500 Hz |
| 6 | 1 kHz |
| 7 | 2 kHz |
| 8 | 4 kHz |
| 9 | 8 kHz |
| 10 | 16 kHz |

## Development

The plugin is a single JSFX file:

`Effects/Ten Channel EQ.jsfx`

To edit it, change the file in your REAPER `Effects` folder or copy this repository version there after each edit. REAPER can reload JSFX from the FX window after rescanning or reopening the effect.

## License

MIT. See [LICENSE](LICENSE).
