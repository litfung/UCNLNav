# UCNLNav

This library contains routines for:
- Solving geodetic problems (C#/Rust/Matlab)
- Solving TDOA & TOA positioning/navigation problems in 2D & 3D (C#/Rust/Matlab)
- Algorithms for Virtual Long Baseline positioning (C#)  

# Example of TDOA problem
- Known times of arrival to/from base points with known locations
- Known target depth    
![](https://github.com/ucnl/UCNLNav/blob/master/Docs/Pics/problem.png)    
Calculated desudual function:    
![](https://github.com/ucnl/UCNLNav/blob/master/Docs/Pics/TDOA_2D_res_surf.png)    
Residual function and estimated target location:    
![](https://github.com/ucnl/UCNLNav/blob/master/Docs/Pics/TDOA_2D_res_cont.png)    

## WARNING!

If this repository achieves:

- DONE! 25 stars - we'll add partial implementation in MATLAB (Ok, I have uploaded Matlab version on 20 stars =)
- 50 stars - we'll add AoA (Angle of arrival) estimation routines  
- 100 stars - we'll add C implementation of the library  
- 150 stars - we'll add complete documentation for the library  

## HISTORY

23-JAN-2020 Update:
* Added partial implementation of the library in Matlab  
To test the functionality, please, use:
- [TOA & TDOA localisation demo script](https://github.com/ucnl/UCNLNav/blob/master/Matlab/Nav_TOA_TDOA_2D_demo.m) 
- [Geodetic problems: Haversine vs. Vincenty demo](https://github.com/ucnl/UCNLNav/blob/master/Matlab/Nav_Haversine_Vs_Vincenty_demo.m)
- [Library tests](https://github.com/ucnl/UCNLNav/blob/master/Matlab/Nav_tests.m)  


30-NOV-2019 Update:
* Added partial implementation of the library in Rust:
- All the functionality from Algorithms.cs & from Navigation.cs


22-NOV-2019 Update:  
* In GeoPoints.cs new classes for metric point (MPoint and MPoint3D)  
* In Navigation.cs new methods for calculating centroids of clouds of MPoint and MPoint3D, 
converting between local and geographic coordinate systems, methods for calculating statistics (CEP, SEP, STD, MRSE, DRMS)


26-AUG-2019 Update:  
* Routines for VLBL (Virtual long baseline) positioning
* TDOA solution in 3D


### Please, let us know that our work is useful for you: star this repository =)
