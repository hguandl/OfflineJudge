# OfflineJudge
The offline judge system for automatic java assignment judgment

## Build Requirements
You need to use Maven to build this project.

The judge need Java 11 or higher to compile and execute.

## How to Use
Put the student assignment in /student folder. The filename should be the same as the problem name.

For example, if the problem is A1Q1, then put A1Q1.java in /student folder.

The judge will parse the problem set from the first command-line argument, like "java -jar OfflineJudge.jar data/example"
