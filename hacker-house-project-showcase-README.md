# Selected Projects --- Manas Aggarwal

> **AI • Intelligent Systems • Robotics • Software Engineering**
>
> A curated overview of selected systems I have designed and developed
> across AI, intelligent software, robotics, and applied engineering.

------------------------------------------------------------------------

## About This Repository

This repository is a **public, non-sensitive project showcase** created
to provide a high-level view of my technical work.

The projects presented here are active or ongoing work in different
stages of research, experimentation, and product development. The
descriptions intentionally focus on **problems, engineering direction,
capabilities, and my role** rather than exposing proprietary
implementation details.

> **Note:** Source code, internal architectures, research methodology,
> private datasets, unpublished experimental results, and other
> sensitive implementation details are not included because some of
> these projects are associated with ongoing research and/or product
> development.

------------------------------------------------------------------------

# 01 --- Intelligent Security & Control System

### An AI-driven architecture for intelligent monitoring, anomaly awareness, and decision support

One of my major systems projects explores how multiple intelligent
components can work together as a coordinated security and control
layer.

Instead of treating detection, analysis, and response as isolated
functions, the system is designed around a pipeline in which different
computational components contribute to understanding system state,
identifying unusual behaviour, assessing potential threats, and
supporting downstream decisions.

### Core Areas

-   AI-assisted decision making
-   Anomaly detection
-   Threat analysis
-   Intelligent orchestration
-   Agent-oriented system design
-   Backend API architecture
-   System monitoring
-   Risk-aware decision support

### Engineering Direction

The project explores a modular architecture in which specialized
components can perform different responsibilities while communicating
through a central orchestration layer.

A simplified conceptual flow is:

``` text
┌──────────────────────┐
│     System Inputs    │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│   Observation Layer  │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│ Anomaly / Threat     │
│      Analysis        │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│ Decision Intelligence│
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│ Orchestration Layer  │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│ Response / Control   │
└──────────────────────┘
```

### Technology Areas

**Python • FastAPI • AI/ML • Anomaly Detection • Agent Systems • Backend
Engineering**

### What I Worked On

My work has involved thinking through the system architecture, designing
the interaction between intelligent components, implementing backend
services, experimenting with anomaly-detection approaches, and
developing the logic required to move from raw observations toward
actionable system decisions.

### Current Status

**Research / active development**

The project is also part of ongoing research, so detailed implementation
and experimental information is intentionally private.

------------------------------------------------------------------------

# 02 --- Robotics Learning & Evaluation Platform

### A structured software platform for robotics learning, assessment, and progression

This project explores how robotics education can move beyond isolated
tutorials and practical sessions toward a structured, measurable
learning environment.

The platform is designed around progressive robotics challenges in which
learners can work through increasingly difficult tasks while instructors
or authorized evaluators maintain oversight of progression and
assessment.

### Core Areas

-   Robotics education
-   Challenge-based learning
-   Progressive skill development
-   Role-based access
-   Faculty/instructor verification
-   Automated scoring workflows
-   Interactive learning interfaces
-   Full-stack application architecture

### Conceptual Experience

``` text
        STUDENT
           │
           ▼
┌──────────────────────┐
│ Robotics Roadmap     │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│ Challenge / Task     │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│ Submission / Result  │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│ Evaluation & Score   │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│ Verification / Unlock│
└──────────────────────┘
```

### Platform Architecture

The system has been developed around a modern web architecture with a
responsive frontend, backend APIs, database persistence,
authentication/authorization concepts, and structured evaluation
workflows.

### Technology Areas

**Next.js • TypeScript • Tailwind CSS • FastAPI • Python • PostgreSQL •
REST APIs**

### What I Worked On

I have worked across the platform stack, including system architecture,
frontend workflows, backend APIs, role-based functionality, database
design, scoring logic, progression mechanics, and the integration of
robotics-focused learning workflows.

### Why It Matters

The broader goal is to create a more structured bridge between:

**Learning → Practice → Evaluation → Verification → Progression**

rather than treating robotics learning as a collection of disconnected
exercises.

### Current Status

**Active product development**

The implementation is intentionally private because this system is being
developed as a product.

------------------------------------------------------------------------

# 03 --- AI Thought Distillation System

### An experimental AI system exploring how complex human inputs can be compressed into meaningful representations

This project investigates a different question:

> **Can an AI system take a complex thought and identify the smaller set
> of ideas that actually defines it?**

