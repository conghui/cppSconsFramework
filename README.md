## Introduction ##


## Setup ##
- execute the command

  ```
  git submodule update --init --recursive
  git submodule update --recursive
  ```
- choose the right *SConstruct* file in scripts/ folder based on your
requirement.
- if you choose a *SConstruct* file that links with Boost library, make
sure that the boost library are dynamic one.
- modify `boost_root` in *SConstruct* to where your boot are installed
