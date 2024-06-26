# E̶r̸r̴o̵r̵ ̶4̸0̷4̸ - Azul Connect

![Error 404 Logo.jpg](https://github.com/IntrixTheName/Error404/blob/c17b5343e40100331db39d85264d0561f0285e1e/Error%20404%20Logo.jpg)

Project group "Error 404" for the 2024 EagleHacks Hackathon event.

[![OpenSSF Scorecard](https://api.securityscorecards.dev/projects/github.com/IntrixTheName/Error404/badge?style=flat)](htt‌ps://securityscorecards.dev/viewer/?uri=github.com/IntrixTheName/Error404)
![Static Badge](https://img.shields.io/badge/language-HTML-blue)
![Static Badge](https://img.shields.io/badge/license-MIT-crimson)



## Project Vision & Overview

The vision of this project is to unite those with ideas to those who can help. Many ideas go unrealized because it's unreasonable to expect a person to have *every*. *single* *piece*. of information they need to follow through with a project idea (side note from Brad- I have personal anecdotes of projects sitting half-complete in GitHub repositories because I hit a brick wall of knowledge at the time).

Introducing Azul Connect, a Chrome-based extension that allows users within a community to post about their project ideas and gather a team outside the normal bounds of classmates, friends, etc. It's the hope of this extension that more project ideas can get passed around, which can lead to more creative projects and a greater opportunity for improvement, both for the end users of potentially innovative projects, and learning opportunities for the users in the community who can learn through applied experience on these projects.

## Current Prototype

The current prototype is limited in functionality due to the limited timescale of the proposal design sprint. Currently, it has a proof-of-concept with hard-coded examples of what posts might look like, along with a general approach to styling. A PowerPoint consisting of a brief overview and link to Figma mockup are included in the repository.

## Future Development & Intended Progression

The grander plan for Azul Connect consists of making a fully-functional extension that could reach out to a database locally-maintained by each individual community, where these projects could be loaded live to the extension through added JavaScript functionality. Additionally, clicking on any of the line items could open a new tab containing extended information about the project like additional context, reports on current progress, links to project resources, and potentially a limited message board to engage with prospective project players.

Firstly, for the database solution: Using a document-style database like MongoDB would well-suited for this project. It would be easy to store each post like a document and keep a log of conversation associated with the project. The structure would be easier to retrieve data from compared to a SQL solution.

Secondly, the ability to open extended details of a project can keep the initial user interface simple to use. If a user wants to learn more, it is also helpful to make the additional information knowm. All about simplicity!
