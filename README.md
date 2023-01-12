# SPRINGBOOT DEMO APP
Compile project in Maven
1. Check Maven version.
    ```bash
    mvn -v
    ```
2. Compile Maven project, creates necessary classes inside `target` folder.
    ```bash
    mvn compile
    ```
3. Maven package will compile the java code, run any tests & packaging the code up in a JAR file.
    ```bash
    mvn package
    ```
4. Run the application issuing this command.
    ```bash
    java -jar target/APP_NAME.jar
    ```
5. Install as local package for external projects referencing
    ```bash
    nvm install
    ```
