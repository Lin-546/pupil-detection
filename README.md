# Pupil and blink detection algorithms for near-eye device applications

## System Requirements
We develop the Windows version of `simple pupil` using 64 bit Windows 10.
## 7-Zip
Install 7-zip to extract files.
## Python
you will need a 64 bit version of Python 3.8. If you install any other version, make sure to install the 64 bit version!
## Install Python Libraries
we recommend using a virtual environment for running `simple pupil`. To install all Python dependencies, you can use the `requirements.txt` file from the root of the simple pupil repository.
## Model
`detector4.svm` `predictor4.dat`
## Data
Video files, User information files
## Software
`pupil.exe`
## Explanation
The `model file` and the `software` are placed in `the same path`, and the software can be used normally. 
Import the captured human eye video file `xxx.mp4` and user information file `name.txt`, perform pupil detection and fitting through `pupil.exe`, and obtain the corresponding data file
## Result
Obtain the video file of the tester's pupil fitting (including the number of blinks), the pupil center position, and the pupil diameter data file.
