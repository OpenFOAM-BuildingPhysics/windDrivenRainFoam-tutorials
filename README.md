# windDrivenRainFoam

An open-source solver for wind-driven rain based on OpenFOAM

Source code for the solver code can be downloaded from [here](https://gitlab.ethz.ch/openfoam-cbp/solvers/winddrivenrainfoam)

The solver is tested for the following OpenFOAM versions:

* OpenFOAM-org (OpenFOAM Foundation) v6, v7, v8, v9, v10, v11
* OpenFOAM-com (OpenCFD-ESI) v1806, v2006, v2106

### Tutorial case

Tutorial case solves for the WDR exposure of an isolated cubic building.

<img src="https://gitlab.ethz.ch/openfoam-cbp/solvers/winddrivenrainfoam/-/wikis/img/tutorial_cube.png"  width="60%">
<br><i>  Catch ratio [-] distribution on the building surfaces and the 
surroundings at a rainfall intensity of 1 mm/h and a reference wind speed of 5 m/s. </i>

### Usage

You can use the tutorial for a specific OpenFOAM version by checking out the commit with corresponding tag. For example, for OpenFOAM v9:

    git clone https://gitlab.ethz.ch/openfoam-cbp/tutorials/winddrivenrainfoam.git winddrivenrainfoam-tutorial
    cd winddrivenrainfoam-tutorial
    git checkout tags/of-org_v9.0

See the list of tags for different versions [here](https://gitlab.ethz.ch/openfoam-cbp/tutorials/winddrivenrainfoam/-/tags)

