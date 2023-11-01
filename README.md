# gemcML

Repository to keep codes related to AI/ML algorithms to assist GEMC for CLAS12.


## Geant4 ML example

[A geant4 example](https://geant4-userdoc.web.cern.ch/Doxygen/examples_doc/html/ExamplePar04.html) is provided to demonstrate  how to use the Machine Learning (ML) 
inference to create energy deposits as a fast simulation model.

On the CUE, the example can be compiled and run with the following commands:

```bash
source /site/12gev_phys/ceInstall/jsetup.sh
module load sim
mkdir build ; cd build
cmake -DGeant4_DIR=$G4INSTALL/lib $G4INSTALL/source/examples/extended/parameterisations/Par04
make -j10
```
