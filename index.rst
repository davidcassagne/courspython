.. Cours documentation master file, created by
   sphinx-quickstart on Sat Aug 30 15:38:24 2014.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Ceci est un premier test de documentation
=========================================

Math
====

This is a test. Here is an equation:
:math:`X_{0:5} = (X_0, X_1, X_2, X_3, X_4)`.
Voici une nouvelle équation :
:math:`a^2+b^2=c^2` qui est sur la même ligne.
Here is another:

.. math::
    :label: This is a label

    \nabla^2 f =
    \frac{1}{r^2} \frac{\partial}{\partial r}
    \left( r^2 \frac{\partial f}{\partial r} \right) +
    \frac{1}{r^2 \sin \theta} \frac{\partial f}{\partial \theta}
    \left( \sin \theta \, \frac{\partial f}{\partial \theta} \right) +
    \frac{1}{r^2 \sin^2\theta} \frac{\partial^2 f}{\partial \phi^2}

You can add a link to equations like the one above :eq:`This is a label` by using ``:eq:``.


Contents:

.. toctree::
   :maxdepth: 2

   densite_etats.rst

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

