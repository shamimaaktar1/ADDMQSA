# ADDMQSA
## This is the replication package for the study: "Decision Models for Selecting Patterns and Strategies in Quantum Systems and their Evaluation by Practitioners"

It contains the high-quality figures of the four decision models and our study dataset. In the following, we briefly describe the folder and file.

**Decision Models**: This folder contains the high-quality figures of the four decision models, namely, the decision model for I) structural abstraction, ii) communications, iii) integration and optimization, and iv) data processing.

**Dataset**: This file contains the information about i) selected GitHub project, ii) selected stack exchange sites, iii) Selected GitHub Issue, iv) Selected Stack Exchange Posts, v) raw data of GitHub issues, vi) raw data of stack exchange posts, vii) pattern and strategy impact.


We proposed a set of decision models for selecting patterns and strategies in four areas of quantum software systems design: structural abstraction, communication, integration and optimization, and data processing. These decision models are proposed based on the knowledge collected from analyzing quantum software development discussions in GitHub issues and Stack Exchange posts. These models will help practitioners choose suitable patterns and strategies to address various design challenges in quantum software systems.


<p align="center">
    <img src="https://github.com/shamimaaktar1/ADDMQSA/assets/75358854/4cf274b1-0c26-4867-9475-c1eb5a3973a2" alt="chatGPT logo" width="250" height="400">
</p>

<h2 align="center">Decision Models for Selecting Patterns and Strategies in Quantum Systems and their Evaluation by Practitioners</h3>

<p align="left">
  This is the replication package for the paper: "Decision Models for Selecting Patterns and Strategies in Quantum Systems and their Evaluation by Practitioners", including the dataset, figures,  scripts, and so on (see the description below).
  <br>

  
## File Organization

1. `Case Study on Architecting the CampusBike Application.pdf` describes the case study on architecting the CampusBike application. It provides the business case and specifications, functional specifications, quality attributes, constraints, and tools and technologies (infrastructure, design, implementation, and testing) for the CampusBike application.

2. `Towards Human-Bot Collaborative Software Architecting with ChatGPT.pdf` describes the idea and an initial case study of introducing ChatGPT in human-bot collaborative architecting.

3. `Architectural Analysis.pdf` outlines and provides a brief description of the functional requirements, software development standards, and constraints for the CampusBike system.

4. `Architecture Evaluation.pdf` provides a set of scenarios for SAAM-based evaluation, including prioritized scenarios that are specifically tailored for the CampusBike application. It also includes a comprehensive set of quality attributes that can be used to evaluate the architecture of the CampusBike application.

5. `Architectural Synthesis.pdf` outlines the non-functional requirements related to maintaining a green campus and provides PlantUML scripts for components and class diagrams. It also includes implementation scripts for various design patterns, as well as graphical representations of these patterns.

6. `Dataset.xlsx` contains the information about i) selected GitHub projects, ii) selected Stack Exchange sites, iii) selected GitHub issues, iv) Selected Stack Exchange posts, v) raw data of GitHub issues, vi) raw data of stack exchange posts, vii) pattern and strategy impact.
7. `Decision Models` folder contains the high-quality figures of the four decision models, namely, the decision model for I) structural abstraction, ii) communications, iii) integration and optimization,


  
## Demo Video 

<p>
 In this video, we show how to use ChatGpt to architect software systems. Particularly, we developed the functional requirements, quality attributes, software standards, component diagrams, and class diagrams. In the class diagram, we also used various design patterns.
</p>
To watch the video, please click on the picture below:
<br>
<br>

 
<p align="center">
   <img src="https://github.com/shamimaaktar1/ADDMQSA/files/15135633/Research.Process.pdf" alt="Research Process"  width="500" height="600">
</p>


## Experiment Replication Steps

This research paper is divided into three main phases.

- [Phase 1: Research Design](#developing-the-architecture-story)
  - [Identifying Quantum Patterns and Strategies](#architectural-analysis)
  - [Modeling Decision Models](#architectural-synthesis)
  - [Evaluating Decision Models](#architectural-evaluation)
  
- [Phase 2: Decision Models](#enabling-collaborative-architecting)
  - [Decision Model for Structural Abstraction](#architectural-analysis)
  - [Decision Model for Communications](#architectural-synthesis)
  - [Decision Model for Integration and Optimization](#architectural-evaluation)
  - [Decision Model for Data Processing](#architectural-evaluation)
- [Phase 3: Evaluation of Decision Models](#conducting-the-empirical-validations)


### Phase 1: Research Design

<p>
These decision models were explicitly crafted for four critical areas of quantum software design:
structural abstraction, communication, integration and optimization, and data processing. These
areas were chosen because they are fundamental to addressing critical design,
implementation, integration, and data management challenges.
</p>
The research method is described below and represented in the picture below:
<br>
<br>

<p align="center">
   <img src="https://github.com/shamimaaktar1/ADDMQSA/files/15135633/Research.Process.pdf" alt="Research Process"  width="600" height="800">
</p>



#### Identifying Quantum Patterns and Strategies
#### Modeling Decision Models
#### Evaluating Decision Models


### Phase 2: Enabling Collaborative Architecting

<p>
 The three tasks of architectural analysis, synthesis, and evalution provide the basis for collaborative architecting. 
</p>
  
#### Architectural Analysis

<p>
 Architectural analysis is managed by the architecture story provided to ChatGPT for articulating the Architecturally Significant Requirements (ASRs) via automatically produced and proposed requirements (by ChatGPT), the manual definition of the requirements (by the architect), or a continual conversation between ChatGPT and the architect to revise (add, delete, or update) the requirements.
</p>

  
#### Architectural Synthesis

<p>
 The ASRs are combined in architectural synthesis to produce a model or representation of the architecture that may serve as a reference point and help to visualize the structural (de-)composition and runtime possibilities for the program. Due to a variety of reasons, the architectural model in this study was created using UML class and component diagrams.
</p>

#### Architectural Evaluation

<p>
 Using scenarios from the architectural story, architectural evaluation compares the synthesized architecture against ASRs. In order to oversee ChatGPT's  evaluation of the architecture, we applied the Software Architecture Analysis Method (SAAM).
</p>


### Phase 3: Conducting the Empirical Validations

<p>
  Empirical validations of collaborative architecting are conducted as a continuation of this study, completing the first two phases and proposing further research.
  
</p>









