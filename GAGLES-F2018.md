---
title: Cubic Fourfolds, Rationality, etc.
subtitle: An episode of <a title="Graduate Algebraic Geometry LEarning Seminar">GAGLeS</a> organized by <span class="people"><a href="index.html">Raymond Cheng</a></span> during the fall of 2018.
---

Cubic fourfolds, i.e. nonsingular cubic hypersurface in projective five space,
pose one of the most tantalizing challenges to the modern algebraic geometer:
show that the very general cubic fourfold is not rational.
Maybe somewhat embarrassingly, there is not a single known example of a cubic
fourfold which is provably not rational!

This episode of GAGLeS will be focussed around cubic fourfolds and, to a large
extent, the techniques that have been developed to address their rationality.
Along the way, we will learn something about Hodge theory, period maps, K3
surfaces, hyperkähler manifolds, and derived categories.

## References

Below is a skewed and non-exhaustive collection of papers touching on the
geometry, moduli, and rationality of cubic fourfolds.
This will hopefully serve as a guide to the topics discussed in the seminar.

### Classical Geometry of Cubic Fourfolds

Cubic fourfolds are classical and surely would have been studied by the
Italians. Perhaps one of the most noteworthy classical studies on cubic
fourfolds was done by Fano, who, at some point, studied the variety of lines on
such hypersurfaces and who exhibited special cubic fourfolds containing quartic
scrolls and which are rational. The MathSciNet review of the following
paper is delightfully alien and at least makes me wonder what algebraic geometry
looked back then.

