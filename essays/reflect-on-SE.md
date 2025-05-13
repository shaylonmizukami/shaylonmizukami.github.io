---
layout: essay
type: essay
title: "Beyond Web Apps: Core Software Engineering Principles"
# All dates must be YYYY-MM-DD format!
date: 2025-05-14
published: true
labels:
  - Reflection
  - Software Engineering
---

<img width="300px" class="rounded float-start pe-4" src="../img/reflect-on-SE.png">

Software engineering is much more than learning the ins and outs of a particular web framework or language. While this course’s technology stack focused on building web applications, its deeper purpose was to immerse us in timeless and broadly applicable practices that underpin successful software projects of any kind. In this reflection, I will explore Configuration Management, Agile Project Management (specifically Issue-Driven Project Management), and Design Patterns—defining each term and illustrating how I can apply these concepts beyond web development.

## Configuration Management

At its heart, configuration management (CM) is the discipline of systematically organizing and controlling all the artifacts of a software project—source code, documentation, build scripts, deployment settings, and more. In practice, we used Git and GitHub to track every change, tag releases, and manage branches. But CM is equally critical in contexts as varied as:

  - **Embedded Systems:** When firmware and hardware configurations must stay in sync, CM ensures that the exact version of code running on a microcontroller corresponds to specific schematic revisions.
  - **Data Science Pipelines:** Versioning not only your analysis code but also datasets and environment specifications (e.g., Dockerfiles or Conda environments) ensures that experiments are reproducible months or years later.
  
By learning to write clear commit messages, employ branching strategies (feature branches, release branches), and tag stable versions, I’ve acquired a mindset of rigorous traceability. In any future project—be it a mobile app, a machine-learning model, or an Internet-of-Things deployment—I can leverage the same CM principles to guarantee that colleagues and I always know exactly what is running where and why.

## Agile Project Management and Issue-Driven Workflows

Agile Project Management is an umbrella term for flexible, iterative approaches to organizing work. One style we practiced is Issue-Driven Project Management, where the central artifacts aren’t Gantt charts or massive requirement documents but rather a prioritized backlog of small, self-contained “issues” or “tickets.” Each issue describes a narrow slice of functionality or a bug to fix, complete with acceptance criteria.

  - **What Agile Means:** Unlike traditional “waterfall” plans that lock in requirements up front, Agile welcomes change. It emphasizes delivering incremental value in short cycles (sprints) and regularly reassessing priorities based on feedback.
  - **Issue-Driven Workflow:** Every piece of work—no matter how small—is represented by an issue in a tracking system (GitHub Issues, Jira, etc.). Teams pull issues, collaborate via comments, and close them only once automated tests pass and the feature meets its definition of done.

This approach is not limited to web apps. For example, in a robotics project, issues might represent “Implement PID control for the arm,” “Test sensor fusion algorithm,” or “Write deployment script for edge device.” By treating each task as a discrete issue, we maintain transparency, facilitate asynchronous collaboration, and adapt quickly when requirements evolve—whether the end goal is a website, a hardware prototype, or a desktop application.

## Design Patterns

Design patterns are proven, reusable solutions to common design challenges in software. They capture best practices at the level of object collaborations and code structure. In our web application work we encountered patterns such as:

  - Model–View–Controller (MVC), which cleanly separates data (Model), user interface (View), and control flow (Controller).
  - Factory and Singleton, which manage object creation and enforce controlled access to shared resources.

Design patterns shine beyond web frameworks. For instance:
  - In desktop GUI applications, MVC (or its variants like MVP/MVVM) ensures that UI code remains decoupled from business logic, making it easier to test and maintain.
  - In distributed systems, the Observer pattern underlies publish–subscribe messaging, where services subscribe to events emitted by other components.
  - In game development, the State pattern helps manage an entity’s different behaviors (idle, walking, attacking) without massive conditional logic.

By internalizing these patterns, I’m now equipped to recognize common structural problems and apply well-tested solutions rather than inventing ad-hoc approaches. This not only accelerates development but also makes codebases easier for new team members to understand.

## Conclusion

Through this course, I gained hands-on experience with fundamental software engineering practices that transcend the specifics of any one technology. Configuration management taught me discipline in versioning and release control; Agile Issue-Driven workflows showed how to organize and adapt work around small, clear tasks; and design patterns provided a shared vocabulary for solving structural challenges in code. Whether I’m building a mobile app, integrating sensor networks, or architecting a micro-services backend, these principles will guide me toward creating robust, maintainable, and adaptable software.

<br><br>

The essay above used ChatGPT for spelling and grammar correction/suggestions.
