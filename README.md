# MailLib
The mavericksoft's Email library

### To use it

Just include the follow in your pom.xml:

* Under the repositories tag:
 ```xml
        <repository>
            <id>mail-mvn-repo</id>
            <url>https://raw.github.com/vberihuete/MailLib/master/</url>
            <snapshots>
                <enabled>true</enabled>
                <updatePolicy>always</updatePolicy>
            </snapshots>
        </repository>
```        

* Under the dependencies tag:
 ```xml
        <dependency>
            <groupId>com.mavericksoft</groupId>
            <artifactId>mail</artifactId>
            <version>1.0-SNAPSHOT<</version>
        </dependency>
```       
### To get started

you can:

1. Use the `SimpleEmailMessage` class, wich gives you a basic implementation of the library.
2. Do your own implementation (or implementations) of the abstract `EmailMessage` class.
