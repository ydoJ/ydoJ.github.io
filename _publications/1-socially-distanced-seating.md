---
title: "🥇An Automated Tool for Optimal Classroom Seating Assignment with Social Distancing Constraints"
collection: publications
permalink: /research/socially-distanced-seating
excerpt: "To depart from time-consuming guesswork, I designed the original tool for automatically selecting the optimal seating arrangement given social distancing guidelines that employed computer vision and integer programming. Working closely with a team of undergraduates, we improved and implemented the system for the university's use in reopening. This project was submitted to the 2021 IISE Annual Conference where it received first place for the OR Division Undergraduate Student Research Award."
subtitle: 'Advised by Professor David Shmoys and Professor Samuel Gutekunst'
location: 'Cornell University'
year: '2020-2021'
---
### Abstract
Social distancing has become a necessity due to COVID-19, requiring schools to reduce classroom capacities to host in-person students. In doing so, schools seek to maximize the number of seats that can be used within a classroom, while ensuring that no pair of usable seats violates social distancing guidelines. We model this problem as a graph-theoretic maximum independent set problem and develop a user-friendly tool that solves real instances of the problem. We then use that tool to create optimal classroom seating plans for a major university.
 
Our core model considers the case of a classroom with fixed seats. This problem can be expressed as a graph, identifying seats as vertices and inserting edges between seats that are closer than some prescribed threshold. A maximum independent set in this graph corresponds to an optimal seating plan. Our seat assignment tool allows any user to solve this problem by uploading an architect’s drawing of a classroom. Then, computer vision aids the user by locating seats, and the tool finds and prints an optimal plan. Our tool also allows users to easily incorporate additional requirements, such as designated teacher spaces and the inclusion of movable chairs.
 
Our tool helped automate the classroom planning process at a major university where its ease of use allowed it to be run on hundreds of classrooms. Compared to initial reduced-capacity classroom estimates determined by the Office of the University Architect, it helped identify over 400 additional seats that could be used by the university.

K. K. Greenberg, T. Hensel, Q. Zhu, S. Aarts, D. B. Shmoys, and S. C. Gutekunst. [“An Automated Tool for Optimal Classroom Seating Assignment with Social Distancing Constraints.”](http://academicpages.github.io/files/socially-distanced-seating.pdf) Proceedings of the IISE Annual Conference, 2021.

Watch my oral presentation [here](https://drive.google.com/file/d/1Tp5pRFD6_uClzTgvqYZlorcRtC_NAnPt/view?usp=sharing).