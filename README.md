# Think DSP

Code for the [Think DSP](https://greenteapress.com/wp/think-dsp/) book. The reference code for the "Think DSP" book is
available [here](https://github.com/AllenDowney/ThinkDSP).

## Setup

- Install [uv](https://docs.astral.sh/uv/getting-started/installation/)
- Install Python: `uv python install`
- Install project dependencies: `uv sync`

## Run

- To run Jupyter Lab: `uv run jupyter lab`

## Speech Terms

- Audio Data: Process involving sampling a continuous sound wave at discrete intervals.
- Sampling Rate: Number of audio snapshots taken per second, measured in kilohertz (kHz). A higher sampling rate
captures more detail, but also increases file size. Speech standard is `16 kHz`.
- Bit Depth: Number of bits per sample. Higher bit depth captures a wider range of sounds, but increases file size.
Speech standard is `16 bit`.
- Channels: Number of audio tracks. Mono (one track) and stereo (two tracks) are most common. Stereo enhances spatial
context for immersive experiences, while mono is ideal for voice clarity. Speech standard is `mono`.
- Dynamic Range: Difference between quietest and loudest sounds in a recording.
