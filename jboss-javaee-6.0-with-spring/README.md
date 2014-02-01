JBoss Java EE 6 with Spring
===============================

This BOM builds on the Java EE full profile BOM, adding Spring.
  
Usage
-----

To use the BOM, import into your dependency management:

    <dependencyManagement>
        <dependencies>
            <dependency>
               <groupId>org.wildfly.bom</groupId>
               <artifactId>jboss-javaee-6.0-with-spring</artifactId>
               <version>8.0.0-SNAPSHOT</version>
               <type>pom</type>
               <scope>import</scope>
            </dependency>
        </dependencies>
    </dependencyManagement>
