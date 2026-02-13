# Acoustic_Analysis
examining the different phonological properties of a language to map its salient features. The observations and interpretations for the Tamil data used with this code can be seen in [Overleaf](https://www.overleaf.com/read/gdkczvyszgwz#5f83a9)

## How to use:
-Get WAV audio files and their respective TextGrid annotations of the same name in a folder in the directory.

## Code structure
1. Use extract formants to get basic values like F1, F2, F3 and duration of the phonemes in the sound files which can be used for other statistical analyses.
2. bhm file can be used to calculate the Bark, Hertz and Mel values of each phonemein the sound files.
3. vot can be used to calculate the voice onset time of the consonants,preferabe in another data folder for efficient working of the code. The positiveor negative value of VOT must be inferred from the waveform analysis of the sound files.
4. diphthongs code can be used for getting the f0 value at 100 time points of the vowel to plot diphthong trajectory paths.
5. VowelPlot file takes select columns of the output of extract formants as input, and outputs individual and comparative vowel spaces and scatterplots of all the vowel entries.
   <table>
  <tr>
    <td><b>Original Stimulus (Edges)</b></td>
    <td><b>Grad-CAM Result </b></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/afe968fc-d88c-4132-aea8-de6aa0ddaaa8" width="300"></td>
    <td><img src="https://github.com/user-attachments/assets/8f530e4b-f5dc-4530-aa9c-11401ade36f4" width="300"></td>
  </tr>
</table>

## Installation and usage
1. Clone the repository:
```bash
   git clone [https://github.com/Darshini-CogSci/Acoustic_Analysis.git](https://github.com/Darshini-CogSci/Acoustic_Analysis.git)