The system experiments with converting free-form human input into
concise representations while adapting the level of computational
reasoning to the complexity of the input.

Rather than simply generating longer responses, the project focuses on
**distillation, abstraction, and representation**.

### Core Areas

-   Large language models
-   Adaptive model routing
-   Natural-language processing
-   Thought representation
-   Semantic distillation
-   Human-AI interaction
-   AI product experimentation

### Conceptual Pipeline

``` text
┌──────────────────────────┐
│     Human Input          │
└────────────┬─────────────┘
             │
             ▼
┌──────────────────────────┐
│ Complexity Assessment    │
└────────────┬─────────────┘
             │
       ┌─────┴─────┐
       │           │
       ▼           ▼
  Lightweight   Deeper
   Processing   Reasoning
       │           │
       └─────┬─────┘
             │
             ▼
┌──────────────────────────┐
│ Semantic Distillation    │
└────────────┬─────────────┘
             │
             ▼
┌──────────────────────────┐
│ Core Representation      │
└──────────────────────────┘
```

### Technology Areas

**Python • LLM APIs • Model Routing • NLP • Streamlit • Prompt/System
Design**

### What I Worked On

I designed and experimented with the application's processing pipeline,
adaptive model-selection logic, AI interaction flow, user interface, and
evaluation of different input complexities.

The project also involved exploring how different reasoning depths
affect the quality and usefulness of distilled representations.

### Research Direction

The system is being developed alongside an ongoing research direction,
so the detailed methodology, experiments, and findings are intentionally
not disclosed in this public showcase.

### Current Status

**Research / experimentation**

------------------------------------------------------------------------

# Technical Themes Across My Work

Although these projects address different problems, several engineering
themes connect them:

  -----------------------------------------------------------------------
  Area                                Experience
  ----------------------------------- -----------------------------------
  Artificial Intelligence             LLMs, intelligent decision systems,
                                      adaptive processing

  Machine Learning                    Anomaly detection, model
                                      experimentation

  Backend Engineering                 Python, FastAPI, REST APIs

  Full-Stack Development              Next.js, TypeScript, responsive
                                      interfaces

  Robotics                            Robotics platforms, learning
                                      workflows, automation

  Databases                           PostgreSQL and structured data
                                      systems

  System Design                       Modular architectures and
                                      orchestration

  Human-AI Interaction                AI interfaces and intelligent
                                      workflows

  Rapid Prototyping                   Turning concepts into functional
                                      systems
  -----------------------------------------------------------------------

------------------------------------------------------------------------

# My Engineering Approach

I generally approach projects through five stages:

``` text
Problem
   ↓
Understand the system
   ↓
Design the architecture
   ↓
Build a working prototype
   ↓
Experiment → Iterate → Improve
```

I particularly enjoy projects where the solution is not obvious at the
beginning and requires combining multiple disciplines.

My interests sit around the intersection of:

**AI + Software + Robotics + Intelligent Systems + Real-World Problems**

------------------------------------------------------------------------

# What I Bring to a Team

### Technical

-   Python and AI/ML development
-   Backend and API development
-   Full-stack application development
-   System architecture
-   Robotics and automation
-   Rapid prototyping
-   Debugging and iterative development

### Problem Solving

I enjoy taking an ambiguous problem, decomposing it into smaller
engineering problems, identifying the core technical challenge, and
building a prototype that can be tested quickly.

### Teamwork

I have experience working in technical teams as well as coordinating
innovation and project-oriented activities. I enjoy contributing both as
an engineer and as someone who can help turn an early idea into a
concrete execution plan.

------------------------------------------------------------------------

# Project Disclosure

This repository is intentionally a **high-level showcase**.

Some projects represented here are:

-   under active research,
-   associated with unpublished work,
-   under product development,
-   or contain proprietary implementation details.

Therefore, this repository does **not** contain:

-   Proprietary source code
-   Private repositories
-   API keys or credentials
-   Private datasets
-   Unpublished research results
-   Detailed research methodology
-   Sensitive algorithms
-   Internal business logic
-   Production infrastructure

The purpose of this repository is to demonstrate the **nature and
breadth of my engineering work**, not to disclose the complete
implementations.

------------------------------------------------------------------------

# Contact

**Manas Aggarwal**

Computer Science Engineering --- AI/ML

Interested in:

**Artificial Intelligence • Robotics • Intelligent Systems • Software
Engineering • Research • Innovation**

------------------------------------------------------------------------

> **Build the system. Understand the problem. Test the idea. Iterate.**
