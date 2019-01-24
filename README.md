# maven-repo
Maven repository for private projects

## Install jar in directory

(note: replace `YOUR_GROUP`, `YOUR_ARTIFACT`, `YOUR_VERSION` and `YOUR_JAR_FILE`)

```bash
mvn install:install-file -DgroupId=YOUR_GROUP -DartifactId=YOUR_ARTIFACT -Dversion=YOUR_VERSION -Dfile=YOUR_JAR_FILE -Dpackaging=jar -DgeneratePom=true -DlocalRepositoryPath=.  -DcreateChecksum=true
```
