JBoss Java EE 6 with Hibernate Search
=====================================

This BOM builds on the Java EE full profile BOM, adding Hibernate Community projects including projects including Hibernate ORM, Hibernate Search and Hibernate Validator.

Usage
-----

To use the BOM, import into your dependency management:

    <dependencyManagement>
        <dependencies>
            <dependency>
              <groupId>org.wildfly.bom</groupId>
              <artifactId>jboss-javaee-6.0-with-hsearch</artifactId>
              <version>8.0.0-SNAPSHOT</version>
              <type>pom</type>
              <scope>import</scope>
            </dependency>
        </dependencies>
    </dependencyManagement> 

