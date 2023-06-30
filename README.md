# Propagation-simulation-result-2
The results of numerical FDTD simulations for the paper entitled "Properties of Whistler Waves’ Ducting in Plasmas
2 With Systems of Small-scale Density Depletions" by Zudin I.Yu. et al.

All files stored here are vectors or matrices coefficients presented in the text format and space symbol separated. "loadtxt" function from "numpy" library can be used for the data loading by a Python user. Each folder corresponds to a figure with the same number.

## Figure2 folder
All files are the solutions of the dispersion equations wrote in the paper. Each of file consist in two columns. First column is the density depletion width $d$ (in meters), and second column is wavenumber $p$.
* "even_0.dat", "even_1.dat" ... are the fist, the second etc. even modes of the plain depletion.
* "odd_0.dat", "odd_1.dat" ... are the fist, the second etc. odd modes of the plain depletion.
* "m=0_0.dat", "m=0_1.dat" ... are the fist, the second etc. brunches of the modes of the cylindrical depletion with azimuth number $m=0$.
* "m=+1_0.dat", "m=+1_1.dat" ... are the fist, second the etc. modes of the cylindrical depletion with azimuth number $m=1$.
* "m=-1_0.dat", "m=-1_1.dat" ... are the fist, second the etc.  modes of the cylindrical depletion with azimuth number $m=-1$.

## Figure3 folder
All files are the dependences of normalized localization scale $\delta/d$ from $d$. Each of file consist in two columns. The first one is the density depletion width $d$ (in meters), and the second column is $p$. The files is named in such a manner as in Figure2 folder.

## Figure5 folder
"Ex.dat", "Ey.dat" and so on are the amplitudes of electric and magnetic field components presented in Figure \#5 of the paper. "Ne.dat" is simulated density profile at z=60 km, as in above the file consists in two columns. The first is the $x$ coordinate and the second is the density. "xgrid.dat" and "zgrid.dat" are Cartesian coordinates of the grid's nodes used for field representation. So Ex(x\[i\],z\[j\])=Ex\[j,i\]

* units of plasma density is "m(-3)"
* units of electrical field components is "mkV/m"
* units of magnetic field components is "pT"
* units of Cartesian coordinates is "km"

The grid used for the data presentation is less detailed than that used for actual simulation.


## Figure6 folder
The same description as for Figure5 folder.

## Figure7 folder
"subdecameter.Sz.dat", "subdecameter.Sx.dat", "subhectometer.Sz.dat", and "subhectometer.Sz.dat" are the Pointing vector projections calculated in the cases of subdecameter and subhectometer depletions. "xgrid.dat", "zgrid.dat" are the coordinates of the grid's nodes. "subdecameter.Ne.dat" and "subhectometer.Ne.dat" is is simulated density profiles of systems of subdecameter and subhectometer depletions. The files ogranized in such mannar as in Figure5 folder.
The grid used for the data presentation is less detailed than that used for actual simulation.

* units of plasma density is "m(-3)"
* units of energy flux is "mkW/m(2)"
* units of Cartesian coordinates is "km"

## Figure8 folder
"subdecameter.Sz.dat", "subdecameter.Sz.dat" are the Pointing vector projections calculated in the cases of subdecameter and subhectometer depletions. "subhectometer.Ex.dat", and "subhectometer.Ex.dat" are the amplitudes of the electric field component. "xgrid.dat", "zgrid.dat" are the coordinates of the grid's nodes. "subdecameter.Ne.dat" and "subhectometer.Ne.dat" is is simulated density profiles of systems of subdecameter and subhectometer depletions. The files organized in such manner as in Figure5 folder.
The grid used for the data presentation is less detailed than that used for actual simulation.

* units of electrical field components is "mkV/m"
* units of plasma density is "m(-3)"
* units of energy flux is "mkW/m(-2)"
* units of Cartesian coordinates is "km"

## Figure9 folder

"subhectometer.Ex.dat", "subhectometer.Ex.dat" etc. are the profiles along $x$ of the components of the electric field and the plasma density. The files organized in such a manner. First column is coordinates values, the second one is the field component or density value.

* units of plasma density is "m(-3)"
* units of electrical field components is "mkV/m"
* units of Cartesian coordinates is "km"

## Figure10 folder

"subhectometer.Ex.dat", "subhectometer.Ex.dat" are the 2d-spectrums of the $E_x$ complex amplitude in the cases of subhectometer and subdecameter  depletions. "kx_grid.dat" and "kz_grid.dat" are the Cartesian coordinates of the grid's nodes used for spectrums representation.

* units of electrical field components is "mkV/m km(2)"
* units of Cartesian coordinates is "km(-1)"

## Figure11 folders
"subhectometer.Ex.dat", "subhectometer.Ex.dat", and "smoothed.Ex.dat" are the 1d spectrums presented on the Figure \#10 the cases of subhectometer, subdecameter and smoothed depletions.
* units of electrical field components is "mkV/m km"
* units of Cartesian coordinates is "km(-1)"

## Figure12 folders
"subhectometer.Ex.dat", "subhectometer.Ex.dat", and "smoothed.Ex.dat" are the 1d spectrums presented on the Figure \#11 the cases of subhectometer, subdecameter and smoothed depletions.
* units of electrical field components is "mkV/m km"
* units of Cartesian coordinates is "km(-1)"
