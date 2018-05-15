# Test Plan Project Puerto Rico

Version 1.0

## Revision History

| **Date** | **Version** | **Description** | **Author** |
| --- | --- | --- | --- |
| 14.05.2018 | 1.0 | Initial Version | Stephan Stroh, Thomas Pötzsch |

# Table of Contents
- [Introduction](#1-introduction)
    - [Purpose](#11-purpose)
    - [Scope](#12-scope)
    - [Intended Audience](#13-intended-audience)
    - [Document Terminology and Acronyms](#14-document-terminology-and-acronyms)
    - [References](#15-references)
- [Evaluation Mission and Test Motivation](#2-evaluation-mission-and-test-motivation)
    - [Background](#21-background)
    - [Evaluation Mission](#22-evaluation-mission)
    - [Test Motivators](#23-test-motivators)
- [Target Test Items](#3-target-test-items)
- [Outline of Planned Tests](#4-outline-of-planned-tests)
    - [Outline of Test Inclusions](#41-outline-of-test-inclusions)
    - [Outline of Other Candidates for Potential Inclusion](#42-outline-of-other-candidates-for-potential-inclusion)
    - [Outline of Test Exclusions](#43-outline-of-test-exclusions)
- [Test Approach](#5-test-approach)
    - [Testing Techniques and Types](#51-testing-techniques-and-types)
- [Entry and Exit Criteria](#6-entry-and-exit-criteria)
    - [Test Plan](#61-test-plan)
- [Deliverables](#7-deliverables)
    - [Test Evaluation Summaries](#71-test-evaluation-summaries)
    - [Reporting on Test Coverage](#72-reporting-on-test-coverage)
    - [Perceived Quality Reports](#73-perceived-quality-reports)
    - [Incident Logs and Change Requests](#74-incident-logs-and-change-requests)
    - [Smoke Test Suite and Supporting Test Scripts](#75-smoke-test-suite-and-supporting-test-scripts)
- [Testing Workflow](#8-testing-workflow)
- [Environmental Needs](#9-environmental-needs)
    - [Base System Hardware](#91-base-system-hardware)
    - [Base Software Elements in the Test Environment](#92-base-software-elements-in-the-test-environment)
    - [Productivity and Support Tools](#93-productivity-and-support-tools)
- [Responsibilites, Staffing and Training Needs](#10-responsibilities-staffing-and-training-needs)
    - [People and Roles](#101-people-and-roles)
    - [Staffing and Training Needs](#102-staffing-and-training-needs)
- [Iteration Milestones](#11-iteration-milestones)
- [Risks, Dependencies, Assumptions and Constraints](#12-risks-dependencies-assumptions-and-constraints)

## 1. Introduction
###  1.1 Purpose

The purpose of the Iteration Test Plan is to gather all of the information necessary to plan and control the test 
effort for a given iteration. It describes the approach to testing the software, and is the top-level plan generated 
and used by managers to direct the test effort.

This Test plan for Poject Puerto Rico supports the following objectives:
- Identifying the items that should be targeted by the tests.
- Identifying the motivation for and ideas behind the test areas to be covered.
- Outlining the testing approach that will be used.
- Identifying the required resources and providing an estimation for the test efforts.

### 1.2 Scope

Project Puerto Rico is tested using unit tests as a testing method to ensure that the implementation is working 
correctly throughout the development.

### 1.3 Intended Audience

This document is written for internal usage by the project team and contains technically detailed informations.
The description of the application itself is not part of it. Therefore this document is for the developement team and 
for readers with the necessary background knowledge.

### 1.4 Document Terminology and Acronyms

| Abbr | Abbreviation                        |
|------|-------------------------------------|
| CI   | Continuous Integration              |
| n/a  | not applicable                      |
| SRS  | Software Requirements Specification |
| tbd  | to be determined                    |
| TDD  | Test Driven Development             |
| UI   | User Interface                      |

### 1.5 References
- [Blog](https://poetzschstroh.wordpress.com/)
- [GitHub](https://github.com/DrFelder/ppr)
- [Documentation](https://github.com/DrFelder/ppr-documentation)
- [Use Case Diagram](https://github.com/DrFelder/ppr-documentation/blob/master/Diagrams/PPR-UseCases.jpg)
- [Risk Management](https://github.com/DrFelder/ppr-documentation/blob/master/ProjectManagement/RiskManagement.md)

### 1.6 Document Structure
See Table of Contents

## 2. Evaluation Mission and Test Motivation

### 2.1 Background

The test coverage for our project leads to a better control of new implementations and the changes made to existing code.
It gives us a better possibility to make sure that future changes won't influence the functionality in a negative way. The 
integration of testing into the deployment process ensures that just stable versions which meet our quality requirements 
are being deployed.

### 2.2 Evaluation Mission
 
The main reason for implementing tests is to ensure that occurring problems are identified as early as possible. This
leads to stable and working versions of our project. Continuous testing provides us the opportunity to automatically 
verify the functionality of our project. With Test Driven Development (TDD) the tests are written before 
the functionality itself gets implemented. This helps to prevent problems before they occur.

### 2.3 Test Motivators

The motivation to use testing in our project was to reduce functional risks and keep the quality as high as possible. 
It helps to fulfill the needed requirements and is good for implementing the Use Cases by checking the correct working 
results.

## 3. Target Test Items

The following list identifies the tested parts of our application. Tests will cover the main backend functionality as 
well as the logical implementations.

- Controller
- Model

## 4. Outline of Planned Tests


### 4.1 Outline of Test Inclusions

Backend functionality will be tested with unit tests.

Logical functionality will be tested with unit tests.

### 4.2 Outline of Other Candidates for Potential Inclusion

An additional option for testing would be the user interface as well as the testing of the performance of the application.

### 4.3 Outline of Test Exclusions

n/a

## 5. Test Approach
### 5.1 Initial Test-Idea Catalogs and Other Reference Sources
The concept of unit testing is to structure the code into pieces that are as small as possible. These units ar going to 
be tested individually to check the functionality on the lowest possible level. Due to this partitioning of the 
implementation, bugs and problems can be found rather easily. If the granular functionalities have been approved, 
the units can be put together to modules, which then will be tested on this higher level. Unit Testing has proven to 
be a good way to find bugs and problems in software early and reliable.

### 5.2 Testing Techniques and Types

#### 5.2.1 Data and Database Integrity Testing
n/a

#### 5.2.2 Function Testing

| Technique Objective: | Assert correct behavior of each functionality of the project |
| --- | --- |
| Technique: | Creation of unit tests for each functionality that is part of model or controller |
| Oracles: |  Successful execution of unit tests in Unity Test Runner - Successful execution of unit tests on build |
| Required Tools: | TBD |
| Success Criteria: | All tests pass and the required code coverage is given. TravisCI build passes and all tests run green |
| Special Considerations: | -|

#### 5.2.3 Business Cycle Testing
n/a

#### 5.2.4 User Interface Testing
n/a

#### 5.2.5 Performance Profiling
n/a

#### 5.2.6 Load Testing
n/a

#### 5.2.7 Stress Testing
n/a

#### 5.2.8 Volume Testing
n/a

#### 5.2.9 Security and Access Control Testing
n/a

#### 5.2.10 Failover and Recovery Testing
n/a

#### 5.2.11 Configuration Testing
n/a

#### 5.2.12 Installation Testing
n/a

## 6. Entry and Exit Criteria
### 6.1Test Plan
#### 6.1.1 Test Plan Entry Criteria
The execution of the test plan can begin as soon as the first unit test is written and a new version of the 
application was committed to GitHub and built.

#### 6.1.2 Test Plan Exit Criteria
The execution of the Test Plan is completed when all test run without errors and the project is finished.

#### 6.1.3 Suspension and Resumption Criteria
The test plan is not supposed to be suspended. Therefore, there are no suspension and resumption criteria.  

### 6.2 Test Cycles

#### 6.2.1 Test Cycle Entry Criteria
A test cycle begins when the build of a new version is initiated.

#### 6.2.2 Test Cycle Exit Criteria
The test effort of a cycle is deemed sufficient when a build has been completed without failures and all unit tests are run successfully.

#### 6.2.3 Test Cycle Abnormal Termination
Occurring errors during the build terminate the test cycle.

## 7.Deliverables

### 7.1 Test Evaluation Summaries


### 7.2 Reporting on Test Coverage
n/a

### 7.3 Perceived Quality Reports
n/a

### 7.4 Incident Logs and Change Requests


### 7.5 Smoke Test Suite and Supporting Test Scripts
n/a

### 7.6 Additional Work Products
n/a

#### 7.6.1 Detailed Test Results


#### 7.6.2 Additional Automated Functional Test Scripts
n/a

#### 7.6.3 Test Guidelines
n/a

#### 7.6.4 Traceability Matrices
n/a

## 8.Testing Workflow
When an developer adds new functionality to the project, he also writes an appropriate Unit-Test covering the functionality. 
All unit tests are then automatically executed on a build.
The developer can also test parts of the new code by running the tests from his IDE.

## 9. Environmental Needs

### 9.1 Base System Hardware

### 9.2 Base Software Elements in the Test Environment

### 9.3 Productivity and Support Tools

### 9.4 Test Environment Configurations

## 10. Responsibilities, Staffing, and Training Needs
### 10.1 People and Roles

This table displays the staffing assumptions for the test effort of our project.

|Role|Minimum Resources Recommended|Specific Responsibilities|
|-|:-:|-|
|Test Manager|1|Ensures that testing is complete and conducted for the right motivators|
|Test Analyst|1 |Selects what to test based on the motivators|
|Test Designer|1|Decides what tests should be automated vs. manual and creates automations|
|Tester|2|Implements and executes the tests|

### 10.2 Staffing and Training Needs

All necessary roles are staffed by members of the project team. 
# 11. Iteration Milestones
| **Milestone** | **Planned Start Date** | **Actual Start Date** | **Planned End Date** | **Actual End Date** |
| --- | --- | --- | --- | --- |
| Iteration Plan agreed | 14.05.2018  | 14.05.2018  | End of Project |  |
| Iteration starts |  14.05.2018 | 14.05.2017 | End of Project |  |
|>= 20% Test Coverage | 30.05.2018||
|>= 30% Test Coverage | 10.06.2018||
|>= 50% Test Coverage | 20.06.2018||
|Tests integrated in CI | 14.05.2018 | 14.05.2018 | End of Project ||

# 12. Risks, Dependencies, Assumptions, and Constraints
The risk for our project are outlined in our 
<a https://github.com/DrFelder/ppr-documentation/blob/master/ProjectManagement/RiskManagement.md"> risk assessment 
document </a>.

## 13. Management Process and Procedures
### 13.1 Measuring and Assessing the Extent of Testing


### 13.2 Assessing the Deliverables of this Test Plan

### 13.3 Problem Reporting, Escalation, and Issue Resolution
Minor Problems will be fixed by the developer of the task. Major Problems will be escalated and handled 
in an additional YouTrack task. 

### 13.4 Managing Test Cycles
n/a

### 13.5 Traceability Strategies
n/a

### 13.6 Approval and Signoff
This test plan has to be approved by the Test Designer and the Testers.
