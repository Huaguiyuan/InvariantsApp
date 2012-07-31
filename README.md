InvariantsApp
=============

Application developed in undergraduate research about computing topological invariants.

Currently, it is computing Jones Polynomial and Kauffman Polynomial X correctly.
Unfortunately, there are a bug in the algorithm for computing the Kauffman Polynomial F (not known yet). It is computing correctly for some knot.

Possible future improvement: re-code the algorithm for Kauffman Polynomial X using bit mask. It will probably improve its performance.

The number of Thurston-Bennequin and Maslov (Rotation) is computed using the projection of a topological knot. The algorithm makes the changes (not visible) to approximate to a Legendrian knot, and then, compute these numbers.

Probably this project will be discontinued.