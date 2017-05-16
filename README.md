# README #

Install:

// <JAVA_HOME> ex: "*C:\Program Files\Java\jdk...*"

**Create start.bat:**

```
#!java

"<JAVA_HOME>\bin\java" -server -jar Eternity.jar -r16 -c16 -p puzzles16x16.txt
```

**Usage, restart:**

If you want to continue (after stop running), add the last state file to parameters:

```
#!java

"<JAVA_HOME>\bin\java" -server -jar Eternity.jar -r16 -c16 -p puzzles16x16.txt -s state_20160330115709975.eii
```