# Parallel Programming - EP2

This is the second programming exercise for the discipline Introductions to
Parallel and Distributed Programming (MAC5742/2017-1) and consists on a GPU 
parallel adaptation/implementation for cryptography codes.

## Cryptography parallel algorithms using CUDA programming language

The core idea behind this project is to acquire some knowledge about the
CUDA programming languange and how to use it to implement parallel code
for cryptography algorithms.

In order to check the performance gain, we will compare our parallel
implementation with few sequential samples provided to us by the instructors.

Our main intention with this work is to study if there is any significative
performance gain by using the parallel programming paradigm in common
cryptography codes.

Also, our secondary goal is to get a better understanding of parallel code
structure using CUDA, like *blocks* and *grids*.

## Getting Started

### Prerequisities

To the present, the only know prerequisites for running/compiling this project
are:

```
A CUDA-capable GPU
A supported version of Linux with a gcc compiler and toolchain
The NVIDIA CUDA Toolkit
```

The NVIDIA CUDA Toolkit and its installation instructions are available at [NVIDIA](http://developer.nvidia.com/cuda-downloads)


### Aditional Prerequisities

Also, in order to check eventual documentation, you also must have:

```
A PDF/PS reader installed
```

### (Pre)Installing

We recommend that you fork this repository by logging into your github account
and clicking on the fork icon on the top right side of the screen, because that
will make it easy to contribute with the project via pull requests.

After forking you can get your own copy of project by doing:

```
git clone https://github.com/YOUR-USERNAME/parallelProgEP1.git
```

Alternately, you can just get a copy of this repository by cloning it from
upstream by doing:

```
git clone https://github.com/deciolauro/parallelProgEP1.git
```

However, please note that if using this second method you will not be able to
contribute unless you get a contributor permission from someone inside the
project.


### Compiling

After cloning, you can compile  by doing:

```
cd NAME/src
./make
```

## Running the tests

You can also, after compiling, run the tests and see the log results by
executing:
```
cd NAME/test
./run_tests
```

Eventually, the logs will be stored in an specific folder inside the project
path, so you may also need permission to create a new folder if needed.

## Documentation

Eventually we will provide a simple doxygen auto created documentation for part
of the implementation at [Docs]().

## Contributing

Please read [CONTRIBUTING](CONTRIBUTING.md) for details on our code of conduct,
and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available,
see the [tags on this repository](https://github.com/deciolauro/parallelProgEP2/tags)

In summary, this means that our Versioning system follow the specific structure:

A version X.Y.Z-K represents:

* X -> MAJOR version change (reserved for incompatible API changes or Major improvements)
* Y -> MINOR version change (reserved for adding functionality and Minor changes)
* Z -> PATCH version change (reserved for bug fixes, typos...)
* K -> PRE-RELEASE version id (an small ASCII alphanumerics and hyphen
[0-9A-Za-z-] with the identifier for the pre-release)

The current build released is 0.0.1

## Authors

* **Candy Tenorio Gonzales (cvtenoriog@gmail.com)**
* **Décio Lauro Soares (deciolauro@gmail.com)**
* **Fatemeh Mosaiyebzadeh (mahshid.msy179@gmail.com)**

See also the list of [contributors](https://github.com/deciolauro/parallelProgEP1/graphs/contributors) who participated in this project.

Please consult our [CONTRIBUTING](CONTRIBUTING.md) for instructions. 

## License

Unless otherwise stated in the reader of each file, all this project is
licensed under GPL-3.0 - see the [LICENSE.md](LICENSE.md) file for details.

## Copyright

Copyright (C) <2017>  Candy Tenorio Gonzales; Décio Lauro Soares; Fatemeh Mosaiyebzadeh

## Final explanations

A significative part of the sequential code and great part of the insigths and
initial explanations was provided by our TA Pedro Bruel and can be found in his
repository [Pedro Bruel](https://github.com/phrb/MAC5742-0219-EP2) and are
provided by his own LINCENSE.

Make sure you checked either our [LICENSE.md](LICENSE.md) and his, specially for
the sequential code used in the comparative analysis that he provided.

Also, although we tried to take care of any License/Copyright nuances while
using the code he provides, in any case of conflict you should follow
[his](https://github.com/phrb/MAC5742-0219-EP2/LICENSE.md) specs.

## Acknowledgments

We would like to thank:

* Prof. Alfredo Goldman Vel Lejbman, Ph.D for all the support
* Pedro Bruel for the insights, initial orientation and code examples

## Trademarks

NVIDIA and the NVIDIA logo are trademarks or registered trademarks of NVIDIA Corporation in the U.S. and other countries. Other company and product names may be trademarks of the respective companies with which they are associated.
