# 💿 exports/

Track exports sub-folder:

- pMST are pre-masters with -6dB of headroom;
- lmtMST are limited pre-masters for comparison purposes limited at -0.04tpdB  (true peak decibels);
- MST are rendered masters.

** represents the version number.

```bash
.
└── <track-name>/
    ├── ...
    ├── exports/ # ** - version number (01, 02, 03, ...)
    │   ├── pMST** (pre-master [-6dB])
    │   ├── lmtMST** (limited master [-0.04tpdB])
    │   └── MST**
    └── ...
