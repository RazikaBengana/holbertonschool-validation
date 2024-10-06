<div align="center">
<br>

![Testing_in_the_software_development_methodology.png](README-image/testing_in_the_software_development_methodology.png)

</div>


<p align="center">
<img src="https://img.shields.io/badge/-DEVOPS-yellow">
<img src="https://img.shields.io/badge/-Linux-lightgrey">
<img src="https://img.shields.io/badge/-WSL-brown">
<img src="https://img.shields.io/badge/-Ubuntu%2020.04.4%20LTS-orange">
<img src="https://img.shields.io/badge/-JetBrains-blue">
<img src="https://img.shields.io/badge/-Holberton%20School-red">
<img src="https://img.shields.io/badge/License-not%20specified-brightgreen">
</p>


<h1 align="center"> Testing in the Software Development Methodology </h1>


<h3 align="center">
<a href="https://github.com/RazikaBengana/holbertonschool-validation/tree/main/module2#eye-about">About</a> •
<a href="https://github.com/RazikaBengana/holbertonschool-validation/tree/main/module2#hammer_and_wrench-tasks">Tasks</a> •
<a href="https://github.com/RazikaBengana/holbertonschool-validation/tree/main/module2#memo-learning-objectives">Learning Objectives</a> •
<a href="https://github.com/RazikaBengana/holbertonschool-validation/tree/main/module2#computer-prerequisites">Prerequisites</a> •
<a href="https://github.com/RazikaBengana/holbertonschool-validation/tree/main/module2#mag_right-resources">Resources</a> •
<a href="https://github.com/RazikaBengana/holbertonschool-validation/tree/main/module2#bust_in_silhouette-authors">Authors</a> •
<a href="https://github.com/RazikaBengana/holbertonschool-validation/tree/main/module2#octocat-license">License</a>
</h3>

---

<!-- ------------------------------------------------------------------------------------------------- -->

<br>
<br>

## :eye: About

<br>

<div align="center">

