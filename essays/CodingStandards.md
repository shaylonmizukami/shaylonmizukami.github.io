---
layout: essay
type: essay
title: "The Power of Coding Standards"
# All dates must be YYYY-MM-DD format!
date: 2025-02-13
published: true
labels:
  - Coding Standards
  - ESLint
  - VSCode
---

<img width="300px" class="rounded float-start pe-4" src="../img/CodingStandards.png">

Coding standards often get dismissed as trivial rules about indentation, brace placement, or variable naming conventions. However, I believe they serve a much more important purpose. If I had to choose only one software engineering practice to improve code quality, it would be coding standards, since they are not just about style but they influence maintainability, collaboration, and even how we learn a programming language.

<br>

## Coding Standards as a Learning Tool

When learning a new language, sticking to established coding standards can accelerate comprehension. ESLint, for instance, enforces best practices in JavaScript and TypeScript, which makes it easier to recognize patterns, avoid common pitfalls, and write more efficient and cleaner code. It also prevents bad habits from forming early on, making sure that code remains readable and functional even as projects grow in complexity. For example, ESLint flags unused variables and improper scoping, reinforcing JavaScript's lexical scoping rules. Without these enforced standards, a beginner like me might repeatedly make subtle mistakes that lead to bugs and inefficiencies. Therefore, coding standards guide developers toward writing better code.

## My Experience with ESLint

After my first week using ESLint in VSCode, I have mixed feelings. At first, I had an overwhelming number of errors and warnings pop up, sometimes for things that seemed insignificant. However, currently I am beginning to appreciate the discipline it enforces. The process of eliminating ESLint errors made me rethink how I structure my code. It forces me to consistently use *const* and *let* instead of *var*, improving my understanding of JavaScript's block scoping. It also highlighted areas where I was writing redundannt code. While it can feel tedious, the benefits outweigh the initial pain.

## Maintainability and Collaboration

Coding standards are important for team-based development. A well-structured codebase minimizes the cognitive load required to understand a project and reduces the onboarding time for new developers. Imagine working on a large open-source project where every contributor follows different formatting rules. This would be a nightmare to read and debug the code. Standards such as those enforced by ESLint ensure that the code remains consistent, regardless of who wrote it. This consistency is particularly important in long-term projects where different engineers contribute over time. It also reduces friction in code reviews, allowing reviewers to focus on logic and functionality rather than style issues. However, while I appreciate the importance of coding standards, I also think that excessive rigidity can suppress creativity as not every rule enforced by ESLint feels necessary in every context.

## Conclusion

My experience with coding standards through ESLint in VSCode has been both challenging and informative. While it was frustrating initially, these standards are a valuable tool for learning and improving maintainability and collaboration. Rather than viewing them as just syntactic constraints, we should accept coding standards as a fundamental practice that improves software quality at every level. In the long run, good coding standards lead to better developers, cleaner code, and more efficient teamwork, which makes them an indispensable part of software engineering.

<br><br>

The essay above used ChatGPT for spelling and grammar correction/suggestions.
