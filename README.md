# nircam_grism

JWST NIRCam/WFSS Grism codes and data produced by Fengwu Sun et al.

If you have any question, please do not hesitate to contact me via my email: fengwu.sun在cfa.harvard.edu

If you find my workflow, codes and/or data products helpful, it would be great if you could acknowledge it in your research and cite our NIRCam grism commissioning paper at: [https://ui.adsabs.harvard.edu/abs/2023ApJ...953...53S/abstract](https://ui.adsabs.harvard.edu/abs/2023ApJ...953...53S/abstract).

I specially thank Eiichi Egami, Marcia Rieke, Nor Pirzkal and Christopher N. A. Willmer for their help with the codes, and numerous NIRCam WFSS users across the globe for their testing and usage.

#### v3.0 change (2024.07.31): 
- Include new tracing & wavelength calibration based on Commissioning + Cycle-1 + Cycle-2 calibration data taken in the SMP-LMC-58 field.
- The 1/f noise, background and continuum subtraction parts are improved.
- Fix a minor bug in the `extract_2d_spec` function for grism C.
- Include wavelength correction to barycentric coordinates.
- Re-structure the 1D spectral extraction and plotting code block. User can supply source morphology (`A`, `B` and `PA`) to run optimal extraction.
 
