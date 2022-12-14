# 00_Stakeholder_Expectations.md

THIS DOCUMENT IS PART OF THE TECHNICAL REQUIREMENTS DEFINITION PROCESS (TRDP), THAT TRANSFORMS THE STAKEHOLDERS EXPECTATIONS INTO A DEFINITION OF THE PROBLEM AND THEN INTO A COMPLETE SET OF VALIDATED TECHNICAL REQUEREMENTS EXPRESSED AS "SHALL" STATEMENTS. THE GOAL OF THE TECHNICAL REQUIREMENT DEFINITION PROCESS IS THE DEFINITION AND DESING OF SOLUTIONS FOR THE END PRODUCT BREAKDOWN STRUCTURE (EPBS).

## 1. Introduction

A 6DOF Motion Platform (also known as Stewart Platform), is a type of parallel manipulator that has six prismatic actuators, commonly hydraulic jacks or electric linear actuators, attached in pairs to three positions on the platform's baseplate, crossing over to three mounting points on a top plate. Devices placed on the top plate can be moved in the six degrees of freedom in which it is possible for a freely-suspended body to move: Three linear movements and three rotations.

The Stewart platform design is extensively used in flight simulators, particularly in the full flight simulator which requires all 6 degrees of freedom.

## 2. List of Stakeholders

- Project Sponsor
- STEAM Instructor
- STEAM Assistant
- Student

## 3. Stakeholder Expectations

### 3.1 Mission Objetives & Constraints

Design and build a 6DOF Motion Platform - MP with low-cost materials and prototyping electronics, portable design and resistant to transportation for STEAM trainig purposes.

### 3.2 Operational Objectives

The design of the MP will follow the Arcadia's MBSE methodology and the Capella tool.

Document change control will be maintained throughout the project.

Additionally, good practices described in "NASA System Engineering Handbook", "INCOSE Systems Engineering Handbook A Guide for System Life Cycle Processes and Activities" and "Model-Based Requirements Engineering" will be taken as a reference.

### 3.3 Mission and Operational Success Criteria

**Mission Criteria**
The established mission criteria are:

- The design of the MP must be safe both for users and for transportation. The mobile or delicate parts must be protected so that they are manipulated by children 10 years of age and older.
- The MP will connect with a flight simulator to imitate the flight attitude of the aircraft.
- The MP will have a LCD screen with a keyboard to change the modes of operation. It will be integrated with a voice assistant like Alexa to switch modes of operation in the same way.
- The MP will have visual and sound indications, and interfaces to peripherals such as an external keyboard or joystick.
- The MP will have its digital twin that will interact with the real MP.

**Operational Criteria**
The established operational criteria are:

- Document change control will be maintained using the GIT tool.
- Remote repositories will be hosted on GitHub.
- The semantic versioning will follow will follow the guidelines indicated in: <https://semver.org/>
- There will be the following repositories: a. STWRT-CAD for the Computer-Aided Design, b. STWRT-SKETCH for the Sketch Code, c. STWRT-MBSE for the Model Based System Engineering, d. STWRT-DOCS for documents and support, e. STWRT-DT for Simulation and Digital Twins and f. STWRT-PROJECT for consolidation of all repositories and project management execution.
- The repositories will have at least two branches: a. main and b. dev-master. The atomic changes will be made on the dev-master branch. Once the changes from the dev-master branch are approved, they will be merged into the main branch and published with a TAG number with the same semantic version number.
- The desing will follow each step of the Arcadia's MBSE Methodology.
- The Scrum Methology will be implemente during each step of the Arcadia's MBSE Methodology.
- During each step of the Arcadia's MBSE Methodology, the Product Backlog, Sprint Backlog and the Increments (Scrum Artifacts) will be commited in the dev-master branch of the respository. Once aproved the deliverables of the step, the dev-master will be merged into the main branch and published with a TAG number with the same semantic version number.
- The "NASA System Engineering Handbook" will be used as a supplementary reference. In case of inconsistency with the Arcadia's MBSE Methodology, the Arcadia's MBSE Methodology will prevail, including the lexicon.
- The "INCOSE Systems Engineering Handbook A Guide for System Life Cycle Processes and Activities" will be used as a supplementary reference in those areas of knowledge not covered by Arcadia's MBSE Methodology and "NASA System Engineering Handbook".
