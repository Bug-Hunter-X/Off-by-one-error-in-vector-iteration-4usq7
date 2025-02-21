This repository demonstrates a common off-by-one error in C++ when iterating over a `std::vector`. The `bug.cpp` file contains the erroneous code, while `bugSolution.cpp` provides the corrected version.  The error arises from incorrectly using `<=` in the loop condition when accessing vector elements. Remember that vector indices start at 0 and end at `size() - 1`. 