# Type traits missing from C++17

This library adds type traits and macros for metaprogramming in C++17.

 - `DZE_REQUIRES` is a wrapper around `std::enable_if_t` mainly designed to mark down usages of SFINAE across a code base for easier migration to C++20's concepts when it is available.
 - dze::enable_special_members, dze::enable_copy_move are empty traits classes that can be used as a base class to conditionally enable special members of the derived class.
