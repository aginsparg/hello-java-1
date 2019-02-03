test test test
This build will always fail because it has 2 examples of failing tests:
one based on the source code, and one based on an incorrect test.

# Learning Objectives

* Simple hello world example
* Experience with Git source code management
* Building with Gradle (using the Gradle wrapper)
* Automated unit testing with JUnit
* Continuous integration with Travis

# System requirements

* Java 6 SDK or later

# Running the Application

On Linux or Mac OS X:

    $ ./gradlew run
	
On Windows:
	
    > gradlew run

# Running the Tests

On Linux or Mac OS X:

    $ ./gradlew test
	
On Windows:
	
    > gradlew test
    
There will be a line that says > There were failing tests. See the report at: file:///... 
Copy & paste that line in a browser address bar, starting with file: to the end, to see the failures

Alternatively, in the Project view, right-click TestHelloWorld and select Run 'TestHelloWorld' or 
right-click app and select Run 'All Tests' 
This shows the specific JUnit assertion errors without the need for copy and paste
