.. role:: math(raw)
    :format: latex html

Onsager Matrix Calculation
##########################

This repository contains a library ``onsager.py`` for calculating the Onsager matrix $L$ using the generalized Einstein formula:

:math:`$L_{\alpha\beta} = \lim_{t\to\infty}\frac{\left\langle \mathbf{R}_\alpha(t)\cdot \mathbf{R}_\beta(t)\right\rangle}{6t}$$`

where :math:`$\mathbf{R}_\alpha$` is the total displacement of atom type :math:`$\alpha$` and :math:`$t$` is time.

An example usage of this library is included in ``example.py``.