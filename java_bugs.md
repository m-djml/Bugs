<h1>Java Bugs</h1>

<h2>1. "Cannot access 'java.lang.Object'" : </h2>
- when : happened after installing new IDE theme (?)
- env : Windows, IntelliJ, Java 17, Gradle JVM azul 17
- solution : Settings -> Build Tools > Gradle -> ☑️ "Enable parallel Gradle model [...]"

<h2>2. No matching tests found in any candidate test task. </h2>
    Requested tests:
        Test pattern com.eidd.robot.rest.controller.RobotApiControllerTest in task :test
- when : running tests
- env : ^^^
- solution : import "org.junit.jupiter.api.Test;" instead of "import org.junit.Test;" + declare "void testName()" instead of "public void testName()"
