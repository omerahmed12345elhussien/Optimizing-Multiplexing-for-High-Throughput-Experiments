# Optimizing Multiplexing for High Throughput Experiments
Reproducibility is often hard to achieve in high throughput experiments due to missing calibration which holds particularly for proteomic mass spectrometry data.
This fact posses a great problem at the analysis stage. To solve the arising situation, we employ a variety of multiplexing kits for a specific labelling of every sample, mixed and analysed as a single experiment. We adopt the commonly used $4 - 8$ markers and fight to increase the number of samples that we can possibly mark with the given limited number of markers. Using the concept of orthogonal arrays, we create a connection with the problem in question. We adopt two main methods, the Bush's method from finite field and the Rao-Hamming method from error-correcting code to create the orthogonal arrays. With the former, we are able to mix $6$ samples using $4$ markers while the latter is capable of mixing $14$ samples with $8$ markers. Finally, we seek by simulation an optimal setup which is able to analyse a higher number of samples in a single trial. We successfully obtained a number of mixture setups capable of combining $12$ samples using $6$ markers and $14$ samples using $8$ markers. We determined the effect of different levels of noise from different probability distributions on the mixture setups we obtained.
## Repository contents
* The simulation part is implemented in [Codes](Codes.rar). It is done in R.
* [OMER_Essay_2016-2017](OMER_Essay_2016-2017.pdf) contains the full project. 
