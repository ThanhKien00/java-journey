# Setting up Environment

Setting up an efficient Java development environment is the beginning of your Java journey. This article will help you
step-by-step how to set up a Java development environment.

## Get your JDK

Firstly, your computer needs to install the JDK, which includes the Java Runtime Environment (JRE) as well as
development tools, such as Java Compiler and Debugger.

1. Visit the [Official Oracle Website](https://www.oracle.com/java/technologies/downloads/).
2. Download the latest version of JDK Installer that matches your operating system.
3. Run the installer and follow the on-screen instructions.
4. After install completely, set the `JAVA_HOME` environment variable to the `bin` folder of JDK installation directory.

## Path to Java World with `JAVA_HOME`

The `PATH` environment variable specifies the directories containing executable programs on your system. In
Windows, these programs are files that end in `.exe` extension. By including a program's directory in `PATH`, it becomes
available to use on the command line by name, without having to specify its full path. So for easy access to a program,
the 'PATH' should contain the directory of that program.

The `JAVA_HOME` environment variable can be considered as a pointer to the JDK. When a program or tool depends on the
JDK for its operation, it leverages the value of `JAVA_HOME` to locate the JDK's installation directory.

## IDE is your Sidekick, Choose it right!

An Integrated Development Environment (IDE) is a software application that provides comprehensive facilities for
software development. An IDE basically consists of at least a source-code editor, build automation, and a debugger.

There are many popular IDEs for developing Java application:

## References

-[JAVA_HOME vs. PATH Environment Variables](https://tomgregory.com/gradle/java-home-vs-path-environment-variables/#:~:text=The%20JAVA_HOME%20environment%20variable%20is,that%20pointer%20to%20find%20it.)