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
   <img src="[https://github.com/shamimaaktar1/ADDMQSA/files/15135633/Research.Process.pdf](https://github.com/shamimaaktar1/ADDMQSA/assets/75358854/bc868529-2ec2-43c0-9a41-362010e9aa7c)" alt="Research Process"  width="700" height="600">
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
These decision models were explicitly crafted for four critical areas of quantum software design: structural abstraction, communication, integration and optimization, and data processing. These areas were chosen because they are fundamental to addressing critical design, implementation, integration, and data management challenges.
</p>
The research method is described below and represented in the picture below:
<br>
<br>

<p align="center">
   <img src="https://github.com/shamimaaktar1/ADDMQSA/assets/75358854/bc868529-2ec2-43c0-9a41-362010e9aa7c" alt="Research Process"  width="650" height="600">
</p>



#### Identifying Quantum Patterns and Strategies

<p>
The required patterns, strategies, quality attributes, and impact of patterns on quality attributes for creating decision models are collected data from the two sources (e.g., GitHub1 and
Stack Exchange sites2) inspired by the guidelines for selecting empirical methods for software engineering research. The following are used to extract the relevant issues and posts from both
GitHub and Stack Exchange sites.
</p>


#### Modeling Decision Models

<p>
The decision flow is represented using the Inclusive, Exclusive, and Parallel gateways from the Business Process Model and Notation (BPMN). Each area of quantum software architecture design is depicted using a grey box. A circle marks the commencement of a decision process. Inclusive gateways initiate multiple outgoing paths in a decision process, while Exclusive gateways activate a single outgoing path. Conversely, Parallel gateways facilitate several concurrent outgoing paths in the decision process. Rounded rectangles denote the patterns and strategies associated with a quantum software architecture design area. A bidirectional arrow indicates a “complements” relationship between two patterns or strategies. An octagon and a dashed arrow symbolize constraints for each pattern or strategy. The positive and negative influences of each pattern or strategy on the quality attributes are signified by plus (+) and minus (-) signs, respectively. 
</p>
<br>
<br>

<p align="center">
   <img src="https://github.com/shamimaaktar1/ADDMQSA/assets/75358854/8c52844e-dc48-46e9-af0b-c31c0d36e40f" alt="Model and Notation (BPMN)"  width="500" height="300">
</p>


#### Evaluating Decision Models

In our study, we conducted a survey of quantum software practitioners and aimed to refine and evaluate our decision models. We conducted a descriptive survey following the guidelines proposed by Kitchenham and Pfleeger. Our survey questionnaire was conducted using Google Forms.


### Phase 2: Decision Models

<p>
 The three tasks of architectural analysis, synthesis, and evalution provide the basis for collaborative architecting. 
</p>
  
#### Decision Model for Structural Abstraction

<p>
The decision model for structural abstraction in quantum software system design is a comprehensive framework that guides practitioners in selecting the most appropriate architecture pattern
based on the impact for structural abstraction. Each pattern within the model serves a specific purpose and is evaluated based on its positive and negative impacts on these attributes.
</p>

  
#### Decision Model for Communications

<p>
The decision model for quantum communication aids practitioners in choosing the right communication pattern for quantum software systems by evaluating the impact of quality attributes. This model is vital for enhancing the interaction between quantum components to ensure eﬀiciency, reliability, and scalability. 
</p>

#### Decision Model for Integration and Optimization

<p>
The decision model for quantum integration and optimization aims to streamline the development and enhancement of quantum software systems by guiding the selection of appropriate architectural patterns based on the impact of quality attributes. This model helps practitioners integrate various programming techniques and optimize quantum operations, considering eﬀiciency, extensibility, and testability
</p>

#### Decision Model for Data Processing

<p>
The decision model for quantum data processing is crafted to simplify the handling, processing, and testing of quantum data within quantum software systems. It emphasizes Performance, Compatibility, Extensibility, and Flexibility in quantum computations.
</p>


### Phase 3: Evaluation of Decision Models

<p>
  To evaluate the decision models, we conducted a survey of the response 24 practitioners.
</p>









