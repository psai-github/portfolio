---
layout: post
title: "AP CSP Retrospective: From Setup to Collaboration and MCQ Reflection"
description: "Reflecting on tool setup, teaching Sass inputs, PVO ideation, collaboration, AI, the development life cycle, and College Board MCQ results."
permalink: /csp-retrospective-2026/
courses: { csp: {week: 7} }
---

# AP CSP Retrospective — October 2026

## My progress so far

At the beginning of this stretch of AP Computer Science Principles, much of my attention was on getting the development environment working and learning how to navigate a portfolio-based workflow. Setting up tools and working with repositories made me appreciate how much development depends on the surrounding infrastructure, not just writing code. GitHub, local development, organizing files, and publishing work are all parts of communicating a project's progress. Instead of viewing setup as an obstacle before the “real” programming, I now see reproducible setup and organization as essential engineering skills.

Another meaningful experience was teaching a lesson about **Sass inputs**. Preparing to teach pushed me beyond simply recognizing a concept: I had to consider how a learner would understand it, how to break the idea into manageable pieces, and how examples could make it concrete. Explaining technical material is also a test of my own understanding. A next step is to include more small hands-on exercises and to check for misunderstandings rather than assuming an explanation landed.

Our **PVO ideation** work helped me see development before implementation. An idea becomes more useful when we clarify the problem, the intended user, what the first viable version should accomplish, and how to decide which features matter. I am learning to resist jumping into coding before thinking through the requirements and tradeoffs. This also connects to iteration: a first proposal is a starting hypothesis, not a final product.

My portfolio includes homework notebooks on **variables, strings, lists, data abstraction, conditionals, Boolean expressions, iterations, procedures, libraries, randomness, algorithmic efficiency, and Sass components**. Working across these topics has helped me make connections between concepts that might otherwise appear separate. For example, inputs collect information, conditionals decide how a program responds, and procedures and abstractions help keep the result manageable.

## How I am growing as a collaborator

Collaboration is more than splitting a workload. It requires communicating decisions, listening to other interpretations, documenting progress, and making code and explanations understandable to someone else. Teaching a lesson made that especially clear: even when I understand something, the way I communicate it determines whether it helps the group. During project ideation, I have been practicing evaluating suggestions against user needs rather than relying only on personal preferences.

I want to improve further by asking more targeted questions, clarifying ownership and deadlines, seeking feedback earlier, and using GitHub issues and commits to keep work visible. A good collaborator should make it easier for the next person to pick up the project.

## How my use of AI is becoming more intentional

AI can speed up brainstorming, explaining unfamiliar syntax, generating example code, and identifying possible bugs. However, it should support my thinking rather than substitute for it. I am working toward a workflow where I **first identify the problem and form a hypothesis**, then ask AI focused questions, inspect its reasoning or output, test any generated code, and revise based on actual results. If I cannot explain why a proposed solution works, I should not treat it as finished.

AI is particularly useful as a learning partner when I ask it to challenge my understanding or compare alternatives. Its limitations also reinforce the importance of verification: fluent explanations and plausible code can still be wrong.

## Understanding the software development life cycle

These experiences have made the **software development life cycle (SDLC)** more concrete for me:

1. **Planning and requirements:** PVO ideation asks who the user is and what problem the product solves.
2. **Design:** Decide how inputs, interfaces, data, and logic should work together.
3. **Implementation:** Apply programming concepts and tools to build a working version.
4. **Testing:** Try normal cases, edge cases, and unexpected inputs; compare expected and actual results.
5. **Deployment and documentation:** Use the portfolio and GitHub to share work and make it reproducible.
6. **Feedback and iteration:** Reflect on what worked, communicate with collaborators, and improve the next version.

The process is not strictly linear. It is often necessary to return to design after testing or refine the problem after receiving feedback.

## College Board MCQ results: evidence-based analysis

I completed a 66-question College Board AP CSP multiple-choice practice assessment in **1:24:57**, scoring **53/66 (80.3%)**. The analysis below is calculated from the question-by-question report; it is not a separate CB Analytics dashboard export.

