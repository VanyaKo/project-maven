# Project Maven

## How to use

- Navigate to the project directory
- Build the project:
  - run `mvn install:install-file -Dfile=./lib/desktop-game-engine.jar -DgroupId="com.javarush" -DartifactId=desktop-game-engine -Dversion="1.0" -Dpackaging=jar` to install `desktop-game-engine` dependency from `lib` to a local repository
  - run `mvn clean install` to install the artifact to a local repository
- Run the game:
  - run `mvn javafx:run`
