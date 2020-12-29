# Family Solution

Solution for the Family Problem in Geektrust.

### Run the Solution
Import the geektrust.jar into sts as existing project
Project > Run As > Maven clean
Configure the Arguments in the Run configurations tab ans also skip tests.
Run Geektrust.java > Java Application
Output will be present in the console.

```
mvn clean install -DskipTests
java -jar geektrust.jar <absolute_path_to_input_file>
```
javac in.geektrust.family/Geektrust.java
java -cp in.geektrust.family.Geektrust <absolute_path_to_input_file>
```
