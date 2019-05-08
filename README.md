# travis_gcc_cpp17

[![Travis CI logo](TravisCI.png)](https://travis-ci.org)

Branch|Status
---|---
master|[![Build Status](https://travis-ci.org/richelbilderbeek/travis_gcc_cpp17.svg?branch=master)](https://travis-ci.org/richelbilderbeek/travis_gcc_cpp17)
develop|[![Build Status](https://travis-ci.org/richelbilderbeek/travis_gcc_cpp17.svg?branch=develop)](https://travis-ci.org/richelbilderbeek/travis_gcc_cpp17)

This GitHub is part of [the Travis C++ Tutorial](https://github.com/richelbilderbeek/travis_cpp_tutorial).

The goal of this project is to have a clean Travis CI build, with specs:

 * Build system: none
 * C++ compiler: `gcc`
 * C++ version: `C++17`
 * Libraries: `STL` only
 * Code coverage: none
 * Source: one single file, `main.cpp`

Less complex builds:

 * Use C++98: [travis_gcc_cpp98](https://www.github.com/richelbilderbeek/travis_gcc_cpp98)
 * Use C++11: [travis_gcc_cpp11](https://www.github.com/richelbilderbeek/travis_gcc_cpp11)
 * Use C++14: [travis_gcc_cpp14](https://www.github.com/richelbilderbeek/travis_gcc_cpp14)

Equally complex builds:

 * Use clang instead of GCC: [travis_clang_cpp17](https://www.github.com/richelbilderbeek/travis_clang_cpp17)

More complex builds:

 * Use of `qmake`: [travis_qmake_gcc_cpp17](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp17)
