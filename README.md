# myapp211
a simple Grails web application created using Grails 2.1.1

## creating the grails 2.1.1 web application

    ashburndave@dphnuc:~/g2projects$ grails --version
    
    Grails version: 2.1.1
    ashburndave@dphnuc:~/g2projects$ javac -version
    javac 1.7.0_80
    ashburndave@dphnuc:~/g2projects$ java -version
    java version "1.7.0_80"
    Java(TM) SE Runtime Environment (build 1.7.0_80-b15)
    Java HotSpot(TM) 64-Bit Server VM (build 24.80-b11, mixed mode)
    ashburndave@dphnuc:~/g2projects$ 
    ashburndave@dphnuc:~/g2projects$ grails --non-interactive --plain-output --stacktrace -verbose create-app myapp211
    
    Base Directory: /home/ashburndave/g2projects
    |Loading Grails 2.1.1
    |Configuring classpath
    |Downloading: ivy-1.0.1.RELEASE.xml
    |Downloading: ivy-2.4.1.xml
    |Downloading: ivy-1.1.xml
    |Downloading: ivy-1.45.xml
    |Downloading: ivy-1.0.xml
    |Downloading: ivy-2.2.0.xml
    |Downloading: ivy-1.2.1.xml
    |Downloading: ivy-3.2.3.xml
    |Downloading: ivy-2.7.1.xml
    |Downloading: ivy-1.6.2.xml
    |Downloading: ivy-1.2_jdk5.xml
    |Downloading: ivy-4.10.xml
    |Downloading: ivy-1.8.2.xml
    |Downloading: org.springframework.uaa.client-1.0.1.RELEASE.jar
    |Downloading: protobuf-java-2.4.1.jar
    |Downloading: json-simple-1.1.jar
    |Downloading: bcpg-jdk15-1.45.jar
    |Downloading: bcprov-jdk15-1.45.jar
    |Downloading: jline-1.0.jar
    |Downloading: ivy-2.2.0.jar
    |Downloading: jansi-1.2.1.jar
    |Downloading: jna-3.2.3.jar
    |Downloading: serializer-2.7.1.jar
    |Downloading: grails-docs-2.1.1.jar
    |Downloading: grails-bootstrap-2.1.1.jar
    |Downloading: grails-scripts-2.1.1.jar
    |Downloading: grails-core-2.1.1.jar
    |Downloading: grails-resources-2.1.1.jar
    |Downloading: grails-web-2.1.1.jar
    |Downloading: slf4j-api-1.6.2.jar
    |Downloading: spring-test-3.1.2.RELEASE.jar
    |Downloading: concurrentlinkedhashmap-lru-1.2_jdk5.jar
    |Downloading: junit-4.10.jar
    |Downloading: ant-1.8.2.jar
    |Downloading: ant-launcher-1.8.2.jar
    |Downloading: ant-junit-1.8.2.jar
    |Downloading: tomcat-embed-core-7.0.30.jar
    |Downloading: tomcat-embed-jasper-7.0.30.jar
    |Downloading: tomcat-embed-logging-log4j-7.0.30.jar
    |Downloading: ivy-1.8.3.xml
    |Downloading: ivy-1.0.xml
    |Downloading: ivy-1.3.1.xml
    |Downloading: ivy-1.5.xml
    |Downloading: ivy-3.2.1.xml
    |Downloading: ivy-2.1.xml
    |Downloading: ivy-1.1.xml
    |Downloading: ivy-1.0.1.Final.xml
    |Downloading: ivy-1.6.10.xml
    |Downloading: ivy-2.2.xml
    |Downloading: ivy-3.1.xml
    |Downloading: ivy-1.2.2.xml
    |Downloading: ivy-2.0.8.xml
    |Downloading: ivy-1.4.xml
    |Downloading: ivy-1.5.6.xml
    |Downloading: ivy-1.3.164.xml
    |Downloading: ivy-1.1.2.xml
    |Downloading: ivy-1.1.4c.xml
    |Downloading: ivy-2.4.6.xml
    |Downloading: ivy-1.2.16.xml
    |Downloading: ivy-1.6.2.xml
    |Downloading: groovy-all-1.8.8.jar
    |Downloading: commons-beanutils-1.8.3.jar
    |Downloading: commons-el-1.0.jar
    |Downloading: commons-validator-1.3.1.jar
    |Downloading: commons-codec-1.5.jar
    |Downloading: commons-collections-3.2.1.jar
    |Downloading: commons-io-2.1.jar
    |Downloading: jta-1.1.jar
    |Downloading: hibernate-jpa-2.0-api-1.0.1.Final.jar
    |Downloading: grails-crud-2.1.1.jar
    |Downloading: grails-hibernate-2.1.1.jar
    |Downloading: grails-spring-2.1.1.jar
    |Downloading: grails-logging-2.1.1.jar
    |Downloading: grails-plugin-codecs-2.1.1.jar
    |Downloading: grails-plugin-controllers-2.1.1.jar
    |Downloading: grails-plugin-domain-class-2.1.1.jar
    |Downloading: grails-plugin-converters-2.1.1.jar
    |Downloading: grails-plugin-datasource-2.1.1.jar
    |Downloading: grails-plugin-filters-2.1.1.jar
    |Downloading: grails-plugin-gsp-2.1.1.jar
    |Downloading: grails-plugin-i18n-2.1.1.jar
    |Downloading: grails-plugin-log4j-2.1.1.jar
    |Downloading: grails-plugin-scaffolding-2.1.1.jar
    |Downloading: grails-plugin-services-2.1.1.jar
    |Downloading: grails-plugin-servlets-2.1.1.jar
    |Downloading: grails-plugin-mimetypes-2.1.1.jar
    |Downloading: grails-plugin-url-mappings-2.1.1.jar
    |Downloading: grails-plugin-validation-2.1.1.jar
    |Downloading: spring-core-3.1.2.RELEASE.jar
    |Downloading: spring-aop-3.1.2.RELEASE.jar
    |Downloading: spring-aspects-3.1.2.RELEASE.jar
    |Downloading: spring-asm-3.1.2.RELEASE.jar
    |Downloading: spring-beans-3.1.2.RELEASE.jar
    |Downloading: spring-context-3.1.2.RELEASE.jar
    |Downloading: spring-context-support-3.1.2.RELEASE.jar
    |Downloading: spring-expression-3.1.2.RELEASE.jar
    |Downloading: spring-jdbc-3.1.2.RELEASE.jar
    |Downloading: spring-jms-3.1.2.RELEASE.jar
    |Downloading: spring-orm-3.1.2.RELEASE.jar
    |Downloading: spring-tx-3.1.2.RELEASE.jar
    |Downloading: spring-web-3.1.2.RELEASE.jar
    |Downloading: spring-webmvc-3.1.2.RELEASE.jar
    |Downloading: grails-datastore-gorm-1.1.0.RELEASE.jar
    |Downloading: grails-datastore-core-1.1.0.RELEASE.jar
    |Downloading: grails-datastore-simple-1.1.0.RELEASE.jar
    |Downloading: aspectjweaver-1.6.10.jar
    |Downloading: aspectjrt-1.6.10.jar
    |Downloading: cglib-2.2.jar
    |Downloading: asm-3.1.jar
    |Downloading: commons-fileupload-1.2.2.jar
    |Downloading: oro-2.0.8.jar
    |Downloading: commons-dbcp-1.4.jar
    |Downloading: commons-pool-1.5.6.jar
    |Downloading: h2-1.3.164.jar
    |Downloading: jstl-1.1.2.jar
    |Downloading: xpp3_min-1.1.4c.jar
    |Downloading: ehcache-core-2.4.6.jar
    |Downloading: log4j-1.2.16.jar
    |Downloading: jcl-over-slf4j-1.6.2.jar
    |Downloading: jul-to-slf4j-1.6.2.jar
    |Downloading: grails-plugin-testing-2.1.1.jar
    |Downloading: grails-test-2.1.1.jar
    .
    |Environment set to development
    ......    [mkdir] Created dir: /home/ashburndave/g2projects/myapp211/src
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp211/src/java
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp211/src/groovy
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp211/grails-app
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp211/grails-app/controllers
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp211/grails-app/services
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp211/grails-app/domain
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp211/grails-app/taglib
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp211/grails-app/utils
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp211/grails-app/views
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp211/grails-app/views/layouts
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp211/grails-app/i18n
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp211/grails-app/conf
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp211/test
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp211/test/unit
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp211/test/integration
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp211/scripts
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp211/web-app
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp211/web-app/js
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp211/web-app/css
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp211/web-app/images
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp211/web-app/META-INF
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp211/lib
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp211/grails-app/conf/spring
    .    [mkdir] Created dir: /home/ashburndave/g2projects/myapp211/grails-app/conf/hibernate
    ..     [copy] Copying 1 resource to /home/ashburndave/g2projects/myapp211
    .    [unjar] Expanding: /home/ashburndave/g2projects/myapp211/grails-shared-files.jar into /home/ashburndave/g2projects/myapp211
    .   [delete] Deleting: /home/ashburndave/g2projects/myapp211/grails-shared-files.jar
    .     [copy] Copying 1 resource to /home/ashburndave/g2projects/myapp211
    .    [unjar] Expanding: /home/ashburndave/g2projects/myapp211/grails-app-files.jar into /home/ashburndave/g2projects/myapp211
    .   [delete] Deleting: /home/ashburndave/g2projects/myapp211/grails-app-files.jar
    .     [copy] Copying 1 resource to /home/ashburndave/.grails/2.1.1/projects/.core/integration-files
    .    [unjar] Expanding: /home/ashburndave/.grails/2.1.1/projects/.core/integration-files/grails-integration-files.jar into /home/ashburndave/.grails/2.1.1/projects/.core/integration-files
    .   [delete] Deleting: /home/ashburndave/.grails/2.1.1/projects/.core/integration-files/grails-integration-files.jar
    .     [copy] Copying 3 files to /home/ashburndave/g2projects/myapp211
    ..
    |Created Eclipse project files.
    .
    |Created Grails Application at /home/ashburndave/g2projects/myapp211
    ashburndave@dphnuc:~/g2projects$ 
    ashburndave@dphnuc:~/g2projects$ tree myapp211
    myapp211
    ├── application.properties
    ├── grails-app
    │   ├── conf
    │   │   ├── ApplicationResources.groovy
    │   │   ├── BootStrap.groovy
    │   │   ├── BuildConfig.groovy
    │   │   ├── Config.groovy
    │   │   ├── DataSource.groovy
    │   │   ├── hibernate
    │   │   ├── spring
    │   │   │   └── resources.groovy
    │   │   └── UrlMappings.groovy
    │   ├── controllers
    │   ├── domain
    │   ├── i18n
    │   │   ├── messages_cs_CZ.properties
    │   │   ├── messages_da.properties
    │   │   ├── messages_de.properties
    │   │   ├── messages_es.properties
    │   │   ├── messages_fr.properties
    │   │   ├── messages_it.properties
    │   │   ├── messages_ja.properties
    │   │   ├── messages_nl.properties
    │   │   ├── messages_pl.properties
    │   │   ├── messages.properties
    │   │   ├── messages_pt_BR.properties
    │   │   ├── messages_pt_PT.properties
    │   │   ├── messages_ru.properties
    │   │   ├── messages_sv.properties
    │   │   ├── messages_th.properties
    │   │   └── messages_zh_CN.properties
    │   ├── services
    │   ├── taglib
    │   ├── utils
    │   └── views
    │       ├── error.gsp
    │       ├── index.gsp
    │       └── layouts
    │           └── main.gsp
    ├── lib
    ├── scripts
    ├── src
    │   ├── groovy
    │   └── java
    ├── test
    │   ├── integration
    │   └── unit
    └── web-app
        ├── css
        │   ├── errors.css
        │   ├── main.css
        │   └── mobile.css
        ├── images
        │   ├── apple-touch-icon.png
        │   ├── apple-touch-icon-retina.png
        │   ├── favicon.ico
        │   ├── grails_logo.jpg
        │   ├── grails_logo.png
        │   ├── leftnav_btm.png
        │   ├── leftnav_midstretch.png
        │   ├── leftnav_top.png
        │   ├── skin
        │   │   ├── database_add.png
        │   │   ├── database_delete.png
        │   │   ├── database_edit.png
        │   │   ├── database_save.png
        │   │   ├── database_table.png
        │   │   ├── exclamation.png
        │   │   ├── house.png
        │   │   ├── information.png
        │   │   ├── shadow.jpg
        │   │   ├── sorted_asc.gif
        │   │   └── sorted_desc.gif
        │   ├── spinner.gif
        │   └── springsource.png
        ├── js
        │   └── application.js
        ├── META-INF
        └── WEB-INF
            ├── applicationContext.xml
            ├── sitemesh.xml
            └── tld
                ├── grails.tld
                └── spring.tld
    
    28 directories, 56 files
    ashburndave@dphnuc:~/g2projects$ 

## Grails 2.1.1 web application dependencies

I ran the command below to examine the dependencies of a Grails 2.1.1 web application.  I copied the three .txt files
created below to the top level directory of the actual project (~/g2projects/myapp211) and commited them to github,
where then can be found at the following URL.

https://github.com/ashburndev/myapp11




