#################################
Energie et puissance de chauffage
#################################

.. _energie-de-transfert-thermique:

Energie de transfert thermique
==============================

Le chauffage, ou l'élévation de température, d'un corps se produit au contact ou au voisinage d'un autre corps de température plus élevée. Il se produit alors un transfert d'énergie, le `transfert thermique`_, du corps le plus chaud vers le plus froid jusqu'à équilibre de la température des deux corps.

Dans ces conditions, la quantité d'énergie nécessaire pour élever la température d'un corps de masse :math:`m` de la température :math:`t_1` à la température :math:`t_2` dépend de sa `capacité thermique massique`_ :math:`C_m`. Cette quantité d'énergie :math:`Q` est calculée par la formule suivante :

.. math::

 \Delta_\theta=(t_2-t_1)

 Q = m.C_m.\Delta_\theta

avec :

* :math:`Q` l'énergie nécessaire exprimée en Joules (J)
* :math:`m` exprimée en grammes (g)
* :math:`\Delta_\theta` exprimée en Kelvin (K)

.. topic:: Application numérique

 La capacité thermique massique de l'eau à l'état liquide étaestnt de :math:`4,185 J.g^{-1}.K^{-1}`. Ainsi, la quantité d'énergie nécessaire pour augmenter la température de :math:`1kg` d'eau de :math:`1K` est égale à :

 .. math::
  Q = 1000g\times4,185\times1K = 4185 J

.. _transfert thermique: http://fr.wikipedia.org/wiki/Transfert_thermique
.. _capacité thermique massique: http://fr.wikipedia.org/wiki/Capacit%C3%A9_thermique_massique

Puissance de chauffage
======================

La `puissance thermique`_, ou puissance de chauffage, désigne la :ref:`quantité d'énergie <energie-de-transfert-thermique>` qu'un système fourni par unité de temps. Dans le `système international d'unités`_ cette puissance s'exprime en watts (:math:`W`) et correspond à la quantité d'énergie qu'un système produit en 1 seconde :

.. math::

 1 W = 1 J.s^{-1}

Ainsi, un système dont la puissance est de 1000 watts produit une énergie de 1000 joules par seconde. Un tel système sera donc capable d'augmenter la température de :math:`1kg` d'eau en :

.. math::

 t = \frac{4185 J}{1000 W} = 4,185 s

Pour les TP, essayez avec une bouilloire !

.. topic:: Application numérique

 Etant donné un volume d'eau de :math:`20l` [#f1]_ à la température initiale de :math:`15^\circ c`, quelle est la puissance de chauffage nécessaire pour porter ce volume à ébullition (:math:`100^\circ c`) en 30 minutes ?

 Réponse :

  * L'énergie nécessaire pour amener les :math:`20l` d'eau à ébullition est égale à :

  .. math::
   Q = 20000g\times4,185\times (100-15) = 7114500J

  * Pour produire cette énergie en 30 minutes il faut disposer d'un système capable de fournir une puissance de chauffage égale à :

  .. math::

   P = \frac{7114500}{30\times60} = 3952 W

.. _puissance thermique: http://fr.wikipedia.org/wiki/Puissance_(physique)#Puissance_thermique
.. _système international d'unités: http://fr.wikipedia.org/wiki/Syst%C3%A8me_international_d%27unit%C3%A9s

.. rubric:: Footnotes

.. [#f1] Masse volumique de l'eau : :math:`1l = 1kg` à :math:`4^\circ c`.