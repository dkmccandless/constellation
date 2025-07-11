Package constellation implements Nancy Roman's table-based lookup algorithm for determining the IAU designated constellation containing an astronomical coordinate pair, described in _Identification of a Constellation from a Position_ (1987).

Call At with a right ascension in hours and declination in degrees.

Note that the boundaries of the constellations are defined in the Besselian year 1875.0 epoch; coordinates in other epochs, such as B1950.0 or J2000.0, must be precessed to B1875.0 before calling At.
