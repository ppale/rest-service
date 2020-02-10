To run the server: `./gradlew bootRun`

To run the tests: `./gradlew test`

To build the jar: `./gradlew build`

To unpack the jar: `mkdir -p build/dependency && (cd build/dependency; jar -xf ../libs/*.jar)`

To build the docker container: `docker build -t ppale/spring-rest .`

To run the docker container: `docker run -p 8080:8080 ppale/spring-rest`