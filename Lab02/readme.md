## Title:Basic sound processing and manipulation using python
## Objectives:
1. Load and play a sample sound clip(drum.wav)
2. Process and manipulate and audio signal
3. Perform audio using sign wave
4. Visualize audio waveform and spectrum properties
## Background Theory:
  
  Sound is a continuous analog signal produced by vibrations in the air. When this signal is recorded and handled by a computer, it is transformed into a digital form made up of numerical values. These digital samples allow the sound to be stored, played back, edited, and analyzed using software tools.

  Features:

  1)  Represents sound as a variation of amplitude over time.

  2) Can be stored in standard file formats such as WAV, MP3, and FLAC.

  3) Supports digital operations including filtering, amplification, and noise reduction.

  4) Can be analyzed in both the time domain and the frequency domain.

  

  
 ## Sampling and Quantization
  
 Digital audio is created through two main processes: sampling and quantization.

  Sampling involves measuring the sound signal at fixed time intervals. The number of samples taken per second is called the sampling rate (for example, 44.1 kHz for CD-quality audio).

  Quantization assigns each sample a discrete numerical value based on the system’s bit depth (for example, 16-bit or 24-bit audio).


* PyDub
  
  PyDub is a Python library designed for straightforward audio editing and manipulation tasks. It provides simple commands for modifying and managing audio files efficiently.

  Features:
  1) Allows trimming, merging, and splitting of audio segments.

  2) Supports volume control, fade-in and fade-out effects, and  playback speed changes.

  3) Enables conversion between different audio formats such as MP3 and WAV.

  4) Uses FFmpeg as a backend for audio processing.
  

 


  
  

## Procedure

i. The necessary libraries, including PyDub, Librosa, NumPy, and Matplotlib, were imported.

ii. The sample audio file (drum.wav) was loaded using PyDub.

iii. The audio file was played to confirm that it was successfully loaded.

iv. The signal was processed by performing operations such as adjusting volume, trimming sections, applying simple effects, and modifying playback speed or sampling rate.

v. The audio data was converted into a waveform and displayed to observe its time-domain characteristics.

vi. A spectrogram was generated using Librosa to visualize the distribution of frequencies over time.

vii. A synthetic audio signal, such as a sine wave, was created using NumPy for demonstration purposes.

viii. The processed and generated audio files were saved or exported using PyDub or Librosa.


## Output
The audio file drum.wav was successfully loaded and played using Pydub or Librosa. The waveform clearly displayed the time-domain representation, and the spectrogram showed the frequency distribution over time. A synthetic sine wave was created using NumPy, with both its waveform and spectrogram visualized successfully.

