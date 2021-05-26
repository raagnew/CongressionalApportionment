# CongressionalApportionment
Alternative US congressional apportionments based on 2020 Census state populations.

Apportionment is essentially a constrained rounding problem.  States have target unrounded quotas based on House of Representatives stipulated size (435) and their respective populations per the decennial census.  The objective is to round these quotas fairly within the House size constraint.

Apportionment has been contentious since the founding of our republic.  Various methods have been suggested and used; some have proven to be faulty.  So-called divisor methods avoid gross paradoxes, but there are alternatives within that mix and they don't always agree.

In their comprehensive monograph, Balinski & Young (https://www.brookings.edu/book/fair-representation/) argue that the current legislated apportionment method (Hill, aka "equal proportions"), in use since 1941, unduly favors small states.  The 2020 result appears to illustrate that.  Balinski & Young favor the Webster method.  Webster is based on the simple arithmetic mean, familiar to everyone.  Hill is based on the geometric mean, slightly more complicated.  The identric mean alternative has some theoretical advantages, despite increased complexity, and it appears to have performed logically in both 2010 and 2020.
