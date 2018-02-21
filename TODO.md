Pseudoprimality tests
=====================

-   [Miller-Rabin](https://en.wikipedia.org/wiki/Miller–Rabin_primality_test)
-   [Fermat](https://en.wikipedia.org/wiki/Fermat_pseudoprime)
-   [Lucas](https://en.wikipedia.org/wiki/Lucas_pseudoprime)
-   [Baillie-PSW](https://en.wikipedia.org/wiki/Baillie%E2%80%93PSW_primality_test)
-   Deterministic variants of Miller-Rabin

Elliptic curves
===============

-   Weierstrass form
-   Montgomery form
-   Generic class for other int implementations
-   For Montgomery: [PRAC and safe
    Ladder](https://arxiv.org/pdf/1703.01863.pdf)

Other references:
-----------------

-   <https://wstein.org/edu/124/lenstra/lenstra.pdf>
-   <https://wstein.org/edu/124/misc/montgomery.pdf>
-   <https://wstein.org/edu/124/misc/arjen_lenstra_factoring.pdf>
-   <https://wstein.org/edu/124/misc/koblitz_ecc.pdf>

gmpy2 support
=============

-   [gmpy2](https://github.com/aleaxit/gmpy) support for elliptic curves
-   implement alternative faster sieves using
    [gmpy2](https://gmpy2.readthedocs.io/en/latest/advmpz.html) or numpy
-   interface the [Advanced Number Theory Functions from
    gmpy2](https://gmpy2.readthedocs.io/en/latest/advmpz.html#advanced-number-theory-functions)
    and replicate them in pure Python for compatibility

Factorization algorithms
========================

-   [Lenstra's
    algorithm](https://wstein.org/edu/124/lenstra/lenstra.pdf) on
    elliptic curves
-   Multiple-polynomial quadratic sieve
-   Parallelism with
    [SCOOP](https://scoop.readthedocs.io/en/0.7/api.html?highlight=futures#scoop.futures.as_completed)
-   Hart's one line factoring algorithm
    ([pdf](http://wrap.warwick.ac.uk/54707/1/WRAP_Hart_S1446788712000146a.pdf))
-   Other algorithms from
    [primefac](https://pypi.python.org/pypi/primefac)

Maybe
=====

-   Multiprocessing support: better than SCOOP locally and because of
    the ability to terminate
-   [General number field
    sieve](https://wstein.org/129/references/Lenstra-Lenstra-Manasse-Pollard-The%20number%20field%20sieve.pdf),
    see also <https://github.com/radii/msieve>