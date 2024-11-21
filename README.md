```
mvn clean
mvn package
# https://github.com/CycloneDX/cyclonedx-maven-plugin/issues/579
cyclonedx-win-x64.exe validate --input-file target\bom.json --input-version v1_5 --fail-on-errors > validation_result.txt
```
