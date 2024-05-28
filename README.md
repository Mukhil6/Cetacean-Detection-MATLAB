This project can be used to detect cetacean whistles using the following methods of feature extraction : Mel - Frequency Cepstrum Coefficients , Short Time Fourier Transform [STFT],
and Wavelet Transform. The project uses Dynamic Time Warping [DTW] to classify the species. You can replace the synthetic templates I have used with actual cetacean recordings.
My project was based on this research paper: https://ieeexplore.ieee.org/abstract/document/9385855
For cetacean noise samples: https://oceanexplorer.noaa.gov/explorations/sound01/background/seasounds/seasounds.html
Other sources used to make this project:
https://www.encyclopedie-environnement.org/en/life/listening-to-cetaceans/ (for the cetacean whistle range[0 to 20khz])
https://in.mathworks.com/help/signal/ref/stft.html (To calculate the stft)
https://www.researchgate.net/figure/Sample-spectrogram-representing-a-bottlenose-dolphin-whistle-Parameters-manually_fig2_258859719 ([bottlenose dolphin whistle range [7 khz to 14 khz])(Mean minimum and maximum frequency ranges)
https://www.researchgate.net/figure/Spinner-Dolphin-whistle-showing-the-fundamental-frequency-or-whistle-contour-and-two_fig1_8450285([Spinner Dolphin whistle range 10.58khz - 13.96 khz])
https://royalsocietypublishing.org/doi/10.1098/rstb.2021.0046 ([Common dolphin frequency range 5-15khz])
https://www.fisheries.noaa.gov/feature-story/artificially-increased-noise-has-profound-effect-gray-whale-calling-behavior([gray whales whistle range 100-2000hz])
https://arxiv.org/pdf/2211.01065v2.pdf ([ Cetaceans produce vocalisations that are periodic in nature and these signals may be modelled as amplitude - frequency modulated sinusoids])
