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

- Javadocs are linked on the side of this repository (Or click [here](https://sigonasr2.github.io/jinput2.10/))
- Final built jar is found in [Releases](https://github.com/sigonasr2/jinput2.10/releases)
   - I will post new releases whenever they become useable and stable with new functionality. My main branches are effectively my development branch. I commit directly to main, so be wary. Use the Releases page for guaranteed stability.
   - I have a jar with sources inside of the `dist` folder that lets you comfortably program with IDE helpers named accordingly.

The other changes are:

# License
Licensed under BSD License, copyright is attributed in each source file committed.
