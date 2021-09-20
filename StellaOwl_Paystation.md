# Robocode - Robocode: Learn to Code While Battling Tanks

## Project Abstract
_Robocode is an educational programming game. The goal is to create a ferocious robot battle tank to battle against other tanks. Players can build their tank using either Java or .NET. The robot battles are then run on the screen in real time. Interested in helping Robocode live up to their motto (“Build the best, destroy the rest!”)? Click the link below to learn more._ 


## Project Relevance
_This project will give students practice in object-oriented design, test driven development, creating UML diagrams, debugging, implementing design patterns, and working developing a GUI. GitHub is being used for version control, Gradle is used to build the project, Junit is being used for unit testing, and issue tracking is being done in SourceForge._

## Conceptual Design
_I propose that our team will contribute to the development of open feature requests related to game optimization. Examples include creating new weight classes for tanks, implementing new weapons. Another feature request is the implementation of a single-player offline campaign, although I’m not sure if it’s feasible to complete in the given time constraints. Additionally, the team can contribute at a smaller scale by finding, reporting, and fixing bugs._

## Background

<https://sourceforge.net/projects/robocode/>

***Building***
- Clone the repo
  - $ git clone https://github.com/robo-code/robocode.git robocode-proj
- in robocode-proj directory, run: 
  - $ ./gradlew build


**Running in Intellij**
- First, open the 'robocode-project' directory in IntelliJ.
- Secondly, set the JDK for the Robocode project, which needs to be JDK 8.
- From the menu, select: File > Project Structure | Platform Settings | SDKs > + (plus sign) > Add JDK
- Select the home directory of your JDK 1.8 installation.
- The last step is to align IDEA with the Gradle setup. You do this by running the 'Reload All Gradle Projects', which is available by pressing the "refresh button" with the Gradle tool window in its top-left corner.
- Click green ‘Run’ Button to run the Robocode application in Intellij

## Required Resources
- _Group members competencies_
- Intellij (v. 2021.2 is what I am using)
- JDK 8
- Git
