### Gradle JAR task up to date check strange behaviour

Build `./gradlew jar`
Check content of `build/libs` - jar is there
`./gradlew clean` - `build` folder is now gone
`./gradlew -i jar` - gradle tells that task is up to date, no jar in `build/libs`
