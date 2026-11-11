# comsol-electrospinning-parametric-study
Automated COMSOL Multiphysics parametric study of an electrospinning setup using Python (MPh)
# Electrospinning Electric Field Simulation (COMSOL Multiphysics)

3D electrostatics model of an electrospinning setup, built in COMSOL
Multiphysics during a research internship at the Pakistan Institute of
Engineering and Applied Sciences (PIEAS). A Python (MPh) script can automate
parametric sweeps of the model.

## Model
- Domain: 300 mm box
- Applied voltage: 20 kV (CONFIRM)
- Physics: Electrostatics

## Results

### Geometry
![Geometry](images/geometry.png)

### Electric potential and electric field
Slice of electric potential (0 to 20 kV) with electric field arrows.

![Potential and field](images/potential_field_slice.png)

### Potential along the z axis
![Potential vs z](images/potential_vs_z.png)

### Potential along the x axis
![Potential vs x](images/potential_vs_x.png)

## Key findings
YOUR REAL FINDINGS HERE

## Requirements
COMSOL Multiphysics (licence), Python 3, `pip install mph numpy pandas matplotlib`
