javadoc-bootstrap
=================

Simple project that has a couple of Javadoc'd classes and Maven plugins configured to automatically generate Javadoc.

Currently, you can generate javadoc with this project by running the javadoc:javadoc goal as follows:

    mvn clean javadoc:javadoc

If you really wanted to, you could add a bit more to the pom and you'd wind up with your Javadoc at an earlier stage in
the Maven lifecycle.
