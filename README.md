# Textured_Anti-Reflective-coating

## What is this project about?
This is solar cell research to understand patterned ARC impact on its efficiency. This study aims to understand the textured surface of ARC by using the python-meep simulation tool. Users could specify the desired parameters(pattern sharp, width, depth, symmetry).

## Repository structure
- Six models of surface
   - without ARC
   - flat ARC
   - step ARC
   - wege ARC
   - sphere ARC
   - ellopsoid ARC
## Run
- Download and Install Anaconda: https://www.anaconda.com/products/distribution
- Install pymeep: ```conda create -n mp -c conda-forge pymeep pymeep-extras```, or with mpi: ```conda create -n pmp -c conda-forge pymeep=*=mpi_mpich_*```
- Run ```Jupiter notebook``` and run the selected script(input the desired parameters)

## Reference
https://meep.readthedocs.io/en/latest/
