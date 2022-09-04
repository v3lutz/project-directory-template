# 🎛️ Project Directory Template

A directory template for audio production projects.

## Directory Structure

```bash
.
└── <track-name>/
    ├── artwork/
    │   └── .png/.psd files
    ├── exports/ # ** - version number (01, 02, 03, ...)
    │   ├── pMST** (pre-master [-6dB])
    │   ├── lmtMST** (limited master [-0.04tpdB])
    │   └── MST**
    ├── project_files/
    │   ├── audio_files/
    │   │   ├── reference_tracks/
    │   │   │   └── .wav/.mp3 files
    │   │   ├── recordings/
    │   │   │   └── .wav files
    │   │   └── .wav/.aiff/.flac files
    │   └── <artist-tag/name>_<track-name>_<version> # Save as new version... (FL Studio)
    ├── README.md # This file
    ├── INSPIRATION.md # Inspiration, motivation, reference tracks, ideas
    └── TRACK_INFO.md # Artist, Title, Remixer, Genre, BPM, Key, Export Settings
```

## Contribute

Feel free to contribute to this template by forking this repository or submitting a Pull Request.
