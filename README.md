# Gradle publish to maven local demo

`lib` - project for build some lib

1. `./gradlew :consume-lib:dep` - see ` demo.publish:lib:1.1 FAILED` line
1. `./gradlew pTML #aka publishToMavenLocal`
1. `./gradlew :consume-lib:dep` again and now `demo.publish:lib:1.1` - not in FAILED status. It fetched from mavenLocal