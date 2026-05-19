# OTML Practical 9: Directed Graphical Models

## 1. Aim

The aim of this practical is to understand Directed Graphical Models and represent dependencies among machine learning variables using a directed graph.

In this practical, students create a simple directed graphical model for a Music Genre Recommendation example, where variables such as Age and Gender influence the predicted Music Genre.

---

## 2. Course and Module Mapping

**Course:** A8751 – Optimization Techniques in Machine Learning  
**Module:** Module 1 – Model Fitting and Error Measurement  
**Practical Topic:** Directed Graphical Models

This practical is mapped with Module 1 of OTML, where students study model representation, probabilistic modelling, inference, and dependency structures used in machine learning.

---

## 3. Theory Background

A Directed Graphical Model is a graph-based representation of relationships among variables.

It contains:

| Component | Meaning |
|---|---|
| Node | Represents a variable |
| Directed edge | Represents direction of dependency |
| Parent variable | Variable that influences another variable |
| Child variable | Variable influenced by a parent variable |

A directed edge is written as:

```text
A → B
