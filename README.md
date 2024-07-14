# C++ Assignment Template

This is a template repository for C++ assignments.

## Getting Started

Clone the repository and start coding.

## Building and Running Tests

This repository uses Google Test for unit testing.

### Build and Run Tests

To build and run tests, use the following commands:

```sh
g++ -isystem /usr/include -pthread -o test_main tests/test_main.cpp /usr/lib/libgtest.a /usr/lib/libgtest_main.a
./test_main
