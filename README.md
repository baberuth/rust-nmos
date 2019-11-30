# rust-nmos
Rust implementation of NMOS

This project will use the Rust language to provide an
NMOS compatible stack. 

The stack will be heavily based on the https://github.com/sony/nmos-cpp Sony NMOS stack.


The stack will implemented fully in Rust and interface with 3rd party libraries
via bindings. The aim is to be single-threaded and non-blocking were possible. 

As the broadcast industry is moving towards controlling IP streams via NMOS we would like to provide a capable stack to fullfill the user requirements and to provide easy integration. 

Specifications of NMOS 

- https://github.com/AMWA-TV/nmos
