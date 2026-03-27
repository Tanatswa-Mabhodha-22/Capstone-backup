# 3RD Year Car Rental System
## ADP362S - Applications Development Practice 3
### Assignment 1

---

## Project Description
This project is a Car Rental System built using Java and Maven.
The system is developed using Domain Driven Design (DDD) principles
including Entities, Factories, and Repositories.
Test Driven Development (TDD) is applied throughout the project.

---

## Group Members

| Name | Student Number | Entity |
|------|---------------|--------|
| Stephanie Tola Oluwafemi Lewu (Team Lead) | 230211216 | Member |
| Tanatswa Mabhodha | 220637482 | Booking |
| Owen Jnr Makene | 223219665 | Payment |
| Thandeka Chantal Malande | 222857005 | Insurance |
| Malwandla Blessing Mahori | 230962963 | Car |
| Solomon Elias Machaule | 222359366 | Branch |

---

## How The System Works
- A **Member** registers on the system with their personal details
- The member browses available **Cars** at a **Branch**
- The member creates a **Booking** by selecting a car, start date and end date
- An **Insurance** policy is attached to the booking
- A **Payment** is processed for the booking
- The total cost is calculated based on the car's daily rate and rental duration

---

## Project Structure

src/
└── main/
    └── java/
        └── za/ac/cput/
            ├── domain/       # Entity classes
            ├── factory/      # Factory classes
            └── repository/   # Repository interfaces and implementations
└── test/
    └── java/
        └── za/ac/cput/
            ├── factory/      # Factory test classes
            └── repository/   # Repository test classes

---

## Package Descriptions

### Domain Package
The domain package contains the entity classes of the system.
Each entity represents a real world object in the Car Rental System
such as Booking, Car, Member, Payment, Insurance and Branch.
The entities are built using the Builder Pattern which allows
objects to be created step by step in a controlled way.

### Factory Package
The factory package contains the factory classes for each entity.
A factory class is responsible for creating instances of an entity.
It centralizes the creation of objects so that the rest of the
system does not need to worry about how objects are created.
This follows the Domain Driven Design (DDD) principle of factories.

### Repository Package
The repository package contains the interfaces and implementation
classes for storing and retrieving entities.
Each repository provides the basic CRUD operations which are
Create, Read, Update and Delete.
This follows the Domain Driven Design (DDD) principle of repositories
and ensures the system codes to abstraction not concretion.

### Factory Test Package
The factory test package contains the test classes for each factory.
These tests verify that the factory classes are creating objects
correctly. This follows the Test Driven Development (TDD) approach
where tests are written to prove the code works as expected.

### Repository Test Package
The repository test package contains the test classes for each
repository. These tests verify that the CRUD operations are working
correctly for each entity. This ensures the repository classes
are functioning as expected before the code is merged.


---

## Entities Implemented
- **Member** - Stephanie Tola Oluwafemi Lewu (230211216)
- **Booking** - Tanatswa Mabhodha (220637482)
- **Payment** - Owen Jnr Makene (223219665)
- **Insurance** - Thandeka Chantal Malande (222857005)
- **Car** - Malwandla Blessing Mahori (230962963)
- **Branch** - Solomon Elias Machaule (222359366)

---

## Group Members Github Links
- Tanatswa Mabhodha - https://github.com/Tanatswa-Mabhodha-22/Capstone-.git
- Thandeka Chantal Malande - https://github.com/ThandekaChantal
- Stephanie Lewu - https://github.com/stephanie-lewu/Capstone-
- Malwandla Blessing Mahori - https://github.com/MalBl3ssing/Capstone-.git
- Owen Jnr Makene **(Contributer)** - https://github.com/stephanie-lewu/Capstone-.git
- Solomon Elias Machaule - https://github.com/solomon2608/Capstone-.git

---

## How The System Works
- A **Member** registers on the system with their personal details
- The member browses available **Cars** at a **Branch**
- The member creates a **Booking** by selecting a car, start date and end date
- An **Insurance** policy is attached to the booking
- A **Payment** is processed for the booking
- The total cost is calculated based on the car's daily rate and rental duration

---

## Project Structure

src/
└── main/
    └── java/
        └── za/ac/cput/
            ├── domain/       # Entity classes
            ├── factory/      # Factory classes
            └── repository/   # Repository interfaces and implementations
└── test/
    └── java/
        └── za/ac/cput/
            ├── factory/      # Factory test classes
            └── repository/   # Repository test classes


---

## Entities Implemented
- **Member** - Stephanie Tola Oluwafemi Lewu (230211216)
- **Booking** - Tanatswa Mabhodha (220637482)
- **Payment** - Owen Jnr Makene (223219665)
- **Insurance** - Thandeka Chantal Malande (222857005)
- **Car** - Malwandla Blessing Mahori (230962963)
- **Branch** - Solomon Elias Machaule (222359366)

---

## Technologies Used
- Java
- Maven
- JUnit 5
- IntelliJ IDEA
- GitHub



---


# Car Rental System
#UML Class Diagram
<img width="2614" height="1402" alt="Flowchart (2)" src="https://github.com/user-attachments/assets/249814ef-30b9-43cf-94b0-e8eb552b1be5" />

