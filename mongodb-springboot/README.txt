Install MongoDB server community edition (do not check mongodb compass checkbox).
Install MongoDB compass from internet.
Create directory C:\data\db (this directory is needed for mongodb to start).
Start MongoDB (default port 27017) - C:\Program Files\MongoDB\Server\3.6\bin>mongod
Spring Boot, by default, tries to connect to a MongoDB server at mongodb://localhost/test
Change mongo db url as follows in application.properties (if needed):
spring.data.mongodb.uri=mongodb://user:secret@mongo1.example.com:12345,mongo2.example.com:23456/test