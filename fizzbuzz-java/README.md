# FizzBuzz Java Project

This project implements the classic FizzBuzz problem in Java using Maven. The FizzBuzz program outputs numbers from 1 to a specified number. For multiples of three, it outputs "Fizz" instead of the number, and for the multiples of five, it outputs "Buzz". For numbers that are multiples of both three and five, it outputs "FizzBuzz".

## Project Structure

```
fizzbuzz-java
├── src
│   ├── main
│   │   └── java
│   │       └── com
│   │           └── example
│   │               └── FizzBuzz.java
│   └── test
│       └── java
│           └── com
│               └── example
│                   └── FizzBuzzTest.java
├── pom.xml
└── README.md
```

## Usage

1. Clone the repository.
2. Navigate to the project directory.
3. Build the project using Maven:
   ```
   mvn clean install
   ```
4. Run the FizzBuzz program:
   ```
   mvn exec:java -Dexec.mainClass="com.example.FizzBuzz"
   ```

## Testing

Unit tests for the FizzBuzz class are located in `src/test/java/com/example/FizzBuzzTest.java`. You can run the tests using:
```
mvn test
```

## Dependencies

This project uses JUnit for testing. The dependencies are defined in the `pom.xml` file.