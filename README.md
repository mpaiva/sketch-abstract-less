# Hey there! Read me first

This project is a collection of best-practices having architect, designed and built a number of projects using the Sketch+Abstract combination using LESS as single source of truth (SSOT).

## Why use abstract

It all comes down to one thing... the size of your team. The more people involved the higher the governance needed. That goes from naming convention for layers, artboards, files, branches, projects, teams to the way your team communicates progress, architect files and become more efficient.

## About this Architecture

It's only natural to find better ways of working while experiencing repetitive challenges. After having implemented a number of projects in Abstract you'll start thinking of ways your and your team can become more efficient.

The excitement of using a new tool is our worst enemy. Without the proper training and planning, teams tend to hit bottlenecks and deviate to find multiple ways to solve unforeseen challenges, such as:

- **Branching** - Not fully understanding branching strategies from teh beginning may cause bad habits inherited from the days of collaborating in shared folders.
- **Redundancies** - Speaking of bad habits, the love for _copying and pasting_ leads to high maintenance and laborious change requests.
- **Hand-offs** - Sending links to developers has its consequences, especially if you continue to change your files without having a good communication channel with your development team members.
- **Naming Conventions** - Why is it so hard to find things when you work within a team setting? Not knowing how people name things can be frustrating when trying to collaborate and leverage other people's libraries, styles and component symbols.
- **Maintaining Libraries** - From frequent Sketch releases to plugin dependencies or poorly made decisions in the beginning of the project, can - and will create a huge burden to revisit and refactor styles and component symbols.
- **External Teams** - And then, there are the external teams consuming your Sketch libraries to create features... How do we educate, communicate and collaborate with designers detaching your component symbols and creating more debt and inefficiencies?

There's more, but these were enough to motivate the creation of this project.

## Project Objective

With the understanding of modern web development architectures, our objective is to provide a comprehensive separation of concerns among the design tokens, themes, styles, and components.

## Definitions

Before architecting a new visual language for an enterprise-level Design System, it is important to define a few terms we will be using in the project:

### Organization in Abstract

Your Organization is your team’s home for all design work. Designers and stakeholders collaborate on Projects inside of Organizations.

### Projects in Abstract

Projects are spaces each organization can create to organize their work and initiatives. These are repositories containing files holding styles, component symbols and interface designs.

Projects can be linked to other projects in the same organization.

### Separation of Concerns (SoC)

In computer science, separation of concerns (SoC) is a design principle for separating a computer program into distinct sections such that each section addresses a separate concern. A concern is a set of information that affects the code of a computer program.

### Single Source of Truth (SSOT)

In information systems design and theory, single source of truth (SSOT) is the practice of structuring information models and associated data schema such that every data element is mastered (or edited) in only one place.

### Tokens

Gives access to visual language's styles management

## Dependencies

### Sketch Plugins

- PuzzleTokens
- RenameIt

### NodeJS and NPM Modules

1. Download and install [Node.js](https://nodejs.org/en/download/)
2. Install less or sass using the following Terminal commands:

```
sudo -s  
npm i less -g 
npm i sass -g 
```

### Code Editor

For editing the token source of truth
