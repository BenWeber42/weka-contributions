# Contributions to WEKA

I was fortunate enough to be offered a summer project scholarship
by the University of Waikato. Under the supervision of Professor Eibe Frank I contributed three different subprojects:

The biggest project was the unification of three different domain specific languages (DSL)
in `expressionlanguage`. I unified three existing DSLs into one using an improved design
and added some major performance optimizations.

Next, I implemented the PAA & SAX transformation in `timeseries`.
This implementation is more general than existing implementations (at that time).

Lastly, I changed the implementation for the computation of the standard deviation
in `stddev`.
The previous implementation had numerical stability issues which I discovered when
testing the PAA & SAX transformation.
Additionally, I generated very hard test cases with Python's unlimited precision fractions.
