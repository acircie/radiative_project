# radiative_project
Final Project for the Radiative Processes Class.
The goal of the project is to reproduce a toy model for the spectrum of a Blazar, 
with tweakable parameters.

The spectra are computed using the agnpy package ([docs](https://agnpy.readthedocs.io/en/latest/)),
which is based on the results from [Finke et al. (2008)](https://ui.adsabs.harvard.edu/abs/2008ApJ...686..181F/abstract) and [Dermer and Menon (2009)](https://ui.adsabs.harvard.edu/abs/2009herb.book.....D/abstract).

I use this package to carry out the computation of Synchrotron emission and Synchrotron-Self-Compton emission from a spherical region filled with relativistic electrons with a power-law distribution of energies, to simulate the face-on observation of a blazar-like source.

In 'fixed_parameters' I showcase the functionalities of the package for my case of study, fixing the emission region and the electron distribution and reporting the formulae used to compute the SEDs "behind the scenes". <a target="_blank" href="https://colab.research.google.com/github/acircie/radiative_project/blob/main/fixed_parameters.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

In 'variable_electrons' I compute the spectrum of the toy model fixing the emission region parameters and variating the distribution of electrons. <a target="_blank" href="https://colab.research.google.com/github/acircie/radiative_project/blob/main/variable_electron.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

In 'variable_region' I compute the spectrum for a fixed electron distribution, tweaking the definition of the emission region. <a target="_blank" href="https://colab.research.google.com/github/acircie/radiative_project/blob/develop/variable_region.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

In the first two, the computation is first performed for Synchrotron and SSC emissions separately and then again for the combined SED.
Since the emission regions depends on more parameter, to reduce the length of the notebook, the individual determinations of the Synchrotron and SSC spectra are carried out separately in  'variable_region_synch' <a target="_blank" href="https://colab.research.google.com/github/acircie/radiative_project/blob/main/variable_region_synch.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a> and 'variable_region_ssc' <a target="_blank" href="https://colab.research.google.com/github/acircie/radiative_project/blob/main/variable_region_ssc.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>.
