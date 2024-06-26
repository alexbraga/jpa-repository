<h1 align="center">
  JPA Repository
</h1>

<h3 align="center">
    Java Spring Boot API with Spring Data JPA and H2 Database
</h3>

<p align="center">
  <a href="https://github.com/alexbraga/jpa-repository/commits/master"><img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/alexbraga/jpa-repository"></a>
  <!-- <a href="https://github.com/alexbraga/jpa-repository/blob/master/LICENSE"><img alt="GitHub license" src="https://img.shields.io/github/license/alexbraga/jpa-repository?label=license"></a> -->
</p>

<h4 align="center">
	 Status: Finished
</h4>

<p align="center">
 <a href="#about">About</a> •
 <a href="#features">Features</a> •
 <a href="#how-it-works">How it works</a> •
 <a href="#tech-stack">Tech Stack</a> •
 <a href="#how-to-contribute">How to contribute</a> •
 <a href="#author">Author</a> <!--•
 <a href="#license">License</a> -->

</p>

## About

<p align="justify">An API written in Java with Spring Boot and Spring Data JPA to query for information on users. The database chosen is the in-memory H2 Database, for testing and demonstration purposes.</p>

---

## Features

- Structure divided into Entities, Repositories and Controllers
- Pageable results
- Query parameters for filtering between values
- Classes and objects
- Encapsulation, getters and setters
- Object-Relational Mapping

---

## How it works

1. <a href="#clone-this-repository">Clone this repository</a>
2. <a href="#running-the-application">Run the application</a>
3. <a href="#api-endpoints">API Endpoints</a>

### Pre-requisites

Before getting started, you'll need to have the following tools installed on your machine:

- [Git](https://git-scm.com)
- [Java OpenJDK](https://www.oracle.com/java/technologies/downloads/)
- [Maven](https://maven.apache.org/)

In addition, you might also want an IDE to work with the code, like
[IntelliJ IDEA](https://www.jetbrains.com/idea/).

### Clone this repository

```
git clone https://github.com/alexbraga/jpa-repository.git
```

### Running the application

Navigate to the root directory of the project
```
cd jpa-repository
```

Build the project
```
mvn compile
```

Run the application
```
mvn spring-boot:run
```

- Alternatively, open the project with your preferred IDE and run `/src/main/java/com/example/jparepository/JpaRepositoryApplication.java`
- The server will start at `localhost:8080`

### API Endpoints

- Get all users in the database:
  - `GET` `/users`

- Get all users, with pageable results:
  - `GET` `/users/page?page={page_number}&size={size}`

- Search users by salary range:
  - `GET` `/users/search-salary?minSalary={min_value}&maxSalary={max_value}`

- Search users by name:
  - `GET` `/users/search-name?name={user_name}`

---

## Tech Stack

The following tools were used in the construction of the project:

#### **Language**

- **[Java OpenJDK 11](https://www.oracle.com/java/technologies/downloads/)**

#### **Framework**

- **[Spring](https://spring.io/)**

#### **Dependencies**

- Spring Web
- Spring Data JPA
- H2 Database

> See the file
> [pom.xml](https://github.com/alexbraga/jpa-repository/blob/master/pom.xml)

#### **Utilities**

- Dependency Manager: **[Maven](https://maven.apache.org/)**
- IDE: **[IntelliJ IDEA](https://www.jetbrains.com/idea/)**
- API Testing: **[Postman](https://postman.com)**

---

## How to contribute

1. Fork the project
2. Create a new branch with your changes:
```
git checkout -b my-amazing-feature
```
3. Save your changes and create a commit message (in present tense) telling what you did:
```
git commit -m "Add my amazing feature"
```
4. Submit your changes:
```
git push origin my-amazing-feature
```
5. Create a pull request

---

## Author

<h4>Alexandre Braga</h4>

<div>
<a href="https://www.linkedin.com/in/alexgbraga/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-blue?style=for-the-badge&logo=Linkedin&logoColor=white" alt="LinkedIn"></a>&nbsp;
<a href="mailto:contato@alexbraga.com.br" target="_blank"><img src="https://img.shields.io/badge/-email-c14438?style=for-the-badge&logo=Gmail&logoColor=white" alt="E-Mail"></a>
</div>

<!-- ## License

This project is under the [MIT License](./LICENSE). -->
