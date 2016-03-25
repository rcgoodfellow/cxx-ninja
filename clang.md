Clang Ninja Tricks
==================

Show macro definitions
----------------------

`clang++ -dM -E -x c++ -std=c++11 - < /dev/null`

`-dM`: dump macro definitions as output

`-E`: stop at preprocessing stage

`-x c++`: put the compiler in c++ mode

`-std=c++11`: use c++11 mode **- this is important it changes macro definitions**

