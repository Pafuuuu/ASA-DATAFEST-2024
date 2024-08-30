# ASA-DATAFEST-2024

This repository contains the presentation and analysis for our award-winning project at the 2024 UCLA ASA DATAFEST. The data was provided by Course Kata, a platform that creates and publishes e-books for introductory statistics and data science students. Our goal was to discover students’ learning patterns and propose constructive solutions to enhance the learning experience.

## Project Overview

Our analysis focused on understanding students' learning behaviors and patterns while interacting with Course Kata's e-books. We aimed to identify challenges in the learning process and propose actionable solutions to facilitate a better user experience and improved learning outcomes.

## Student Learning Roadmap

We performed a time series analysis on user engagement time, accuracy scores, and browsing data across different books and chapters. Key insights include:

- **Increasing Difficulty**: Users' correct response rates progressively dropped in later chapters, despite a decrease in chapter length and content.
- **Shift in Focus**: Users' primary focus shifted from coding exercises in early chapters to theory and concepts in later chapters, as indicated by engagement time and attempted trials.
- **Extensive Coding Learning Time**: User engagement time highly correlated with the amount of coding content in each chapter.
- **Poor Coding Outcomes**: Coding exercises showed a pattern of extremely high numbers of attempts and low pass rates, indicating that students struggled to fully grasp the coding concepts.

## User Footage Tracking

By defining an active period (10 minutes), we tracked users' browsing history and visualized connections between chapters when users jumped from one chapter to another within that period. We identified chapters and content that were most frequently connected and defined them as closely related topics.

## Solutions

Based on our findings, we proposed the following solutions:

- **Content and Exercise Adjustments**:
  - Add extra resources, practice, and explanations in later chapters to help users better comprehend complex material.
  - Focus on coding sections in the first half of the chapters and theory/concept sections in the later chapters.

- **Coding Section Modifications**:
  - Implement hints and feedback for coding problems, and integrate AI/LLM models to provide customized debugging suggestions and guidance.

- **User Feedback Collection**:
  - Introduce end-of-chapter self-evaluations as well as pre-chapter evaluations to track users' learning improvements.
  - Randomly add feedback sections after each section/exercise to collect satisfaction data on content design.

- **Connecting Related Knowledge & Content**:
  - Add hyperlinks and review sections to connect highly related chapters and content, making it easier for users to browse back-and-forth to review and reinforce their understanding.

## Conclusion

This project identified critical areas for improvement in the learning experience provided by Course Kata's e-books. As a result, our team was honored the award for Best User Experience.  

---

Explore this repository to see the full analysis, and presentation that led to these findings and recommendations.
