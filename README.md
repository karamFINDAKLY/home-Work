# Home-Work


## What is Doctrine

* Doctrine 2 is an object-relational mapper (ORM) for PHP 7.1+ that provides transparent persistence for PHP objects. It uses the Data Mapper pattern at the heart, aiming for a complete separation of your domain/business logic from the persistence in a relational database management system.



## ORM

* object relational mapper (ORM) that sits on top of a powerful database abstraction layer (DBAL). One of its key features is the option to write database queries in a proprietary object oriented SQL dialect called Doctrine Query Language (DQL). This provides developers with a powerful alternative to SQL that maintains flexibility without requiring unnecessary code duplication.



## the interface

* an interface is a set of behaviors that a class must have, and that is why a class can have several interfaces. we can expect several behaviors from her



## the gol of interface

* ensure that we implement all the methods and therefore allow better reusability




## POLYMARPHISM

* is a mechanism which allows to modify the behavior of a child class with respect to its parent class. it allows interfaces to inherit from more generalized parents. The interest of POLYMARPHISM is to be able to handle several classes without worrying about the type of the object because all these classes are handled in the same way given that they inherit from the same interface. it also helps to avoid errors like calling the function with the wrong type.


## auto-configuration

*we use the file which allows a default configuration "servuces.yml" in app / config. this automatically configures all classes in the src folder as a service without having to configure it manually.