# Source code for reproducing the results and running the test suite

* `Makefile`

    Contains the rules to test the code and check its style consistency.
    At this folder, check the code consistency by executing

        make style

    and run the tests by executing

        make test

    This command runs the automated tests in the files `test_ellipsoids.py`,
    `test_triaxial_ellipsoid.py`, `test_prolate_ellipsoid.py` and `test_oblate_ellipsoid.py`.

    To see a brief description of the rules in the `Makefile`, run

        make help


* `mesher.py`

    Set of classes used to create geometric elements defining triaxial, prolate
    and oblate ellipsoids.

* `triaxial_ellipsoid.py`, `prolate_ellipsoid.py` and `oblate_ellipsoid.py`

    Set of routines to calculate, respectively, the magnetic induction produced by triaxial,
    prolate and oblate ellipsoids.

* [Cookbook_triaxial.ipynb](http://nbviewer.jupyter.org/github/pinga-lab/magnetic-ellipsoid/blob/master/code/Cookbook_triaxial.ipynb),
[Cookbook_prolate.ipynb](http://nbviewer.jupyter.org/github/pinga-lab/magnetic-ellipsoid/blob/master/code/Cookbook_prolate.ipynb) and
[Cookbook_oblate.ipynb](http://nbviewer.jupyter.org/github/pinga-lab/magnetic-ellipsoid/blob/master/code/Cookbook_oblate.ipynb)

    Notebooks illustrating, respectively, the computation of the total-field anomaly produced
    by triaxial, prolate and oblate ellipsoids.

* [demagnetizing_factors.ipynb](http://nbviewer.jupyter.org/github/pinga-lab/magnetic-ellipsoid/blob/master/code/demagnetizing_factors.ipynb)

    Notebook generating the results presented in the subsection 4.1 of the manuscript about
    the demagnetizing factors of triaxial, prolate and oblate ellipsoids.

* [confocal_triaxial_ellipsoids.ipynb](http://nbviewer.jupyter.org/github/pinga-lab/magnetic-ellipsoid/blob/master/code/confocal_triaxial_ellipsoids.ipynb)

    Notebook generating the results presented in the subsection 4.2 of the manuscript
    about the ambiguity between confocal ellipsoids with the same magnetic moment.

* [warrego.ipynb](http://nbviewer.jupyter.org/github/pinga-lab/magnetic-ellipsoid/blob/master/code/warrego.ipynb)

    Notebook generating the results presented in the subsection 4.3 of the manuscript about
    effect of neglecting the self-demagnetization in the magnetic modelling.

* [lambda_triaxial_ellipsoids.ipynb](http://nbviewer.jupyter.org/github/pinga-lab/magnetic-ellipsoid/blob/master/code/lambda_triaxial_ellipsoids.ipynb),
[lambda_prolate_ellipsoids.ipynb](http://nbviewer.jupyter.org/github/pinga-lab/magnetic-ellipsoid/blob/master/code/lambda_prolate_ellipsoids.ipynb) and
[lambda_oblate_ellipsoids.ipynb](http://nbviewer.jupyter.org/github/pinga-lab/magnetic-ellipsoid/blob/master/code/lambda_oblate_ellipsoids.ipynb)

    Notebooks illustrating the parameter lambda for, respectively, triaxial,
    prolate and oblate ellipsoids.

* [dlambda_prolate_ellipsoids.ipynb](http://nbviewer.jupyter.org/github/pinga-lab/magnetic-ellipsoid/blob/master/code/dlambda_prolate_ellipsoids.ipynb) and
[dlambda_oblate_ellipsoids.ipynb](http://nbviewer.jupyter.org/github/pinga-lab/magnetic-ellipsoid/blob/master/code/dlambda_oblate_ellipsoids.ipynb)

    Notebooks illustrating the computation of the spatial derivatives of the
    parameter lambda for, respectively, prolate and oblate ellipsoids.

* `plot_functions.py`

    Routines for saving figures and plot ellipsoids.

* [plot_ellipsoids.ipynb](http://nbviewer.jupyter.org/github/pinga-lab/magnetic-ellipsoid/blob/master/code/plot_ellipsoids.ipynb)

    Notebook illustrating the use of the routines in `plot_functions.py`.

* [demagnetizing_factors_Stoner1945.ipynb](http://nbviewer.jupyter.org/github/pinga-lab/magnetic-ellipsoid/blob/master/code/demagnetizing_factors_Stoner1945.ipynb)

    Notebook comparing the demagnetizing factors calculated with our routines (Eqs. 34 and 36) and those presented by
    Stoner (1945, Table I). The results presented by Stoner (1945, Table I) are in the file
    `Stoner1945_TableI.txt`, in the folder `data`.
