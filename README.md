A docker build of the latest Centos release with update applied, and java installed.

Here's how I build it:

    docker build -t centos-java .

And here's how I run it:

    $ docker run -i -t centos-java
    bash-4.1# java -version
    java version "1.7.0_45"
    OpenJDK Runtime Environment (rhel-2.4.3.4.el6_5-x86_64 u45-b15)
    OpenJDK 64-Bit Server VM (build 24.45-b08, mixed mode)

