# A nonogram solver in Prolog

This is a nonogram solver we have written for a course at the "Universität Leipzig",
for the applied part of the [knowledge representation course][course]
there.

[course]: http://www.informatik.uni-leipzig.de/~brewka/KRoutline.html

## Solution strategy

Our nonogram solver tries to solve nonograms with two steps:

1. "Forcing" cells that must have a certain value. (See [nonogram.pl](./nonogram.pl)
    for details.)
2. "Guessing" values, trying cells with a small number of possibilities first.

## References

* A [different solution][klemens], using a similar guessing strategy, by another
    student taking the same course. (The sorting our solver uses is inspired by
    the presentation of this one, as it didn't occur to us that sorting/optimizing
    is as simple as it is.)

[klemens]: https://gist.github.com/klemens/b61f141ade46da56fc7d
