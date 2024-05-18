# University Room Reservation System

## Overview
This project aims to develop a secure, online room reservation system for university usage, allowing users to perform all reservation operations. The project follows a disciplined software engineering approach, integrating Software Quality Assurance (SQA) techniques such as inspection, validation, and verification throughout the development cycle.

## Project Description
The goal of this project is to specify a room reservation system for university usage with a graphical interface that allows users to perform all reservation operations online and securely. The system will account for the type of rooms (conference, teaching, and lab), their capacity, and their status (available or not in a given time slot).

## Deliverable 1: Software Requirements Specification (SRS)
### Introduction
The SRS provides a thorough and detailed list of information needed to design and implement the room reservation software.

#### Purpose
To provide a comprehensive list of requirements for the development of the room reservation system.

#### Scope
- An online, secure interface for performing all reservation operations.
- The system associates a room to a user for a specified time.
- The system ensures secure room reservations based on user rights and room specifications.

### General Description
#### Product Perspective
The room reservation software is designed for a university intranet, supporting databases and other software, ensuring secure user access.

#### Product Functions
The software will manage room reservations based on date, time, duration, user rights, and reservation rules.

### Specific Requirements
#### Functional Requirements
- **Reservation of a room**: Users can reserve rooms for specified time slots.
- **Modification of a reservation**: Users can modify their reservations.
- **Removing a reservation**: Users can remove their reservations.
- **Check if a room is reserved**: Users can check room availability.

### Analysis Models
The SRS includes sequence diagrams, state-transition diagrams, and data flow diagrams to represent various processes and interactions.

### Change Management Process
The process involves structured steps to handle changes in project scope or requirements, ensuring the SRS remains aligned with project objectives.

For more details, refer to the [Software Requirements Specification](./software_requirenment.pdf).

## Deliverable 2: Acceptance Test Plan
### Overview
The Acceptance Test Plan outlines the procedures and criteria to verify that the developed room reservation software meets the specified requirements in the SRS.

#### Purpose
To ensure the system meets the specified requirements and is secure for university usage.

#### Scope
Covers all functional and non-functional requirements, including room reservations, modifications, cancellations, user interface accessibility, system performance, reliability, security, maintainability, and portability.

### Testing
#### General Approach
Testing will occur within the university's intranet environment, structured into phases including user scenario testing, boundary testing, and security testing. Stakeholders such as students, teachers, administrative staff, and IT personnel will participate.

#### System Testing
Conducted jointly by development personnel and project-assigned personnel, focusing on system functionality and integration.

#### Acceptance Testing
Conducted by the Business Unit, focusing on verifying the system against predefined criteria and scenarios.

### Testing Prerequisites
The room reservation software must pass the developer’s Quality Assurance process before acceptance testing.

### Testing Procedure
A series of tests will be executed to ensure the system functions as specified, with results documented systematically.

For more details, refer to the [Acceptance Test Plan](./Acceptance-Test.pdf).

## Authors
- Merlin Duval - 40286249
- Yash Khosla - 40232363


For more detailed information, please refer to the [Software Requirements Specification](./software_requirenment.pdf) and the [Acceptance Test Plan](./Acceptance-Test.pdf).
