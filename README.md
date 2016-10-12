# Checking SDSS and other sources for ultra-short laser pulses

Recently, [Borra &amp; Trottier 2016](https://arxiv.org/abs/1610.03031) announced the detection of peculiar signals in the spectra of stars. Their method is described in an [earlier paper](https://ui.adsabs.harvard.edu/#abs/2012AJ....144..181B/abstract). Their [first search](https://ui.adsabs.harvard.edu/#abs/2013ApJ...774..142B/abstract) in SDSS data resulted in the detection of such signals only in (223) galaxies, and not in stars. 

The authors claim that these signals, now found in stars, may originate from ultra-short (100 femtoseconds) laser pulses, sent by ET.

All data analyzed by the authors were taken by the SDSS. As the SDSS sometimes observed a target more than once, we can check these other observations. We can also check the same objects (stars, galaxies) using other spectra taken from other telescopes.

The following figure is generated by the script "make_spectra_from_csv" for the object CGCG 390-073. This is a galaxy which was found by Borra 2013 to exhibit such a signal:
![ScreenShot](http://www.jaekle.info/CGCG 390-073-SDSS.png)

However, if we repeat the analysis using a different dataset taken by another telescope, the signal is gone:
![ScreenShot](http://www.jaekle.info/CGCG 390-073-NED.png)

Possible causes for the discrepancy:
* Instrumental or reduction artefact which occurs only sometimes
* Noise
* Natural, but astrophysical phenomenon
* Laser-pulse, but duty cycle <1

A similar analysis can be repeated for all sources given in their 2016 paper, table 1. One can compare all SDSS observations, and data taken by other telescopes, and of course one can take new data. I have checked several (7) examples and never found a signal in two independent datasets of the same object.

I have also performed Fourier transforms for QSOs using SDSS data, and found the same signals to be present. QSOs are a much worse home to ET than FGK stars. Therefore, I tend to believe that the cause for these signals is not ET, but either an instrumental effect, data reduction issues, or noise.
