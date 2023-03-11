<p align="center">
  <a href="https://www.youtube.com/embed/oYeH4Sgh_YU">
    <img src="https://user-images.githubusercontent.com/75358854/222472343-5e21f0fc-b41a-431a-87c2-56ee7349c84d.png" alt="chatGPT logo" width="200" height="200">
  </a>
</p>

<h2 align="center">Architecting Software-intensive Systems with ChatGPT</h3>

<p align="left">
  This is the replication package for the paper: "Towards Human-Bot Collaborative Software Architecting with ChatGPT", including the data, case study,  scripts and so on (see the description below).
  <br>

  
## File Organization

1. `Case Study on Architecting the CampusBike Application.pdf` describes the case study on architecting the CampusBike application. It provides the business case and specifications, functional specifications, quality attributes, constraints, and tools and technologies (infrastructure, design, implementation, and testing) for the CampusBike application.

2. `Towards Human-Bot Collaborative Software Architecting with ChatGPT.pdf` decribes the idea and an initial case study of introducing ChatGPT in human-bot collaborative architecting.


3. `Architectural Analysis.pdf` Functional Requirements, Software Development Standards, and Constraints by considering the following case study.

## Demo Video 

<p>
 In this video, we show how to use ChatGpt to architect software systems. Particularly, we developed the functional requirements, quality attributes, software standards, component diagrams, and class diagrams. In the class diagram, we also used various design patterns.
</p>
To watch the video, please click on the picture below:
<br>
<br>

 
<p align="center">
    <a href="https://www.youtube.com/embed/oYeH4Sgh_YU">
   <img src="https://user-images.githubusercontent.com/75358854/222391866-9b18c78f-5db8-4b8e-b450-0ba631ed240e.png" alt="Architecting with ChatGPT" width="500" height="600">
    </a>
</p>


## Experiment Replication Steps

This research paper is divided into three main phases.

- [Phase 1: Developing the Architecture Story](#developing-the-architecture-story)
- [Phase 2: Enabling Collaborative Architecting](#enabling-collaborative-architecting)
  - [Architectural Analysis](#architectural-analysis)
  - [Architectural Synthesis](#architectural-synthesis)
  - [Architectural Evaluation](#architectural-evaluation)
- [Phase 3: Conducting the Empirical Validations](#conducting-the-empirical-validations)


### Phase 1: Developing the Architecture Story

<p>
 This phase describes the software architecture story, which is generated based on an analysis of the software domain and depicts the operational context of the system or group of operationalized scenarios using a software solution. A prompt is used to provide the architectural story into ChatGPT as a prerequisite for collaborative architecture.
</p>


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






