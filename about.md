---
layout: home
title: 'EGN 4060C: Introduction to Robotics'
nav_exclude: true
permalink: /:path/
seo:
  type: Course
  name: 'EGN 4060C: Introduction to Robotics'
---

# EGN 4060C: Introduction to Robotics

**Term:** Fall 2026  
**Credit Hours:** 3.00

|  | Time | Location |
|---|---|---|
| **Lectures** | 3:00 PM–4:20 PM, Monday and Wednesday | HS1 116 |
| **Labs** | 5:00 PM–7:50 PM, Monday, Wednesday, Thursday, or Friday, depending on the assigned lab section | CMMS 102B |

## Course Description

Introduction to Robotics is a broad survey course that provides an overview of the theory and applications of intelligent robotics, including robot system architecture, perception, planning algorithms, robot learning, and human-robot interaction.

The course is designed to familiarize students with how artificial intelligence (AI) has influenced robotics by enabling autonomous capabilities that allow robots to interact with their environments and with other agents, including robots and humans. The primary goal of the course is for students to understand which algorithms and techniques are appropriate for a given robotic application and why.

The course also includes a laboratory component that provides hands-on experience with real robotic systems. By the end of the course, students will work in teams to prototype a solution to a robotics problem of their choice by applying the knowledge and techniques introduced throughout the course.

The course content is organized into four parts:
- **Part 1: Foundations of Intelligent Robotics**  
  Introduces a framework for understanding AI in robotics and how intelligent robotic systems have evolved.
- **Part 2: Perception and Action**  
  Focuses on how robots perceive their environments and generate actions in response to sensory information.
- **Part 3: Planning and Autonomy**  
  Covers deliberative functions associated with intelligence, including planning, decision-making, and autonomous behavior.
- **Part 4: Robots and Other Agents**  
  Introduces concepts required for robots to interact and collaborate with other agents, including humans and other robots.

## Course Materials and Resources

**Required:** 
- Robin R. Murphy, *Introduction to AI Robotics* (Second Edition).

**Recommended:**
- Gregory Dudek and Michael Jenkin, *Computational Principles of Mobile Robotics*.
- Steven M. LaValle, *Planning Algorithms*.
- Sebastian Thrun, Wolfram Burgard, and Dieter Fox, *Probabilistic Robotics*.


## Prerequisites

Students must earn a minimum grade of C in one of:
- COP 3223C (Introduction to Programming with C)
-  EGN 3211 (Engineering Analysis and Computation)

and, one of：
 - COP 3503C (Computer Science II)
 - EEL 4742C (Embedded Systems)
 - EEL 3657 (Linear Control Systems)
 - EGN 3321 (Engineering Analysis – Dynamics).


## Course Staff

### Instructor

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}
### Teaching Assistants

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}
