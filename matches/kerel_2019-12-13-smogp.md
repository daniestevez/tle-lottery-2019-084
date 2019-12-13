Data used
---------

| filename | satellite / transmitter
-|-
2019-12-11T23:53:49_437.150_8650_44832.dat | SMOG-P


Candidate TLEs used
-------------------
norad id | epoch | source
-|-|-
44827 | 19346.579100 | celestrak
44828 | 19346.578067 | celestrak
44829 | 19341.589213 | celestrak
44830 | 19343.188167 | celestrak
44831 | 19344.595203 | celestrak
44832 | 19343.060075 | celestrak
-|-|-
94832 | 19343.060075 | this analysis

Notes
-----

All candidate objects are running too late.
Measured TCA at station 8650: `2019-12-11T23:53:24`

norad id | TCA @ 8650
-|-
44832 | 2019-12-11T23:53:49
44831 | 2019-12-11T23:54:11
44830 | 2019-12-11T23:54:21
44829 | 2019-12-11T23:54:31
44828 | 2019-12-11T23:54:37
44827 | 2019-12-11T23:55:49
-|-
94832 | 2019-12-11T23:53:24


Fit results
-----------

transmitter | candidate norad id | candidate TLE epoch | center freq/Mhz | residuals/kHz
-|-|-|-|-
SMOG-P | 44827 | 19346.579100 | 437.144 | 5.792
SMOG-P | 44828 | 19346.578067 | 437.147 | 3.808
SMOG-P | 44829 | 19341.589213 | 437.147 | 3.603
SMOG-P | 44830 | 19343.188167 | 437.147 | 3.194
SMOG-P | 44831 | 19344.595203 | 437.148 | 2.706
SMOG-P | 44832 | 19343.060075 | 437.149 | 1.499
-|-|-|-|-
SMOG-P | 94832 | 19343.060075 | 437.150 | 0.064


Analysis results
----------------

As the elements are getting old and SMOG-P is running early there
is only a reduced significance in fitting the TLEs directly when 
trying to find the correct assignment, as this will always result in the
selection of the candidate object running earliest in the group.

To allow precise radio tracking with correct timings, the following TLE was generated
for SMOG-P based on the latest 44832 candidate object TLE by accepting the mean anomaly as 
a free parameter when fitting to the data (by VK5QI at `2019-12-11T23:53:49Z`):

```
0 SMOG-P
1 94832U          19343.06007526  .00000000  00000-0  00000-0 0    05
2 94832  97.0009 207.1982 0040316 243.1745 118.1536 15.64662868    09
```

The fit results for this TLE can be found in the previous section (64 Hz).
