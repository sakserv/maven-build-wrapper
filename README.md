Maven Build Wrapper
-------------------

Simple shell script to pull down maven, setup env variables, and run a mvn clean install


Setup:
------

* Clone the project
```
cd /tmp && git clone https://github.com/sakserv/maven-build-wrapper.git
```

* Run the wrapper
```
cd /tmp/maven-build-wrapper && bash -x bin/build.sh </path/to/project/pom/dir>
```
