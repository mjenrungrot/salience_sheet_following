# Sheet Following using Salience Representation

This repository contains the final project for Music Signal Processing taught by Professor Timothy Tsai 
from Engineering Department at Harvey Mudd College, Fall 2018.

# Pipeline

From MIDI, we synthesize audio and create salience representation (1 bin per semiton, add up all harmonics). Then, we find the onsets (pick sample approach for now).

From sheet music, we extract staff lines detection. Using the staff lines detections, combine onset, and generate soft bootleg score (values are between 0 and 1).

Then, apply block DTW and perform the alignment. Compute two metrics (MSMD and our paper).




# License 

All codes under this repository is licensed under BSD 3-Clause license.

