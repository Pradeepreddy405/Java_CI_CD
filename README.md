1. Installation of JDK to Execute the programs over shell
      -> sudo yum install java
2. To check the java version
      -> java -version
3. OpenJDK is the name of the open source distribution of Java, you have only actually installed the OpenJDK JRE. In order to install the full OpenJDK JDK, you should install the
   corresponding package with -devel appended onto its name.
      -> sudo yum install java-devel
4. Installation of JDK 17 version
      -> sudo yum install java-17-openjdk
5. If you wanna switch from one version java to other by using command
      -> sudo alternatives --config java
