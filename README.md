download apache maven from https://maven.apache.org/download.cgi
download the java extension https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack
download the visual studio code https://code.visualstudio.com/

extract the maven compressed file content into the root directory and add the bin directory to the environment path of windows

open a terminal and test the instalation with

`mvn -v`

the use command 

`mvn archetype:generate -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.1`

for more commands visit https://maven.apache.org/guides/index.html

define your groupId like __org.example.demo__
and the artifactId like __my-app__

for package the project use 

`mvn compile`

`mvn package`

for start 

`java -cp target/makech-tec-1.0-SNAPSHOT.jar org.example.demo.App`