* G. Fano (1943),
[[Sulle forme cubiche dello spazio a cinque dimensioni contenenti rigate razionali del 4∘ ordine](https://link.springer.com/article/10.1007%2FBF02565634)]{.paper},
[MR0010433](https://mathscinet.ams.org/mathscinet/search/publdoc.html?pg1=MR&s1=10433){.MR}.

A modern classic in the theory of cubic fourfolds is one by Arnaud Beauville and
Ron Donagi on the Fano variety of lines on a cubic fourfold.
They show that the Fano variety is a hyperkähler manifold, deformation
equivalent to the Hilbert square of a K3 surface.
Beauville--Donagi achieve this by explicitly constructing a K3 surface whose
Hilbert square is the Fano variety of lines of a Pfaffian cubic fourfold, and
the rest is deformation theory.
This paper perhaps marks the beginning of a long story in so much modern
algebraic geometry.

* A. Beauville and R. Donagi (1985),
[[La variété des droites d'une hypersurface cubique de dimension 4][BD-lines]]{.paper},
[MR0818549](https://mathscinet.ams.org/mathscinet/search/publdoc.html?&pg1=MR&s1=818549){.MR}.

### Moduli and Periods

Cubic fourfolds, being hypersurfaces in a projective space, admit a simple
moduli space given as the set of cubic forms in 6 variables with non-vanishing
discriminant.
Perhaps a more interesting way to parameterize cubic fourfolds, and one which is
more amenable to the construction of a compact moduli space, is via period
mappings and Hodge theory.
Quite remarkably, as Claire Voisin established in her thesis, a global Torelli
theorem holds for cubic fourfolds, perhaps giving the first indication of the
importance and power of Hodge theory in the study of cubic fourfolds.
The geometry of the period domain and the properties of the period map have
since been clarified by Radu Laza, Eduard Looijenga, and others.

* C. Voisin (1986),
[[Théorème de Torelli pour les cubiques de \\(\\mathbf{P}^5\\)][Voisin-Torelli]]{.paper},
[[erratum][Voisin-Torelli-erratum]]{.paper},
[MR0860684](https://mathscinet.ams.org/mathscinet/search/publdoc.html?&pg1=MR&s1=0860684){.MR}.
* R. Laza (2009),
[[The moduli space of cubic fourfolds][Laza-moduli]]{.paper},
[MR2496456](https://mathscinet.ams.org/mathscinet/search/publdoc.html?&pg1=MR&s1=2496456){.MR}.
* E. Looijenga (2009),
[[The period map for cubic fourfolds][Loo-period]]{.paper},
[MR2507640](https://mathscinet.ams.org/mathscinet/search/publdoc.html?&pg1=MR&s1=2507640){.MR}.
* R. Laza (2010),
[[The moduli space of cubic fourfolds via the period map][Laza-period]]{.paper},
[MR2680429](https://mathscinet.ams.org/mathscinet/search/publdoc.html?&pg1=MR&s1=2680429){.MR}.

There are now several different proofs of the Torelli theorem for cubic
fourfolds.
Fraçois Charles has given a short proof based on Verbitsky's Torelli theorem for
hyperkähler manifolds;
Daniel Huybrechts and Jørgen Rennemo have given a proof by using the derived
Torelli theorem for K3 surfaces; and
Bayer et al. have given a variation of the Huybrechts--Rennemo proof using their
work on stability conditions on the Kuznetsov component of a cubic fourfold.

* F. Charles (2012),
[[A remark on the Torelli theorem for cubic fourfolds][Charles-Torelli]]{.paper}.
* D. Huybrechts and J. Rennemo (2016),
[[Hochschild cohomology versus the Jacobian ring, and the Torelli theorem for cubic fourfolds][HR-Torelli]]{.paper}.
* A. Bayer, M. Lahoz, E. Macrì, P. Stellari, and X. Zhao (2017),
[[The Torelli theorem for cubic fourfolds][BLMSZ-Torelli]]{.paper}.

### Hodge Theoretic Approach to Rationality

Toward something more familiar, I think Brendan Hassett is one of the first
modern algebraic geometers who systematically studied the rationality problem
for cubic fourfolds.
In his thesis, Hassett used Hodge theoretic methods to construct certain
divisors in the moduli of cubic fourfolds.
These divisors of _special cubic fourfolds_ contain an unexpected algebraic
cycle and are expected to contain all rational examples.
An important construction made here is that of the K3 associated with a cubic
fourfold; this K3, or rather its primitive Hodge structure, enters as the
orthogonal complement of the extra algebraic class in the primitive cohomology
of the cubic fourfold.

* B. Hassett (2000),
[[Special cubic fourfolds][Hassett-thesis]]{.paper},
[[abridged version][Hassett-thesis-abridged]]{.paper},
[MR1738215](https://mathscinet.ams.org/mathscinet/search/publdoc.html?&pg1=MR&s1=1738215){.MR}.

For a more recent and up-to-date account of these ideas, see also Hassett's
survey:

* B. Hassett (2016),
[[Cubic fourfolds, K3 surfaces, and rationality questions][Hassett-survey]]{.paper},
[MR3618665](https://mathscinet.ams.org/mathscinet/search/publdoc.html?&pg1=MR&s1=3618665){.MR}.

### Derived Category Approach to Rationality

A more recent perspective comes from a derived category point of view.
Specifically, Alexander Kuznetsov, partly inspired by the classical result of
Clemens--Griffiths on the non-rationality of a cubic threefold, has constructed
a derived category invariant which may be a new obstruction to rationality.
In the case of a cubic fourfold, this invariant looks like the derived category
of a K3 surface and Kuznetsov conjectures that a cubic fourfold is rational
precisely when this category can be realized as the derived category of an
honest K3 surface.

* A. Kuznetsov (2010),
[[Derived categories of cubic fourfolds][Kuz-K3-category]]{.paper},
[MR2605171](https://mathscinet.ams.org/mathscinet/search/publdoc.html?&pg1=MR&s1=2605171){.MR}.

A very readable guide to these ideas is Kuznetsov's survey article below.
For a further reference for derived category stuff, K3 categories, and relations
to rationality problems, see also the notes by Emanuele Macrì and Paolo
Stellari.
Also, notes by Asher Auel and Marcello Bernardara give a good account of how
Kuznetsov's approach to rationality fits into the larger picture of things, and
how it is, for instance, related to the Clemens--Griffiths result.

* A. Kuznetsov (2016),
[[Derived categories view on rationality problems][Kuz-survey]]{.paper},
[MR3618666](https://mathscinet.ams.org/mathscinet/search/publdoc.html?&pg1=MR&s1=3618666){.MR}.
* E. Macrì and P. Stellari (2018),
[[Lectures on non-commutative K3 surfaces, Bridgeland stability, and moduli spaces][MS-NCK3]]{.paper}.
* A. Auel and M. Bernardara (2016),
[[Cycles, derived categories, and rationality][AB-notes]]{.paper},
[MR3727501](https://mathscinet.ams.org/mathscinet/search/publdoc.html?&pg1=MR&s1=3727501){.MR}.

### Comparison Between Approaches, etc.

The Hodge theoretic viewpoint and the derived category viewpoint are closely
related.
Nicolas Addington and Richard Thomas seem to be the first to really work out the
precise relationship.
Daniel Huybrechts has since then expanded on this relation and have proved some
basic structure results for the Kuznetsov component of a cubic fourfold.

* N. Addington and R. Thomas (2014),
[[Hodge theory and derived categories of cubic fourfolds][AT-K3]]{.paper},
[MR3229044](https://mathscinet.ams.org/mathscinet/search/publdoc.html?&pg1=MR&s1=3229044){.MR}.
* D. Huybrechts (2017),
[[The K3 category of a cubic fourfold][Huy-K3]]{.paper},
[MR3705236](https://mathscinet.ams.org/mathscinet/search/publdoc.html?&pg1=MR&s1=3705236){.MR}.

One more approach to the rationality problem for cubic problems is a
baby motivic one due to Sergey Galkin and Evgeny Shinder.
Their approach is to find a relation between the class of a cubic fourfold and
its associated Fano variety of lines in the Grothendieck ring of varieties.
This relation together with the hypothesis that a certain element in the
Grothendieck ring is not a zero divisor implies that a very general
cubic fourfold is not rational.
Unfortunately, the non-zero divisor hypothesis seems likely to be false in view
of Lev Borisov's example which shows that the Lefschetz motive is actually a
zero divisor in the Grothendieck ring.
Nonetheless, the work of Galkin--Shinder suggest some further conditions for
when a cubic fourfold might be rational through geometric properties of the
associated Fano variety of lines, a direction further clarified by Nicolas
Addington.

* S. Galkin and E. Shinder (2014),
[[The Fano variety of lines and rationality problem for a cubic hypersurface][GS-Fano]]{.paper}.
* N. Addington (2016),
[[On two rationality conjectures for cubic fourfolds][Add-GS]]{.paper},
[MR3512874](https://mathscinet.ams.org/mathscinet/search/publdoc.html?&pg1=MR&s1=3512874){.MR}.

Finally, a helpful guide to the relationships between cubic fourfolds and K3
surfaces is contained in a set of slides by Daniel Huybrechts:

* D. Huybrechts (2018),
Hodge theory of cubic fourfolds, their Fano varieties, and associated K3 categories,
[1](assets/HuybrechtsLecture1.pdf),
[2](assets/HuybrechtsLecture2.pdf),
[3](assets/HuybrechtsLecture3.pdf),
[4](assets/HuybrechtsLecture4.pdf).

## Schedule

We meet Wednesdays in Mathematics Room ??? between 1:15PM and 2:30PM.

09/05
  ~ [Raymond Cheng]{.speaker},
  ~ [Introduction and Organization]{.title},
  ~ [[Beauville--Donagi (1985)][BD-lines]]{.people},
    [[Hassett (2000)][Hassett-thesis]]{.people},
    [[Hassett (2016)][Hassett-survey]]{.people}.

[09/]{.phantom}12
  ~ [No Seminar]{.speaker},
  ~ [Raymond in Italy]{.title}.

[09/]{.phantom}19
  ~ [Carl Lian]{.speaker},
  ~ [Hodge theory of Cubic Fourfolds]{.title}
  ~ [[Voisin (1986)][Voisin-Torelli]]{.people},
    [[Hassett (2000)][Hassett-thesis]]{.people},
    [[Hassett (2016)][Hassett-survey]]{.people},
    [Huybrechts Slides 2](assets/HuybrechtsLecture2.pdf){.people}.

[09/]{.phantom}26
  ~ [Dmitrii Pirozhkov]{.speaker},
  ~ [Torelli Theorem for Cubic Fourfolds]{.title},
  ~ [[Voisin (1986)][Voisin-Torelli]]{.people},
    [[Hassett (2000)][Hassett-thesis]]{.people},
    [[Hassett (2016)][Hassett-survey]]{.people},
    [Huybrechts Slides 2](assets/HuybrechtsLecture2.pdf){.people}.

10/03
  ~ [TBA]{.speaker},
  ~ [Special Cubic Fourfolds]{.title},
  ~ [[Hassett (2000)][Hassett-thesis]]{.people},
    [[Hassett (2016)][Hassett-survey]]{.people},
    [Huybrechts Slides 1](assets/HuybrechtsLecture1.pdf){.people}.

[10/]{.phantom}10
  ~ [TBA]{.speaker},
  ~ [K3 Surfaces Associated with Cubic Fourfolds]{.title},
  ~ [[Hassett (2000)][Hassett-thesis]]{.people},
    [[Hassett (2016)][Hassett-survey]]{.people},
    [Huybrechts Slides 2](assets/HuybrechtsLecture1.pdf){.people}.

[10/]{.phantom}17
  ~ [Noah Olander]{.speaker},
  ~ [Derived Categories of Cubic Fourfolds]{.title},
  ~ [[Kuznetsov (2010)][Kuz-K3-category]]{.people},
    [[Kuznetsov (2016)][Kuz-survey]]{.people},
    [[Macrì--Stellari (2018)][MS-NCK3]]{.people}.

[10/]{.phantom}24
  ~ [Dmitrii Pirozhkov]{.speaker},
  ~ [Kuznetsov Component of Cubic Fourfolds]{.title},
  ~ [[Kuznetsov (2010)][Kuz-K3-category]]{.people},
    [[Kuznetsov (2016)][Kuz-survey]]{.people},
    [[Macrì--Stellari (2018)][MS-NCK3]]{.people}.

[10/]{.phantom}31
  ~ [TBA]{.speaker},
  ~ [Hodge Theory and Derived Category of Cubic Fourfolds]{.title},
  ~ [[Addington--Thomas (2014)][AT-K3]]{.people},
    [[Huybrechts (2017)][Huy-K3]]{.people},
    [Huybrechts Slides 3](assets/HuybrechtsLecture3.pdf){.people}.

11/07
  ~ [TBA]{.speaker},
  ~ [Rationality and the Fano Variety of Lines, Reprise]{.title},
  ~ [[Galkin--Shinder (2014)][GS-Fano]]{.people},
    [[Addington (2016)][Add-GS]]{.people},
    [Huybrechts Slides 4](assets/HuybrechtsLecture4.pdf){.people}.

[11/]{.phantom}14
  ~ [TBA]{.speaker},
  ~ [---]{.title}.

[11/]{.phantom}24
  ~ [TBA]{.speaker}.
  ~ [---]{.title}.

[11/]{.phantom}28
  ~ [TBA]{.speaker},
  ~ [---]{.title}.

12/05
  ~ [TBA]{.speaker},
  ~ [---]{.title}.

[12/]{.phantom}12
  ~ [TBA]{.speaker},
  ~ [---]{.title}.

[Hassett-survey]: <https://link.springer.com/chapter/10.1007/978-3-319-46209-7_2>
[Hassett-thesis]: <https://www.math.brown.edu/~bhassett/papers/cubics/cubiclong.pdf>
[Hassett-thesis-abridged]: <https://link.springer.com/article/10.1023/A:1001706324425>
[Kuz-K3-category]: <https://link.springer.com/chapter/10.1007%2F978-0-8176-4934-0_9>
[Kuz-survey]: <https://link.springer.com/chapter/10.1007/978-3-319-46209-7_3>
[MS-NCK3]: <https://arxiv.org/abs/1807.06169>
[AB-notes]: <https://arxiv.org/abs/1612.02415>
[AT-K3]: <https://projecteuclid.org/euclid.dmj/1404824304>
[Huy-K3]: <https://www.cambridge.org/core/journals/compositio-mathematica/article/div-classtitlethe-k3-category-of-a-cubic-fourfolddiv/D925A24B93E4C0F9421328222402A5DA>
[GS-Fano]: <https://arxiv.org/abs/1405.5154>
[BD-lines]: <https://math.unice.fr/~beauvill/pubs/bd.pdf>
[Voisin-Torelli]: <https://eudml.org/doc/143409>
[Voisin-Torelli-erratum]: <https://link.springer.com/article/10.1007%2Fs00222-008-0116-z>
[Loo-period]: <https://link.springer.com/article/10.1007%2Fs00222-009-0178-6>
[Laza-period]: <http://annals.math.princeton.edu/2010/172-1/p14>
[Laza-moduli]: <http://www.ams.org/journals/jag/2009-18-03/S1056-3911-08-00506-7/>
[Charles-Torelli]: <https://arxiv.org/abs/1209.4509>
[HR-Torelli]: <https://arxiv.org/abs/1610.04128>
[BLMSZ-Torelli]: <https://arxiv.org/abs/1703.10839>
[Add-GS]: <http://intlpress.com/site/pub/pages/journals/items/mrl/content/vols/0023/0001/a001/index.html>
