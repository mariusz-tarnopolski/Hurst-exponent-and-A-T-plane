# Hurst exponent and A-T plane

Notebook Hurst_exponent.nb contains Mathematica implementations of algorithms for estimating the Hurst exponent: DWT, R/S, DFA, AWC, and from a FARIMA fit. It also contains an example of fractional Gaussian noise with H=0.75.

Notebook A-T_plane.nb contains the functions Abbe and turn for computing the Abbe value and the number of turning points of a time series. It also contains an example of fractional Gaussian noise with H=0.75, as well as a code for generating time series with a PSD given by a power law plus Poisson noise. The A-T plane is built for the pure PL case.

These codes were written in Mathematica v10.4.

If you use this implementations, please cite the corresponding paper:

M. Tarnopolski, N. Żywucka, V. Marchenko & J. Pascual-Granado, A comprehensive power spectral density analysis of astronomical time series I: the Fermi-LAT gamma-ray light curves of selected blazars, Astrophysical Journal Supplement Series, accepted, 2020, https://arxiv.org/abs/2006.03991

Bibtex entry:

@ARTICLE{2020arXiv200603991T,
       author = {{Tarnopolski}, Mariusz and {{\.Z}ywucka}, Natalia and
         {Marchenko}, Volodymyr and {Pascual-Granado}, Javier},
        title = "{A comprehensive power spectral density analysis of astronomical time series I: the Fermi-LAT gamma-ray light curves of selected blazars}",
      journal = {arXiv e-prints},
     keywords = {Astrophysics - High Energy Astrophysical Phenomena, Astrophysics - Astrophysics of Galaxies, Astrophysics - Instrumentation and Methods for Astrophysics},
         year = 2020,
        month = jun,
          eid = {arXiv:2006.03991},
        pages = {arXiv:2006.03991},
archivePrefix = {arXiv},
       eprint = {2006.03991},
 primaryClass = {astro-ph.HE},
       adsurl = {https://ui.adsabs.harvard.edu/abs/2020arXiv200603991T},
      adsnote = {Provided by the SAO/NASA Astrophysics Data System}
}
