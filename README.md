# CLM Mods

This is a repository of modified files for CLM setup in NorESM, for the purpose of modelling some side effects of BECCS.

## Overview
The source files and parameter files in this repository are supposed to work together with the stable release of NorESM/CTSM, specified to be [release-clm5.0.14-Nor_v1.0.4](https://github.com/NorESMhub/CTSM/tree/release-clm5.0.14-Nor_v1.0.4 "release specification on Github"). 

* Modified source files primary follow the update of Cheng [^2] to ESCOMPT/CTSM based on study of BECCS (Cheng et al. 2013 [^1])
  * but keeping some older subroutines for backward compatibility
* parameter file combines the "good" portions of previously used parameter files in order to fulfill requirements 
* land use files NOT included here due to size

## Sources

[^1]: Cheng, Y., Huang, M., Chen, M., Guan, K., Bernacchi, C., Peng, B. & Tan, Z. (2019). Parameterizing perennial bioenergy crops in Version 5 of the Community Land Model Based on Site‐Level Observations in the Central Midwestern United States. Journal of Advances in Modeling Earth Systems, 2(2013), 1–24. [doi.org/10.1029/2019MS001719](https://doi.org/10.1029/2019MS001719 "Chenge et al. 2013")
[^2]: [ESCOMP/CTSM/pull/884](https://github.com/ESCOMP/CTSM/pull/884 "Cheng's update")





