# SpringBootRestService project for running both unit test cases and integration test cases

mvn integration-test -Dspring-boot.run.profiles=dev
above command for running both integration test + usint test cases
mvn failsafe:integration-test   
above command is for running only integration test cases using failsafe plugin used in pom.xml

change the database setting in application.properties
