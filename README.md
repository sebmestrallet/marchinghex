# marchinghex
Generating an hexmesh using a marching cube approach.
![Input](https://raw.githubusercontent.com/fprotais/marchinghex/main/images/origin.png)
![hexified](https://raw.githubusercontent.com/fprotais/marchinghex/main/images/hexified.png)
![clipped](https://raw.githubusercontent.com/fprotais/marchinghex/main/images/clipped.png)
Currently the input is a tet mesh in either .mesh (MEDIT format) or .geogram. It can be generated/displayed with softwares such as GMSH or GRAPHITE.
# Use CMake to build the project:

```sh
git clone --recurse-submodules https://github.com/fprotais/marchinghex
cd marchinghex
mkdir build
cd build
cmake ..
make
./marchinghex ../fertility.mesh
./marchinghex ../kitten.geogram
```

Build on windows works only with static libs. 
