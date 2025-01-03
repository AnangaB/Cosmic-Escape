# Cosmic Escape
“Cosmic Escape” is a game involving an astronaut named Jerry, on his space journey back home to the International Space Station (ISS). In Jerry’s way are different obstacles impeding him from going back. Firstly, deadly giant aliens of the Waru clan are resting throughout space, who are so powerful that they damage any spaceship that bumps into them. Secondly, there are also flying meteors that Jerry must avoid, otherwise his ship will completely tear apart into dust. Lastly, there is a final hurdle for Jerry, that is the lazy Waru Clan Aliens, have put 4 barriers of different color around the ISS, 
that can only be unlocked by keys of matching color, which are scattered throughout space. If that wasn’t enough, Jerry's journey only gets harder with 
stationary rocks around the map that Jerry must navigate around, although not damaging, make the travel lengthier. 
In spite of the perils, scattered around the map are the different keys that Jerry can use to get past the barriers blocking the ISS. 
Furthermore, the keys upon retrieval also boost the Spaceship's score, ensuring further protection against the giant aliens. 
There are also different balls of energy appearing sporadically around the map that boost the Spaceship's score further.

(I did this project as part of CMPT 276: Introduction to Software Engineering at SFU, alongside 3 others.)

## Prerequisites

- Java (version 21)
- Maven (version 4.0.0)


## Getting Started

Clone the repository and navigate to the project folder, by typing the following in your terminal:

git clone https://github.com/AnangaB/Cosmic-Escape.git

cd Cosmic-Escape

Build and run the project with Maven, in your favorite IDE. We used IntelliJ IDEA for development and testing in this project.
To create a Maven project in IntelliJ IDEA, locate File → New → Project → Maven Archetype (Inside "Generators") → Name the project, set the location, and initialize JDK to openjdk-21 → Create

We have outlined the project structure below, which includes resources sections, main source code section and the unit test sections.
## Maven Project Structure

The project follows the standard Maven project structure:

- src/main/java: Contains the main source code of the game.
- src/main/resources: Contains additional resources, such as images.
- src/test/java: Contains the unit tests for the game.

## Dependencies

The project uses the following dependencies:

- JUnit Jupiter (version RELEASE) and JUnit (version 4.13.2) for testing

## Build Automation

To build the project and create the jar file, go to the project directory and run: mvn clean package

To execute the game using the generated jar file run: java -jar target/Cosmic-Escape

To generate javadocs for the project run: mvn javadoc:javadoc
