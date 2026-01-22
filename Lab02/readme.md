## Title:Basic sound processing and manipulation using python
## Objectives:
1. Load and play a sample sound clip(drum.wav)
2. Process and manipulate and audio signal
3. Perform audio using sign wave
4. Visualize audio waveform and spectrum properties
## Background Theory:
  
  Sound is a continuous analog signal produced by vibrations in the air. When this signal is recorded and handled by a computer, it is transformed into a digital form made up of numerical values. These digital samples allow the sound to be stored, played back, edited, and analyzed using software tools.

  Features:

   i) Represents sound as amplitude plotted against time.

   ii) Can be stored in formats such as WAV, MP3, and FLAC.

   iii)Supports digital operations like filtering, amplification, and noise removal.

   iv) Can be examined in both time-domain and frequency-domain views.

   Example: A microphone recording your voice becomes a list of sample values like [0.2, 0.4, 0.1, …].

  
 ## Sampling and Quantization
  
  Sampling captures sound at regular time intervals, while quantization assigns each sample a discrete numeric value. Together, they convert analog audio into digital form.

  Features:

   i) The sampling rate determines how often the signal is measured (e.g., 44.1 kHz for high-quality music).

  ii) Bit depth controls how accurately each sample is represented (e.g., 16-bit audio).

 iii) Higher sampling rates and bit depths improve sound quality and reduce distortion.

  iv) The Nyquist Theorem ensures proper sampling to prevent aliasing.

   Example: Telephone audio uses 8 kHz sampling, while studio audio uses 48 kHz for higher detail.

* PyDub
  
  PyDub is a Python library designed for straightforward audio editing and manipulation tasks. It provides simple commands for modifying and managing audio files efficiently.

  Features:

   i) Supports cutting, joining, and splitting audio clips.

   ii) Enables volume changes, fade effects, and speed adjustments.
  

  iii) Converts audio between different file formats (e.g., MP3 to WAV).
  

   iv) Works with FFmpeg for backend processing.
  

   Example: Trim a 10-second audio clip to 5 seconds using audio[:5000].

* Librose
  
  Librosa is an advanced Python library used for audio analysis, especially in music and machine-learning applications.

  Features:

   i) Generates spectrograms and mel-spectrograms.

  ii) Extracts MFCCs, chroma, tempo, and pitch.
  
 iii)  Provides tools for visualization and signal processing.
 
  iv) Used in speech recognition, music classification, and feature extraction.
  
   Example: Using Librosa to create a spectrogram to analyze the frequency content of a song.
  

## Procedure

 i. The required libraries, such as Pydub, Librosa, NumPy, and Matplotlib, had been imported.

ii. The sample audio file (drum.wav) had been loaded using either Pydub.

iii. The audio had been played in Python to verify that it had been loaded correctly.

iv. The audio had been processed and manipulated by performing tasks such as adjusting the volume, cutting or trimming sections, adding simple effects, and resampling or changing the playback speed.

v. The audio signal had been analyzed by converting it into a waveform (time-domain plot).

vi. The spectrogram had been computed and displayed using Librosa to observe the frequency content of the audio.

vii. A simple audio signal, such as a sine wave, had been synthesized using NumPy .



ix. Finally, the processed audio had been saved or exported using Pydub or Librosa.
## Output
The audio file drum.wav was successfully loaded and played using Pydub or Librosa. The waveform clearly displayed the time-domain representation, and the spectrogram showed the frequency distribution over time. A synthetic sine wave was created using NumPy, with both its waveform and spectrogram visualized successfully.


In this lab, audio was successfully loaded, analyzed, and processed using Pydub, Librosa, NumPy, and Matplotlib. Waveforms and spectrograms demonstrated time and frequency characteristics, while a synthetic sine wave was generated and visualized. The experiment highlighted key audio manipulations like trimming, volume adjustment, and resampling, reinforcing practical skills in digital audio processing.
