# Build Instructions
## IOR

1. Go to ior directory, `cd ior`.
2. Run `./bootstrap`
3. Run `./configure --with-hdf5 `, if the system does not have an HDF5 module, user need to compile parallel HDF5 library and specify the path: `CFLAGS=-I/path/to/hdf5-1.10.6/build/hdf5/include LDFLAGS=-L/path/to/hdf5-1.10.6/build/hdf5/lib -Wl,-rpath,/path/to/hdf5-1.10.6/build/hdf5/lib`
4. Run `make`

## VPIC-IO
1. Go to VPIC-IO directory `cd vpicio`
2. Edit Make file to specify the HDF5 installation path
3. Run `make`



