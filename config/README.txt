vtest01
------------
Testing new egret simulation with shear maker in the sim maker

v11
---
300 random shears, ranging from -0.08 to 0.08, following the
same distribution as great3: uniform in |shear|

100 million objects

v10
---
300 random shears, ranging from -0.05 to 0.05, following the
same distribution as great3: uniform in |shear|.

2,000,000 objects




# v04 and vd04 are using the new egret interface, trying to match v3
v04
    all standard settings.  1,000 per file, 2,000 files for 2,000,000 total
    objects

# do we need to even run a new deep field?
vd04
    all standard settings.  1000 per file, 100 files for 100,000 total
    objects

# for v05 we can re-use the deep field from vd04
v05
    all standard settings.  10,000 per file, 2,000 files for 20,000,000 total
    objects

v06
-0.08
v07
0.04
v08
-0.04


v09
---
1,000,000 zero shear but noise of great3

