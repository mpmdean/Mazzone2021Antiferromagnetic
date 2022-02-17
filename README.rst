==========================================================
Data Repository
==========================================================
Source code and data files for the manuscript Antiferromagnetic Excitonic Insulator State in Sr3Ir2O7. Execute plot.ipynb to view the data.

.. image:: https://zenodo.org/badge/364675326.svg
   :target: https://zenodo.org/badge/latestdoi/364675326

How to cite
-----------
If this data is used, please cite, Antiferromagnetic Excitonic Insulator State in Sr3Ir2O7, D. G. Mazzone, Y. Shen, H. Suwa, G. Fabbris, J. Yang, S-S. Zhang, H. Miao, J. Sears, Ke Jia, Y. Shi, M. H. Upton, D. M. Casa, X. Liu, J. Liu, C. D. Batista, and M. P. M. Dean.
`Nature Communications volume 13, Article number: 913 (2022) <https://doi.org/10.1038/s41467-022-28207-w>`_

Excitonic insulators are usually considered to form via the condensation of a soft charge mode of bound electron-hole pairs. This, however, presumes that the soft exciton is of spinsinglet character. Early theoretical considerations have also predicted a very distinct scenario, in which the condensation of magnetic excitons results in an antiferromagnetic excitonic insulator state. Here we report resonant inelastic x-ray scattering (RIXS) measurements of Sr3Ir2O7. By isolating the longitudinal component of the spectra, we identify a magnetic mode that is well-defined at the magnetic and structural Brillouin zone centers, but which merges with the electronic continuum in between these high symmetry points and which decays upon heating concurrent with a decrease in the material’s resistivity. We show that a bilayer Hubbard model, in which electron-hole pairs are bound by exchange interactions, consistently explains all the electronic and magnetic properties of Sr3Ir2O7 indicating that this material is a realization of the long-predicted antiferromagnetic excitonic insulator phase.

Run locally
-----------

Work with this by installing `docker <https://www.docker.com/>`_ and pip and then running

.. code-block:: bash

       pip install jupyter-repo2docker
       jupyter-repo2docker --editable .

Change `tree` to `lab` in the URL for JupyterLab.

Run remotely
------------


.. image:: https://mybinder.org/badge_logo.svg
 :target: https://mybinder.org/v2/gh/mpmdean/Mazzone2021Antiferromagnetic/HEAD?filepath=plot.ipynb
