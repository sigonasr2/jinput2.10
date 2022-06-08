# jinput2
This project is a fork of the https://github.com/jinput/jinput project, which has not changed since 2018. This is a very progressive project that will push forward unnecessarily unstable modifications aggressively. That being said, the biggest goal is full support for hotswapping controllers, which the original jinput was lacking.

# Changes
The project contains the full Java content necessary to build the jar file. It also distribute the native files.

To build the project make sure you have Apache Ant.

Run
```
ant clean
ant compile jar run
```
`jinput.jar` ends up inside the `dist` folder.

The other changes are:

# License
Licensed under BSD License, copyright is attributed in each source file committed.
