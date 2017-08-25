# siminau-error

A library that defines traits and structs that are used for error handling by
all siminau projects. Currently, the overall error strategy used is to use
enums that are convertible into an error struct.

## Getting started

### Install Rust toolchain

To build, first install the Rust toolchain. While the toolchain may be
installable from a package management system depending on your platform, it
currently is best to install via [rustup][1]. Please visit [www.rustup.rs][1]
to download and run the installer.

[1]: https://www.rustup.rs

### Run safesec

Once Rust is installed, simply enter these commands to confirm that the test
suite succeeds:

```shell
$ git clone https://github.com/siminau/siminau-error.git
$ cd siminau-error
$ cargo test
```

This will run all unit, integration, and doc tests.

## Features

* Error traits and structs

## Licensing

This project is licensed under the MIT license.
