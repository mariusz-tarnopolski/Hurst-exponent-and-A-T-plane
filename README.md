# Hurst exponent and A-T plane

Notebook Hurst_exponent.nb contains Mathematica implementations of algorithms for estimating the Hurst exponent: DWT, R/S, DFA, AWC, and from a FARIMA fit. It also contains an example of fractional Gaussian noise with H=0.75.

Notebook A-T_plane.nb contains the functions Abbe and turn for computing the Abbe value and the number of turning points of a time series. It also contains an example of fractional Gaussian noise with H=0.75, as well as a code for generating time series with a PSD given by a power law plus Poisson noise. The A-T plane is built for the pure PL case.

These codes were written in Mathematica v10.4.

If you use these implementations, please cite the corresponding paper:

M. Tarnopolski, N. Żywucka, V. Marchenko & J. Pascual-Granado, A Comprehensive Power Spectral Density Analysis of Astronomical Time Series. I. The Fermi-LAT Gamma-Ray Light Curves of Selected Blazars, Astrophysical Journal Supplement Series, 250, 1 (2020); https://arxiv.org/abs/2006.03991

Bibtex entry:

@article{Tarnopolski_2020,
	doi = {10.3847/1538-4365/aba2c7},
	url = {https://doi.org/10.3847/1538-4365/aba2c7},
	year = 2020,
	month = {aug},
	publisher = {American Astronomical Society},
	volume = {250},
	number = {1},
	pages = {1},
	author = {Mariusz Tarnopolski and Natalia {\.{Z}}ywucka and Volodymyr Marchenko and Javier Pascual-Granado},
	title = {A Comprehensive Power Spectral Density Analysis of Astronomical Time Series. I. The Fermi-{LAT} Gamma-Ray Light Curves of Selected Blazars},
	journal = {The Astrophysical Journal Supplement Series}
}
