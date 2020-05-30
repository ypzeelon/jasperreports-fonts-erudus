# jasperreports-fonts-erudus

[JasperReports](https://community.jaspersoft.com/project/jasperreports-library) Font Package Containing the [Erudus Icon font](https://github.com/Erudus/erudus-icons)

Until it has not been uploaded to Maven central, you can build it locally and install it to your local maven repository like this:

    mvn install:install-file -Dfile=c:/dev/jasperreports-fonts-erudus/target/jasperreports-fonts-erudus-2020.05.30.1.jar -DgroupId=com.ypzeelon.jasperreports.font -DartifactId=jasperreports-fonts-erudus -Dversion=2020.05.30.1 -Dpackaging=jar -DgeneratePom=true

You can then add it to your pom.xml and use the font in your Jasper reports:

    <dependency>
        <groupId>com.ypzeelon.jasperreports.font</groupId>
        <artifactId>jasperreports-fonts-erudus</artifactId>
        <version>2020.05.30.1</version>
    </dependency>
