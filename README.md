# Test Exam Notes

## Overview
- [Static analysis](#static)
- [Test levels](#levels)
- [Non coding test](#nocode)
- [Test activities](#activites)
- [Code quality](#quality)
- [Maintainable code](#maintainable)
- [Unit test](#unit)
- [Test driven development](#tdd)
- [Test doubles](#doubles)
- [Software quality](#qaulitysw)
- [Dependencies](#dependencies)
- [Test automation](#ci)
- [Specification-based testing](#specification)

## <a name="static"></a>Static analysis
[Static analysis](https://www.youtube.com/watch?v=d_BCGvXbpKs) can on a broad spectrum be described as something that helps you maintain a healthy codebase without actually running any code. Most IDEs come with built in linters, or have plugin available to them, which makes it easy to install and utilize linters for a specific framework. Furthermore, many linters can be run via the CLI, making them easily extendable and shareable.

### Linting
Linting comes with a subset of categories, here amongst syntax and structured linting. Linting is essentially checking the code if specific rules are complied with, as well as spelling of certain keywords in a given contex. Furthermore linting can assist with setting the standard for how the code should be formulated, ensuring the quality and readability of the code. However this all comes down to the lint settings and linter the individual person is using.

## <a name="levels"></a>Test levels
Several testing levels can be defined and they each serve their own purpose.

### Unit testing
Unit testing is the lowest level of testing, where a single "unit" is tested. This is to ensure the unit works on its own. Unit testing is done by developers.

### [Intergration testing](https://www.youtube.com/watch?v=QYCaaNz8emY&list=PLDC2A0C8D2EC934C7&index=6)
In this phase of testing, individual units are combined and tested as a group. Data transfer between the modules is tested thoroughly. Intergration testing is done by testers.

#### Intergration test methods
- Big bang test; Wait untill all intertwained modules are ready
- Incremental testing; Test as modules becomes available

- Top down approach; Requires stubs - develop higher level modules first.
- Bottom up approach; Requries drivers - develop lower level modules first.

### [System testing](https://www.youtube.com/watch?v=N8-qNMHOVyw&list=PLDC2A0C8D2EC934C7&index=5)
System testing is concerned with the behavioor of the system as a whole, unlike intergration testing, which focuses on data transfer between units. System testing checks complete end to end scenarios, as the consumer would use the system.

### Acceptance testing
Acceptance test is usually done at client location by the client. The focus on acceptance test is not to find system defects, but rather to see if the software meets their requirements.

#### Alpha testing
- A small set of employees test the software

#### Beta testing
- A small set of customers test the software

## <a name="nocode"></a>Non coding test

### Reviews
A normal review is done by peers, one where you get isntant feedback would be with pair-programming.

### Technical reviews
Technical review is a form of peer review in which a team or qualified personnel examines the suitability of the software product. If a technical leads handles code reviews, this would fall under the category of technical review.

### Management reviews

### Audit

### Static analysis

### Linters

## <a name="activites"></a>Test activities

## <a name="quality"></a>Code quality
Code quality can meassured in several different ways. The development team most likely has a coding standard, so the initial check would be to see if the coding standard has been followed. Next would be to make sure the teams linter is satisfied, and the two things can often be one and the same. High quality code should be testable, which means their headers, and return values are well thought out.

## <a name="maintainable"></a>Maintainable code

## <a name="unit"></a>Unit testing
Unit test is the lowes level of functional testing. Unit test should cover a single unit or functionality. Looking at a bank project, check ballance would be a unit test, if the class or function itself is responsible for returning this output. Given a user would have to be authenticated to check their account, login with correct credentials would also be a suitable unit test, just like login with wrong credentials, which would be a negative test.

## <a name="tdd"></a>Test driven development
Test driven development is the idea of coding test first. Which means that initially a new module is created by creating the test suitable for said module. The idea is that, if you've written the test, you've practically written the code, and it ensure testable code, as well as tests.

## <a name="doubles"></a>Test doubles

## <a name="qaulitysw"></a>Software quality 

## <a name="dependencies"></a>Dependencies

## <a name="ci"></a>Test automation
Continious intergration and Continous Development is hot topics that continously run your unit test or a specified bunch of test everytime a push or pull is made from the repo. Again these things can be fiddled with in the settings, but generally speaking this is the idea.

## <a name="specification"></a>Specification-based testing