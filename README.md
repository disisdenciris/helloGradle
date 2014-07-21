#Hello Gradle
---------------------------------------

1. create a new repository @Github named $PROJECT_NAME.git
2. create a gradle project with idea named $PROJECT_NAME.git
    1. select "create directories for empty content roots automatically"
    2. select "use local distribution"
3. initialize git
    1. <code>git init</code>
    2. <code>git remote add origin PATH/TO/REPO</code>
    3. <code>git fetch</code>
    4. <code>git checkout -t origin/master</code>
4. create java and test code
5. run program and tests from ide
6. run tests from console
7. run application from console
    1. add application plugin to build file <code>apply plugin: 'application'</code>
    2. declare main class = <code>mainClassName = '$PACKAGE_NAME.$CLASS_NAME'</code>
    3. run program <code>gradle run</code>