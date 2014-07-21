Hello Gradle
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
6. run tests from console <code>gradle test</code>
7. run application from console
    1. add application plugin to build file <code>apply plugin: 'application'</code>
    2. declare main class = <code>mainClassName = '$PACKAGE_NAME.$CLASS_NAME'</code>
    3. run program <code>gradle run</code>
8. review changes with <code>git status</code>
9. add a .gitignore file to prevent tracking of binaries and generated resources
10. review changes with <code>git status</code> and verify only appropriate changes are tracked
11. push to local repository <code>git commit -m "$COMMENT"</code>
12. push to github <code>git push origin master </code>