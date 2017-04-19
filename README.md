# Spring 4 + Hibernate 4 + MySQL+ Maven Integration example (Annotations+XML)


http://websystique.com/spring/spring4-hibernate4-mysql-maven-integration-example-using-annotations/



=========
CREATE TABLE EMPLOYEE(
    id INT NOT NULL auto_increment, 
    name VARCHAR(50) NOT NULL,
    joining_date DATE NOT NULL,
    salary DOUBLE NOT NULL,
    ssn VARCHAR(30) NOT NULL UNIQUE,
    PRIMARY KEY (id)
);

=========