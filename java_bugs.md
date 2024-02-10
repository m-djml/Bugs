<h1>Java Bugs</h1>

1. "Cannot access 'java.lang.Object'" :
- when : happened after installing new IDE theme (?)
- env : Windows, IntelliJ, Java 17, Gradle JVM azul 17
- solution : Settings -> Build Tools > Gradle -> ☑️ "Enable parallel Gradle model [...]"

