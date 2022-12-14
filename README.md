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

## Usage

To use this repo as a template, there are several ways to do it.

1. Click the "Code" dropdown menu button above;
   1. Download template as ZIP or...;
   2. Open a terminal in your desired path (i.e. audio production projects' folder) and paste the following command:

   ```bash
    git clone https://github.com/v3lutz/project-directory-template.git
   ```

2. Create a clone GitHub repository through the "Use as template" button.

## Contribute

Feel free to contribute to this template by forking this repository or submitting a Pull Request.
