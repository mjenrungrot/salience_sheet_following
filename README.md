# Sheet Music Following 

This repository contains the final project for Music Signal Processing taught by Professor Timothy Tsai 
from Engineering Department at Harvey Mudd College, Fall 2018. For more details, please look at the final report [[here]](https://github.com/mjenrungrot/salience_sheet_following/blob/master/writeup/final_paper.pdf).

# Repository
```
File/Folder             |   Descriptions
=====================================================================================================
soundfonts/                 Soundfont used for synthesizing audio
writeup/                    Writeup for the project
dorfer_results/             Results for one of the baseline system.
01_processData.ipynb        Convert MIDI to audio
02_audioToSpec.ipynb        Convert audio to its log-frequency spectrogram
03_generateBootleg.ipynb    Synthesize a bootleg representation from the log-frequency spectrogram
04_Evaluate.ipynb           Evaluate the system's performance
```

# Instructions

1) Download `MSMD` dataset.

2) Install `muscima` library (https://github.com/hajicj/muscima). 
- Clone the repository.
- Run `python setup.py install`.

3) Install `python-midi` library (https://github.com/louisabraham/python3-midi).
- Clone the repository.
- Run `python setup.py install`.

4) Install `python-rtmidi` library (https://github.com/SpotlightKid/python-rtmidi.git).
- Clone the repository.
- Run `python setup.py install`.

5) Install `pdfminer` library (https://github.com/pdfminer/pdfminer.six).
- Clone the repository.
- Run `python setup.py install`.

6) Install `MSMD` library  (https://github.com/CPJKU/msmd)
- Clone the repository.
- Run `python setup.py install`.

# License 

All codes under this repository is licensed under BSD 3-Clause license.
