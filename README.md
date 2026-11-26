# korgTools synth units

MS-20 and Monologue-style synths for drumlogue and original NTS-1.

## Downloads

In Actions, open the latest successful build for your device and download its artifact:

- **drumlogue-unit** contains `ms20.drmlgunit` and `monologue.drmlgunit`.
- **nts1-unit** contains `ms20_nts1.ntkdigunit` and `monologue_nts1.ntkdigunit`.

Both drumlogue synths include NOTE (0-127, default 60/C4). MS-20 opens on WIDE PAD; Monologue opens on ACID LINE. Each drumlogue unit has 11 factory presets.

The original NTS-1 versions have six live controls; remaining settings are baked into each unit. The NTS-1's own filter, envelope and effects also affect the sound.

## Installation

Back up your existing units and start at low volume. These are community-made synths, not Korg-audited recreations.

**drumlogue:** turn it off, connect a USB data cable to your PC, then power on while holding RECORD. Copy the `.drmlgunit` files into `Units/Synths/` on its USB drive, eject safely and confirm restart on the device.

**Original NTS-1:** use Korg NTS-1 Librarian to install the `.ntkdigunit` files. Do not use drumlogue USB storage instructions. These units are not for NTS-1 mkII.

## Source

Separate folders allow both synths and device targets to coexist. GitHub Actions builds with Korg's logue SDK. Builds run when source folders change, or manually using Run workflow.
