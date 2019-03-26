=== UML State Diagram for Mini SQ10 SpyCam

The Mini SpyCam SQ10 is a nice piece of hardware but, having a reduced user interface (just a bi-color led and two buttons) accessing all of its features could be not-too-userfriendly.

Navigate through the user manual is not as well a comfortable task, so I decided to draw a state diagram representing all the states the camera can be in and the steps to switch from one to another.

In order to generate the bitmap image you have to install [PlantUML](https://github.com/plantuml/plantuml).

It comes pre-packaged in several GNU/Linux distribution. In Fedora, all you have to do is just `dnf install -y plantuml` 

To generate a bitmap from the source just use the command `plantuml sq10.dot`
