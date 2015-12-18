# MySQL-Driver
Genric MySQL Data Source Driver for the JEDataCollector

## Dependencies
- [SQLDriverAbstract](https://github.com/AIT-JEVis/SQL-Driver-abstract)

## Installation
- Have a up and running JEVis3 instance
- Build dependency SQL-Driver-abstract
```
git clone https://github.com/AIT-JEVis/SQL-Driver-abstract
cd SQL-Driver-abstract
mvn install
cd ..
```

- Clone this repository and build the driver-jar file
```
git clone https://github.com/AIT-JEVis/MySQL-Driver.git
cd MySQL-Driver
mvn package
```

- Upload the driver to JEVis using JSON2JEVisStructureCreator (assuming [JSON2JEVisStructureCreator](https://github.com/AIT-JEVis/JSON2JEVisStructureCreator) is already built)
```
java -jar ../JSON2JEVisStructureCreator/target/JSON2JEVisStructureCreator-with-dependencies-jar MySQLDriverObjects.json
```

## Configuration
TODO
