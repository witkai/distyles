----------------------------------------------------------
Spring DI Styles webinar companion project
----------------------------------------------------------


Introduction
------------

This project uses Git for source control (http://git-scm.com), and is hosted
at GitHub (http://github.com/cbeams/distyles).

To clone (check out) the project:

    git clone git://github.com/cbeams/distyles.git

If you don't have git installed, and would like a zip or tar of the sources:

    http://github.com/cbeams/distyles/archives/master


This project is built using Gradle (http://gradle.org).

To execute build system tasks, simply run the 'gradle wrapper' script
appropriate to your platform.  You'll notice these scripts are available in the
root of this project, meaning there is nothing for you to download or install.

    For Windows:  `gradlew.bat`
    For OSX/*nix: `gradlew`

The remainder of this document will simply refer these scripts as 'gradlew'.


Discover available tasks:
-------------------------

    gradlew --tasks
        or
    gradlew -t


Build the project:
------------------

    gradlew build

Note that 'build' includes compilation, testing, and packaging. For Maven users,
`gradlew build` is roughly equivalent to `mvn package`.

Of course, the first time you execute this task, Gradle will download all
project dependencies.


Import the project into Eclipse/STS:
------------------------------------

    gradlew eclipse

    File->Import->Existing Projects Into Workspace


Import the project into IntellJ IDEA:
-------------------------------------

    gradlew idea

to create .iml, .ipr, and .iws files


Run the TransferScript main():
------------------------------

    gradlew runTransferScript

