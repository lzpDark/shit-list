# Ubuntu

install OpenJDK

```shell
sudo apt-get install openjdk-8-jre
// or: sudo apt-get install openjdk-8-jdk
```

install OpenJDK

```shell
sudo apt-get install openjdk-11-jre
// or: sudo apt-get install openjdk-11-jdk
```

other version

```
sudo apt-get install openjdk-{version}-jre
// or: sudo apt-get install openjdk-{version}-jdk
```

install OpenJDK: https://openjdk.org/install/

set default JDK version: https://man7.org/linux/man-pages/man1/update-alternatives.1.html

```shell
sudo update-alternatives --config java
```

```
There are 3 choices for the alternative java (providing /usr/bin/java).

  Selection    Path                                            Priority   Status
------------------------------------------------------------
  0            /usr/lib/jvm/java-17-openjdk-amd64/bin/java      1711      auto mode
  1            /usr/lib/jvm/java-11-openjdk-amd64/bin/java      1111      manual mode
* 2            /usr/lib/jvm/java-17-openjdk-amd64/bin/java      1711      manual mode
  3            /usr/lib/jvm/java-8-openjdk-amd64/jre/bin/java   1081      manual mode

Press <enter> to keep the current choice[*], or type selection number: 

```

just choose the number, such like "2" for java-17 above.