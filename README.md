# 🩺 DiabeDash — Gamified Nutrition Education for Children

<p align="center">
  <strong>Making healthy eating education interactive, engaging, and accessible through gamification and AI.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Domain-Digital%20Health-2ea44f?style=for-the-badge" alt="Digital Health" />
  <img src="https://img.shields.io/badge/AI-Gemini-4285F4?style=for-the-badge" alt="Gemini AI" />
  <img src="https://img.shields.io/badge/Focus-Pediatric%20Health-ff69b4?style=for-the-badge" alt="Pediatric Health" />
  <img src="https://img.shields.io/badge/Status-Research%20%26%20Development-orange?style=for-the-badge" alt="Research and Development" />
</p>

---

##  Overview

**DiabeDash** is a gamified digital health education platform designed to introduce children to healthier food choices and diabetes-related nutritional awareness through interactive gameplay and AI-assisted guidance.

By combining game mechanics with a conversational AI coach, DiabeDash explores how digital experiences can make nutrition education more engaging and help children reflect on everyday dietary decisions.

The project brings together **biomedical engineering, gamification, digital health, and artificial intelligence** to explore new approaches to child-friendly health education.

##  Objectives

- Encourage recognition of healthier food choices through interactive gameplay.
- Make nutrition education engaging through rewards, challenges, and penalties.
- Provide AI-assisted nutritional explanations and healthier alternatives.
- Explore the potential of gamified learning to support diabetes self-management awareness.
- Establish a foundation for evaluating usability, engagement, and educational outcomes.

## How It Works

DiabeDash combines a runner-style game with an AI-powered learning experience.

### 1. Interactive Food Runner

Players navigate a game environment where food choices influence their score.

- **Collect healthy foods** to earn rewards.
- **Avoid less nutritious choices** to prevent penalties.
- Learn through immediate, game-based feedback.

### 2. Healthy Eating Challenges

The gameplay introduces food-selection decisions in a simplified, child-friendly environment. These challenges are intended to encourage awareness of healthier dietary choices without replacing individualised nutritional advice.

### 3. AI Healthy Eating Coach

An integrated conversational coach helps players explore nutrition concepts, understand food choices, and discover healthier alternatives.

The coach is designed to complement the gameplay with accessible, supportive educational guidance.

##  Research Motivation

Children may find conventional nutrition education difficult to engage with consistently. Gamification offers a potential way to introduce health concepts through active participation, while conversational AI may help provide explanations in an accessible format.

DiabeDash provides a platform for investigating questions such as:

- Can interactive food-selection games improve children's nutrition knowledge?
- Does immediate game feedback encourage better understanding of food choices?
- Can AI-assisted explanations make nutrition concepts easier to understand?
- How do usability, engagement, and learning outcomes vary across age groups?

These questions require systematic evaluation; they should not be treated as established outcomes of the current implementation.

##  Technology Stack

| Technology | Purpose |
|---|---|
| React | Interactive user interface |
| TypeScript / JavaScript | Application logic |
| Vite | Development server and build tooling |
| Tailwind CSS | Responsive styling |
| Node.js and Express | Backend API proxy |
| Gemini API | AI-assisted Healthy Eating Coach |
| Firebase | Application services and integration |
| Vercel | Web deployment |

*The table describes the project's intended or previously used stack. Update it to match the current repository implementation.*

## 🏗️ System Architecture

```mermaid
flowchart TD
    A[Child / Player] --> B[DiabeDash Web Interface]
    B --> C[Runner Game]
    B --> D[Healthy Eating Challenges]
    C --> E[Score and Feedback]
    D --> E
    B --> F[AI Healthy Eating Coach]
    F --> G[Node.js / Express API Proxy]
    G --> H[Gemini API]
    H --> G
    G --> F
    F --> I[Educational Guidance]

 Future Enhancements

- Adaptive challenges based on gameplay performance.
- Learning-progress dashboards.
- Expanded, expert-reviewed food education content.
- Age-appropriate explanations and accessibility improvements.
- Controlled evaluation of educational effectiveness.
- Collaboration with paediatric and endocrinology specialists.

##  Medical Disclaimer

**DiabeDash is an educational project, not a medical device or treatment system.** It does not measure blood glucose, diagnose diabetes, prescribe diets, or replace a qualified healthcare professional. Its educational effectiveness and potential behavioural benefits must be established through appropriate evaluation.


<p align="center">
  <strong>DiabeDash</strong><br/>
  <em>Play. Learn. Make Healthier Choices.</em>
</p>
