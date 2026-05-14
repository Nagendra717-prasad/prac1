# prac1


















































8th

mvn --version

cd Desktop

mvn archetype:generate ^
-DgroupId=com.demo ^
-DartifactId=MyMavenApp ^
-DarchetypeArtifactId=maven-archetype-quickstart ^
-DinteractiveMode=false

cd MyMavenApp

mvn compile

mvn exec:java -Dexec.mainClass="com.demo.App"


9th

gradle --version

cd Desktop

mkdir zod 

cd zod

gradle init

gradle build 

gradle run 

C:\Users\nagen\Desktop\god>gradle init

Select type of build to generate:
  1: Application
  2: Library
  3: Gradle plugin
  4: Basic (build structure only)
Enter selection (default: Application) [1..4] 1

Select implementation language:
  1: Java
  2: Kotlin
  3: Groovy
  4: Scala
  5: C++
  6: Swift
Enter selection (default: Java) [1..6] 1

Enter target Java version (min: 7, default: 21): 21

Project name (default: god): god

Select application structure:
  1: Single application project
  2: Application and library project
Enter selection (default: Single application project) [1..2] 2

Select build script DSL:
  1: Kotlin
  2: Groovy
Enter selection (default: Kotlin) [1..2] 2

Generate build using new APIs and behavior (some features may change in the next minor release)? (default: no) [yes, no] yes

