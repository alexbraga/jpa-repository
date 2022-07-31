<h1 align="center">
  JPA Repository
</h1>

<h3 align="center">
    Java Spring Boot REST API with Spring Data JPA and H2 Database
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

<p align="justify">A REST API written in Java with Spring Boot and Spring Data JPA to query for informations on users. The database chosen is the in-memory H2 Database, for testing and demonstration purposes.</p>

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
2. Compile the code
3. Run `JpaRepositoryApplication.java`

### Pre-requisites

Before you begin, you will need to have the following tools installed on your
machine:
- [Git](https://git-scm.com)
- [Java OpenJDK](https://www.oracle.com/java/technologies/downloads/)

In addition, you might also want an IDE to work with the code, like
[IntelliJ IDEA](https://www.jetbrains.com/idea/).

#### Clone this repository

```
git clone https://github.com/alexbraga/jpa-repository.git
```

#### API Endpoints

- Get all users in the database:
  - `/users`

- Get all users, with pageable results:
  - `/users/page?page={page_number}&size={size}`

- Search users by salary range:
  - `/users/search-salary?minSalary={min_value}&maxSalary={max_value}`

- Search users by name:
  - `/users/search-name?name={user_name}`

---

## Tech Stack

The following tools were used in the construction of the project:

#### **Language**

- **[Java OpenJDK 11](https://www.oracle.com/java/technologies/downloads/)**

#### **Dependencies**

- Spring Web
- Spring Data JPA
- H2 Database

> See the file
> [pom.xml](https://github.com/alexbraga/jpa-repository/blob/master/pom.xml)

#### **Utilities**

- Dependency Manager: **[Maven](https://maven.apache.org/)**
- Database Manager: **[DBeaver](https://dbeaver.io/)**
- IDE: **[IntelliJ IDEA](https://www.jetbrains.com/idea/)**
- API Testing: **[Postman](https://postman.com)**

---

## How to contribute

1. Fork the project
2. Create a new branch with your changes: `git checkout -b my-amazing-feature`
3. Save your changes and create a commit message (in present tense) telling what
   you did: `git commit -m "Add my-amazing-feature"`
4. Submit your changes: `git push origin my-feature`

---

## Author

<p>Alexandre Braga</p>

[![Twitter Badge](https://img.shields.io/badge/-@_alex_braga-1ca0f1?style=flat-square&labelColor=1ca0f1&logo=twitter&logoColor=white)](https://twitter.com/_alex_braga)
[![Linkedin Badge](https://img.shields.io/badge/-Alexandre%20Braga-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/alexgbraga/)
[![Gmail Badge](https://img.shields.io/badge/-contato@alexbraga.com.br-c14438?style=flat-square&logo=Gmail&logoColor=white)](mailto:contato@alexbraga.com.br)

---

<!-- ## License

This project is under the [MIT License](./LICENSE). -->
