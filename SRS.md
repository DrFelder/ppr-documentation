# 1 Introduction

## 1.1 Purpose
This document contains the complete SRS of the Project Puerto Rico.
Project Puerto Rico is going to be designed to make dealing with problems that the government is not talking about easy.
A web interface is designed to allow users from all over the world to create events and specify the resources they need.
These events can contain a description, detailed information that only attendees see, and data such as the location and the date of the event.
Others who wish to participate can apply with their resources and then participate in the event.
Profiles of users inform about the skills and events they have already participated in, to make it easier to find qualified personnel.
Below every technical aspect and feature is described and/or determined.

## 1.2 Scope
This document covers the entire project in every aspect.

## 1.3 Definitions, Acronyms, Abbreviations
- **PPR** - Project Puerto Rico
- **UC** - Use Case
- **UCD** - Use Case Diagram
- **OUCD** - Overall Use Case Diagram
- **SAD** - Software Architecture Document
- **RFC** - Request for Comments

## 1.4 References

|			Title									                            |	Date		|
|-------------------------------------------------------------------------------|---------------|
| [PPR Blog](https://poetzschstroh.wordpress.com/)                              | 21.10.17      |
| [PPR Repository](https://github.com/DrFelder/ppr)                             | 21.10.17      |
| [PPR Documentation Repository](https://github.com/DrFelder/ppr-documentation) | 21.10.17      |
| [PPR Issue Tracker](https://youtrack.surreal.is/)                             | 21.10.17      |

## 1.5 Overview of the SRS
The following chapters are about our vision and perspective, the software requirements, the demands we have, licensing and the technical realisation of this project.

# 2 Overall Description
Everywhere in the world exist problems that governments won't solve.
Many helpers have begun to take on these circumstances to make the world a better place.
Although the helpers are doing the right thing, their actions are mostly illegal.
There is no way to organize such relief activities, and to find qualified personnel and resources.
Our platform is designed to provide a secure way to bring helpers together and organize events.
Users can represent themselves and their skills using a profile, create events, and specify the resources and helper needed.
Others may then apply, and if the project leader considers them to be qualified, participate in the project.
The following diagram shows the UCs:

[![Overall use case diagram](Pictures/PPR-UseCases.jpg)](Pictures/PPR-UseCases.jpg)

# 3 Specific Requirements

## 3.1 Functionality

The requirements are organized by user.

### 3.1.1 User
#### 3.1.1.1 Create account
A new account is created by the user, making it possible for him to log in and use the service.
##### Description

##### Pre Condition

##### Normal Flow of Events
- event

##### Use case diagram
[![Use case diagram](Pictures/)](Pictures/)

##### Workflow diagram
[![Overall use case diagram](Pictures/)](Pictures/)

#### 3.1.1.2 Edit profile
The user edits his profile, providing information about himself.
##### Description

##### Pre Condition

##### Normal Flow of Events
- event

##### Use case diagram
[![Use case diagram](Pictures/)](Pictures/)

##### Workflow diagram
[![Overall use case diagram](Pictures/)](Pictures/)

#### 3.1.1.3 Create Event
An event is created by a user, making him the organizer of the event.
##### Description

##### Pre Condition

##### Normal Flow of Events
- event

##### Use case diagram
[![Use case diagram](Pictures/)](Pictures/)

##### Workflow diagram
[![Overall use case diagram](Pictures/)](Pictures/)

#### 3.1.1.4 Apply for an event
A user applies for participating in an event as a specified role or providing specified resources.
##### Description

##### Pre Condition

##### Normal Flow of Events
- event

##### Use case diagram
[![Use case diagram](Pictures/)](Pictures/)

##### Workflow diagram
[![Overall use case diagram](Pictures/)](Pictures/)

#### 3.1.1.5 Manage applications
An overview over submitted applications and the ability to withdraw them is provided.
##### Description

##### Pre Condition

##### Normal Flow of Events
- event

##### Use case diagram
[![Use case diagram](Pictures/)](Pictures/)

##### Workflow diagram
[![Overall use case diagram](Pictures/)](Pictures/)

#### 3.1.1.6 Chat with another user
The user can chat with another user by inviting him.
##### Description

##### Pre Condition

##### Normal Flow of Events
- event

##### Use case diagram
[![Use case diagram](Pictures/)](Pictures/)

##### Workflow diagram
[![Overall use case diagram](Pictures/)](Pictures/)

#### 3.1.1.7 Access event history
An overview over past events and related information is given.
##### Description

##### Pre Condition

##### Normal Flow of Events
- event

##### Use case diagram
[![Use case diagram](Pictures/)](Pictures/)

##### Workflow diagram
[![Overall use case diagram](Pictures/)](Pictures/)


### 3.1.2 Organizer
#### 3.1.2.1 Edit event
The organizer can edit the event, changing the date or the provided information.
##### Description

##### Pre Condition

##### Normal Flow of Events
- event

##### Use case diagram
[![Use case diagram](Pictures/)](Pictures/)

##### Workflow diagram
[![Overall use case diagram](Pictures/)](Pictures/)

#### 3.1.2.2 Create requirements
The organizer can add requirements to the event (either resources or helpers), and give detailed information.
##### Description

##### Pre Condition

##### Normal Flow of Events
- event

##### Use case diagram
[![Use case diagram](Pictures/)](Pictures/)

##### Workflow diagram
[![Overall use case diagram](Pictures/)](Pictures/)

#### 3.1.2.3 Edit requirements
The organizer can edit the requirements of an event.
##### Description

##### Pre Condition

##### Normal Flow of Events
- event

##### Use case diagram
[![Use case diagram](Pictures/)](Pictures/)

##### Workflow diagram
[![Overall use case diagram](Pictures/)](Pictures/)

#### 3.1.2.4 Accept/reject applications
Applications can be accepted or rejected, informing the user that submitted it.
##### Description

##### Pre Condition

##### Normal Flow of Events
- event

##### Use case diagram
[![Use case diagram](Pictures/)](Pictures/)

##### Workflow diagram
[![Overall use case diagram](Pictures/)](Pictures/)

#### 3.1.2.5 Compare applications
Different applications can be compared, highlighting important facts such as the users overall rating.
##### Description

##### Pre Condition

##### Normal Flow of Events
- event

##### Use case diagram
[![Use case diagram](Pictures/)](Pictures/)

##### Workflow diagram
[![Overall use case diagram](Pictures/)](Pictures/)

#### 3.1.2.6 Start an event
An event can be started by the organizer, which prevents users from applying.
##### Description

##### Pre Condition

##### Normal Flow of Events
- event

##### Use case diagram
[![Use case diagram](Pictures/)](Pictures/)

##### Workflow diagram
[![Overall use case diagram](Pictures/)](Pictures/)

#### 3.1.2.7 Conclude event (mark as success/failure)
After an event is finished, the organizer can set its state either to "succeeded" or "failed".
##### Description

##### Pre Condition

##### Normal Flow of Events
- event

##### Use case diagram
[![Use case diagram](Pictures/)](Pictures/)

##### Workflow diagram
[![Overall use case diagram](Pictures/)](Pictures/)

#### 3.1.2.8 Assess the participants
The participants are being assessed by the organizer.
##### Description

##### Pre Condition

##### Normal Flow of Events
- event

##### Use case diagram
[![Use case diagram](Pictures/)](Pictures/)

##### Workflow diagram
[![Overall use case diagram](Pictures/)](Pictures/)

#### 3.1.2.9 Invite a user to an event
If the organizer wants a specific person to join the group, they can invite them to be a helper.
##### Description

##### Pre Condition

##### Normal Flow of Events
- event

##### Use case diagram
[![Use case diagram](Pictures/)](Pictures/)

##### Workflow diagram
[![Overall use case diagram](Pictures/)](Pictures/)


### 3.1.3 Participant
#### 3.1.3.1 Join the event (access hidden information, join the team chat)
After an application has been accepted, the user can access the team chat and hidden information of the event provided by the organizer.
##### Description

##### Pre Condition

##### Normal Flow of Events
- event

##### Use case diagram
[![Use case diagram](Pictures/)](Pictures/)

##### Workflow diagram
[![Overall use case diagram](Pictures/)](Pictures/)

#### 3.1.3.2 Assess team leaders
After the event is concluded, participants can assess the team leader.
##### Description

##### Pre Condition

##### Normal Flow of Events
- event

##### Use case diagram
[![Use case diagram](Pictures/)](Pictures/)

##### Workflow diagram
[![Overall use case diagram](Pictures/)](Pictures/)
