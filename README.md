javadoc-bootstrap
=================

Simple project that has a couple of Javadoc'd classes and Maven plugins configured to automatically generate Javadoc.

Currently, you can generate javadoc with this project by running the javadoc:javadoc goal as follows:

    mvn clean javadoc:javadoc

If you really wanted to, you could add a bit more to the pom and you'd wind up with your Javadoc at an earlier stage in
the Maven lifecycle.  Take the code in the following profile as an example:

    mvn clean compile -Pcompile-javadoc

Not only does this profile compile the source, but it attaches the javadoc goal in the javadoc plugin to the compile
phase in the Maven lifecycle.