**`Testing in the software development methodology`** module explores **the importance of testing within the software development lifecycle**.
<br>
It introduces tools and techniques for continuous testing, allowing for the identification of bugs and issues early in the development process.
<br>
`Hugo` remains a core part of the framework, while testing tools are integrated into the automation pipeline.
<br>
<br>
This project has been created by **[Holberton School](https://www.holbertonschool.com/about-holberton)** to enable every student to understand how **DevOps workflows**, **testing practices**, **CI/CD**, and **containerization** work.

</div>

<br>
<br>

<!-- ------------------------------------------------------------------------------------------------- -->

## :hammer_and_wrench: Tasks

<br>

**`0. Build an Application using Make`**

**`1. Static Analysis (Lint) with Golang`**

**`2. Unit Tests with Code Coverage`**

**`3. Integration Tests with Golang`**

**`4. Testing a Static Website`**

**`5. Avengers Assemble: Putting All The Bricks Together`**

<br>
<br>

<!-- ------------------------------------------------------------------------------------------------- -->

## :memo: Learning objectives

<br>

This project aims at practicing with automated tests. 
<br>
<br>
The goal is to understand the pros and cons of different testing methods to be able to understand the value of doing, or not doing, a kind of test.

<br>

**_After this project, you should be able to:_**

<br>

```diff

+ Understand what linting is the extent of its usages (which kind of file can be linted, and the impact of running it often)

+ Understand the difference between unit tests and integration tests

+ Use code coverage as a helper to write tests

+ Understand that not only “classical” code is to be tested, but also a lot of the artifacts we can generate

+ Understand how “component”-based testing for acceptance and end to end validation is to be used

```

<br>
<br>

<!-- ------------------------------------------------------------------------------------------------- -->

## :computer: Prerequisites

<br>

The following elements are required In addition to the previous module (**“Module 1: Introduction to DevOps: Automate Everything to Focus on What Really Matters”**) prerequisites.

<br>
<br>

### Concepts

<br>

**You should have a basic knowledge of the following concepts:**

<br>

- What a compiled language is (`C`/`C#`/`Golang`/`Rust`/etc.)

    - Generation process from source to executable binary
    - Basic types: `string`, `integer`, `boolean`, `maps`, `arrays`
    - Basic algorithmic: `loops`, `conditional`, `functions`

- Installing command line tools with `NPM` (in addition to package managers)

- Understand the basics of the `HTTP` protocol (client/server, verbs, headers)

<br>
<br>

### Tooling

<br>

This project needs the following tools / services:

<br>

- Same tools as previous module

- [Golang](https://go.dev/) in `v1.15.*`

- [NPM](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm/) `v7+` with [NodeJS](https://nodejs.org/en/download/) `v14.*` (stable)

- [Python 3 with pip module](https://docs.python.org/3/installing/index.html)

- [golangci-lint](https://github.com/golangci/golangci-lint)

<br>
<br>

### Story

<br>

Following the previous module situation, you are now able to build and deploy the static website for the company **Awesome Inc**. in an automated way.

As the communication team is happy with your work, you’ve been tasked to add an `HTTP API` to improve the website.

You want to ensure that the shipped software is without bugs.

You’ll test each component of this new website to ensure that there will be no regression in the future, and to make sure that any refactoring or change can be done with confidence.

The `API` is written in the [Golang](https://go.dev/) language but there is no need to be familiar with the language.

While the production team is building the new production platform for the website, you’ve been tasked to create an `HTTP API` application to add new features.

As we are in a **“DevOps”** course, your “Ops” personality expects that this application is monitored by a “Health” page to determine if the application is running and ready to accept traffic.

<br>
<br>

<!-- ------------------------------------------------------------------------------------------------- -->

## :mag_right: Resources

<br>

**_Do you need some help?_**

<br>

**Read or watch:**

* [A Tour of Go](https://tour.golang.org/welcome/1)

* [Unit Test](http://martinfowler.com/bliki/UnitTest.html)

* [Software Testing](https://en.wikipedia.org/wiki/Software_testing)

* [Testing](http://martinfowler.com/tags/testing.html)

* [Test Coverage](http://martinfowler.com/bliki/TestCoverage.html)

* [Test Driven Development](http://martinfowler.com/bliki/TestDrivenDevelopment.html)

* [curl Man Page](https://curl.se/docs/manpage.html)

* [pgrep(1) Linux Man Page](https://linux.die.net/man/1/pgrep)

* [markdownlint-cli](https://github.com/igorshubovych/markdownlint-cli)

* [Go - All Releases](https://go.dev/dl/)

* [golangci-lint](https://github.com/golangci/golangci-lint)

* [Go - io package - WriteString](https://go.dev/pkg/io/#WriteString)

* [The Blank Identifier in Golang](https://golangdocs.com/blank-identifier-in-golang)

* [Error Handling and Go](https://blog.golang.org/error-handling-and-go)

* [Automatic Prerequisites](https://www.gnu.org/software/make/manual/html_node/Automatic-Prerequisites.html)

* [Installing Python Modules](https://docs.python.org/3/installing/index.html)

* [Download Node.js](https://nodejs.org/en/download/)

* [Downloading and Installing Node.js and npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm/)

* [W3C Validator](https://github.com/hs-hq/W3C-Validator)

* [npm - markdown-link-check](https://www.npmjs.com/package/markdown-link-check)

<br>
<br>

<!-- ------------------------------------------------------------------------------------------------- -->

## :bust_in_silhouette: Authors

<br>

**${\color{blue}Razika \space Bengana}$**

<br>
<br>

<!-- ------------------------------------------------------------------------------------------------- -->

## :octocat: License

<br>

```Testing in the software development methodology``` _project has no license specified._

<br>
<br>

---

<p align="center"><br>2023</p>