# AudioSignal

A MATLAB-based project for audio signal processing, including bird recognition, heart rate estimation, and loudness segmentation.

## Project Structure

- **Bird Recognition/**  
  MATLAB scripts and data for recognizing bird sounds using FFT and other signal processing techniques.
  - `Reference/`: Contains reference bird audio files (`bird1.wav`, `bird2.wav`, `bird3.wav`)
  - `Task/`: Contains task audio files (`F1.wav` to `F8.wav`)
  - `.fig` files: MATLAB figure files for visualizations

- **Heart Rate Estimation/**  
  MATLAB scripts and data for estimating heart rate from audio signals.
  - `.mat` files: MATLAB data files
  - `.fig` files: MATLAB figure files for results and analysis

- **Loudness Segmentation/**  
  MATLAB scripts for segmenting audio based on loudness.
  - `audios/`: Audio files in `.wav` and `.mp3` formats
  - `text/`: Corresponding text files for each audio
  - `.fig` files: MATLAB figure files for visualizations

- **Signals/**  
  Contains organized subfolders for each project with reference and task data.

## Requirements

- MATLAB (R2020a or later recommended)
- Signal Processing Toolbox

## How to Run

1. Clone this repository:
   ```powershell
   git clone https://github.com/Praveen-ing/AudioSignal.git
   ```
2. Open MATLAB and set the working directory to the project folder.
3. Run the desired `.m` script from the relevant subfolder.

## Authors

- Praveen-ing

## License

This project is licensed under the MIT License.

## Acknowledgements

- MATLAB documentation and Signal Processing Toolbox
