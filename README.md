# radiative_project
Final Project for the Radiative Processes Class.
The goal of the project is to reproduce a toy model for the spectrum of a Blazar, 
with tweakable parameters.

The spectra are computed using the agnpy package ([docs](https://agnpy.readthedocs.io/en/latest/)),
which is based on the results from [Finke et al. (2008)](https://ui.adsabs.harvard.edu/abs/2008ApJ...686..181F/abstract) and [Dermer and Menon (2009)](https://ui.adsabs.harvard.edu/abs/2009herb.book.....D/abstract).

I use this package to carry out the computation of Synchrotron emission and Synchrotron-Self-Compton emission from a spherical region filled with relativistic electrons with a power-law distribution of energies, to simulate the face-on observation of a blazar-like source.

In ['fixed_parameters'](https://colab.research.google.com/drive/1lqaaPylqCMJOV4CoT686kws0s1iBEEIr#scrollTo=WX1cvCeakc83) I showcase the functionalities of the package for my case of study, fixing the emission region and the electron distribution and reporting the formulae used to compute the SEDs "behind the scenes".

In ['variable_electrons']() I compute the spectrum of the toy model fixing the emission region parameters and variating the distribution of electrons.

In ['variable_region']() I will compute the spectrum for a fixed electron distribution, tweaking the definition of the emission region.

In all three files, the computation is first performed for Synchrotron and SSC emissions separately and then again for the combined SED.


An outline of the project running on colab can be found [here](https://colab.research.google.com/drive/1AyK1ziMVhhf6KXTRsbTPu3JsLB648nqB?usp=sharing)
