# Pitch shift
Various overlap-add (OLA), synchronized overlap-add (SOLA), waveform similarity overlap-add (WSOLA), and phase vocoder algorithms  
Purely educational and should not be used for anything ...  
Requires `librosa`, `numpy`, and `IPython`, optionally `matplotlib` for displaying spectrograms

Jupyter Notebook organization:
* OLA
  * direct pitch shift
    * OLA
    * SOLA
  * time scale, playback rate change
    * OLA
    * SOLA
    * WSOLA
* Phase vocoder
  * ignore transients
    * direct pitch shift
    * scale hop length
    * time scale, playback rate change
  * add transients back in
    * direct pitch shift
    * scale hop length
    * time scale, playback rate change
