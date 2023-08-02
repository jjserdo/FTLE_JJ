## Table of Contents
  1. [Simulation Pitching Airfoil by Karthik Menon](#pitching-airfoil)
  2. [PIV Pitching Airfoil by Yuanhang Zhu](#piv-pitching-airfoil)
  3. [Simulation 2D Cylinder by Arturo](#2d-cylinder)

---
---
# Pitching Airfoil
## Individual Runs
`Date`, `Time`: When the run was finished  
`time`, `space`: FTLE run time and grid size  
`inter`: Number of interpolated spaces between datasets  

| Date    | Time | time        | space    | inter |
|---------|------|-------------|----------|-------|
| 7/26/23 | 1336 | 63800-69800 | 300,300  | 4     |
| 7/26/23 | 1357 | 75800-69800 | 300,300  | 4     |
| 7/26/23 | 1453 | 63800-69800 | 500,400  | 4     |
| 7/26/23 | 1545 | 75800-69800 | 500,400  | 4     |
| 7/26/23 | 1607 | 66800-69800 | 500,400  | 4     |
| 7/26/23 | 1633 | 72800-69800 | 500,400  | 4     |
| 7/27/23 | 0814 | 63800-69800 | 1000,800 | 4     |
| 7/26/23 | 1249 | 57800-63800 | 250,200  | 4     |
| 7/26/23 | 1249 | 69800-63800 | 250,200  | 4     |

## Batch Runs
`Date`, `Time`: When the run was finished  
`space`: FTLE run time and grid size  
`inter`: Number of interpolated spaces between datasets   
`target`, `range`, `dt`:  Center of analysis, range, and time difference between runs    
`~runtime`: Approximate run time for the entire batch   
`comp`: Computer used to run batch 

| Date      | Time |  space   | inter |  target | range | dt  |       ~runtime       | comp |
|-----------|------|----------|-------|---------|-------|-----|----------------------|------|
| 7/29/2023 | 1137 |  250,200 | 4     | 69800   | 3000  | 200 | 10.5 hrs, 20 min     | hp   |
| 8/  /2023 |      |  500,400 | 4     | 69800   | 3000  | 200 |         , 77 min     | hp   |
| 7/31/2023 | 2316 |  500,400 | 4     | 78800   | 3200  | 200 | 10   hrs,  9 min     | vr   |      
| 8/  /2023 |      | 1000,800 | 4     | 36800   | 6000  | 200 |         , 78/250 min | vr   |
| 8/  /2023 |      |          |       |         |       |     |                      |      |   
| 8/  /2023 |      |          |       |         |       |     |                      |      |   
| 8/  /2023 |      |          |       |         |       |     |                      |      |   

---
---
# PIV Pitching Airfoil

---
---
# 2D Cylinder

---
## Comments
- [ ] Need a better naming convention for files
- [x] Batch processing
- [x] Run on a faster computer
- [x] Finish sweep on the wavelength
