# MSBuild / Dotnet Core Example

## How to setup and consume inherited build targets

### Overview

This project is an example of how to consume the inherited build file targets produced by the [main example project](https://github.com/JollyWizard/InheritableBuildTarget.csproj) in this series.

### Usage

* Pull, build, and publish (locally) the [main example project](https://github.com/JollyWizard/InheritableBuildTarget.csproj) using `dotnet` or Visual Studio.

* Pull this project and build it using `dotnet` or Visual Studio.

### Details

This project demonstrates the process of importing inherited build artifacts using three 3 default targets:

* `HelloProps` Located in the dependency.
* `HelloTargets` Also located in the dependency.
* `Hello-Child` A local target in this projects build file, but uses a property declared in the dependency.

### Technical Overview

Please see the main example project for technical background on these topics.
