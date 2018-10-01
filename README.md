JavaSIM has been available since 1997 and is an object-oriented simulation package based upon C++SIM. It provides discrete event process-based simulation similar to SIMULA's simulation class and libraries. A complete list of the facilities provided follows:

- The core of the system gives SIMULA-like simulation routines, random number generators, queueing algorithms, and thread package interfaces.
- Entity and set manipulation facilities similar to SIMSET.
- Classes allow "non-causal" events, such as interrupts, to be handled.
- Various routines for gathering statistics, such as histogram and variance classes.

The system also comes with complete examples and test routines which illustrate many of the issues raised in using the simulation package. It is used by many commercial and academic organisations.

Prior to 2007 both C++SIM and JavaSim were freely available in source and binary from Newcastle University, under the University's own licence. However, in late 2007 the University decided that everything could be released into open source under LGPL.

You can find details of the releases in the https://github.com/nmcl/JavaSim/releases section as well as binary downloads.

In 2015 the code was moved from Codehaus to github. All JIRAs from there were also migrated to github issues.

----

To build:

mvn compile

Run tests and create installation:

mvn install

To cleanup:

mvn clean
