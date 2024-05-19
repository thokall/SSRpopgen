# SSRpopgen
This r-package facilitates analysis of simple population genetic analysis of SSR data in R. The goal is to allow for easy import of genotypes from genotypefiles and then make use of some of the more commonly package for population genetic analysis in R to generate summary data. Other than basics summary it allows for population structure type of analysis.


# Tools used
Here is a set of tools that might be useful. Note that strataG is mainly used to run structure and summarize the results from this.
- adegenet
- strataG
- hierfstat
- pegas
- ape
- poppr

# Installation structure
Structure is a bit complicated to install/compile on modern hardware as it requires 32 bit support and most os today nowadays is 64-bit. it hence requieres a set of 32-bit related components to be added prior to installation. 

## Ubuntu
Install the correponding packages as stated for Fedora below using apt.

## Fedora
On Fedora the easiest is to use dnf:
```
dnf install glibc-devel.i686 libstc++.i686 ncurses-libs.i686
```

## Download Structure and clumpp
Download [Structure](https://web.stanford.edu/group/pritchardlab/software/structure.html) and [Clumpp](https://web.stanford.edu/group/rosenberglab/clumpp.html). If using the pre-build binary of structure just copy this to a folder that is part of you $PATH and make sure it is executable. Clumpp can be build according to instructions and then just move the binary as for structure. 




