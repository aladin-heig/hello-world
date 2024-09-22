# How to use

## Terminal

### Simple use

You can write the two following commands in order to generate a basic message with hello or goodbye
```sh
# Prints a simple greeting message 
java -jar target/java-intellij-idea-and-maven-1.0-SNAPSHOT.jar hello
```

```sh
# Prints a simple greeting message
java -jar target/java-intellij-idea-and-maven-1.0-SNAPSHOT.jar goodbye
```

### Use a custom name and greetings
If you want to go further, you can also write custom messages.
````sh
# Replace "name" and "greeting" by what you want
java -jar target/java-intellij-idea-and-maven-1.0-SNAPSHOT.jar "name" hello --greetings "greeting"
````