# Compile Java

1. Compile java files to target folder.
`javac -d target src/main/java/com/morgan/lox/**`
2. Create a jar file from the generated class files.
`jar cfm jlox.jar MANIFEST.MF target/com/morgan/lox/**`