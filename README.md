Installation guide:

1. Download the .zip file to your local
2. Unzip the file
3. Open command prompt and changed the directory to your Unzipped file location
4. Run the command: mvn install -DskipTests
5. In your Mule application pom.xml, include the dependency:
   <dependency>
    <groupId>a87dfd3c-a093-4ada-b811-29fd439c18bc</groupId>
    <artifactId>file-utility-module</artifactId>
    <version>1.0.0</version>
    <classifier>mule-plugin</classifier>
</dependency>