| Big Idea | Correct | Accuracy | Reflection |
|---|---:|---:|---|
| **1 — Creative Development** | 3/5 | **60.0%** | Development processes make sense to me, but the missed debugging and test-case questions reveal a gap between conceptual understanding and systematic testing. |
| **2 — Data** | 13/16 | **81.3%** | I did well with compression, metadata, binary representation, and data representation; I need more care with data comparisons, binary text representation, and interpreting projections. |
| **3 — Algorithms and Programming** | 24/30 | **80.0%** | I generally understand conditions, procedures, and loops, but robot algorithms, program flow, and runtime reasoning need more deliberate tracing. |
| **4 — Computer Systems and Networks** | 3/4 | **75.0%** | I handled Internet communication, redundant routing, and open standards, but missed a question about the IETF. This sample is small. |
| **5 — Impact of Computing** | 10/11 | **90.9%** | This is my strongest observed area: security, encryption, crowdsourcing, licensing, and societal consequences. I missed a comparison involving online versus print encyclopedias. |

### Specific strengths and weaknesses

**Strengths:** Security and encryption (Q2, Q47, Q51), ethical and legal issues (Q16, Q35), procedures and abstraction (Q10, Q20, Q54, Q55, Q57, Q60), compression (Q24, Q25, Q59), and core Internet concepts (Q15, Q23, Q39). These results suggest I can apply a broad base of CSP concepts rather than relying on a single unit.

**Targets for improvement:** I missed Q1 (swapping variables), Q6 (IETF), Q12 (interpreting a social-media projection), Q21 and Q31 (robot algorithms), Q22 (weather procedure), Q28 (binary sequences in a text editor), Q33 (rental-site flowchart), Q43 (algorithm runtime), Q61 (school data comparison), Q62 (encyclopedia comparison), and Q65–Q66 (debugging and selecting tests). I should revisit the exact question explanations before concluding which misconception caused each miss.

The two missed **1.4** questions (Q65 and Q66) make testing a priority. Similarly, missed questions in **3.9** and **3.12** show that I should practice tracing loops and procedures carefully on paper. My **2.3** results were mixed, so I should distinguish what a dataset directly shows from what can reasonably be inferred or predicted from it.

### Timing observations

The reported total is **84 minutes and 57 seconds**, averaging about **77 seconds per question**. Q2 alone shows **24:10** but was correct. That is a reminder that time allocation matters as well as accuracy. I should find out whether that time reflects active problem solving or simply leaving the question open; the timing report alone cannot tell me. I also missed some questions despite answering them quickly, especially Q65 and Q66, which suggests I should slow down enough to test examples rather than choose the first plausible answer.

## Concrete next steps

- **Testing and debugging:** Build a table of normal, boundary, and invalid inputs for small procedures. Revisit Q65–Q66 and practice explaining why each test case matters.
- **Algorithm tracing:** Trace swaps, loops, robot movement, and flowcharts with a variable/state table before checking answer choices.
- **Data interpretation:** Review Q12, Q28, and Q61; distinguish representation errors, comparisons, and unsupported extrapolations.
- **Networks and impacts:** Review the IETF's role and the tradeoffs between collaborative online and print resources.
- **Collaboration and SDLC:** Use a simple issue checklist for each new feature: user problem, acceptance criteria, implementation, tests, feedback, and reflection.
- **AI literacy:** Record the question I asked AI, the suggestion it made, how I verified it, and what I learned independently.

## Final reflection

I am becoming more aware that being a computer scientist involves more than being able to write an algorithm. It means building reliable tools, explaining ideas, collaborating with others, identifying worthwhile problems, testing assumptions, and revising work based on evidence. My MCQ score shows encouraging breadth, but it also exposes specific weaknesses—particularly debugging, test selection, and careful algorithm tracing. My goal for the next phase of CSP is to turn those weaknesses into habits of systematic thinking while making my contributions easier for teammates to understand and build upon.
