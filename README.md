# HelloJava

## Commande Maven

```
mvn clean
mvn compile
mvn test
mvn clean compile
mvn clean test
mvn package
mvn clean package
```

## Lancement projet Java

```
cd .../target
Identifier le jar
java -jar nom-version.jar
	exemple : java -jar ebanking-0.0.1-SNAPSHOT.jar
```

## Dependence BDD Sql Light
```
	<dependency>
		<groupId>com.h2database</groupId>
		<artifactId>h2</artifactId>
	</dependency>
```
