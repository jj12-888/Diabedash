# DiabeDash

**A Gamified Approach to Nutrition Education and Diabetes Awareness in Children**

## Overview

DiabeDash is a digital health education platform designed to introduce children to healthier food choices and diabetes-related nutritional awareness through interactive gameplay and AI assisted guidance.

The platform combines a runner-style game with a conversational Healthy Eating Coach to create an engaging environment for exploring basic nutrition concepts.

## Features

- **Interactive Gameplay:** Collect healthier food items, avoid less nutritious choices, and receive score-based feedback.
- **Nutrition Education:** Introduces food-selection concepts through simple, interactive challenges.
- **AI Healthy Eating Coach:** Provides accessible explanations of nutrition concepts and suggestions for healthier alternatives.
- **Gamified Learning:** Uses rewards and immediate feedback to encourage active participation.

## Technology Stack

| Technology | Purpose |
|---|---|
| React | User interface |
| TypeScript / JavaScript | Application logic |
| Vite | Development and build tooling |
| Tailwind CSS | Styling |
| Node.js and Express | Backend and API integration |
| Google Gemini API | AI-assisted educational guidance |
| Firebase | Application services, where applicable |
| Vercel | Deployment |

## Getting Started

### Prerequisites

- Node.js and npm
- Git
- Gemini API key, if using the AI coach
- Firebase configuration, if required

### Installation

Clone the repository:

```bash
git clone <repository-url>
cd DiabeDash
```

Install dependencies:

```bash
npm install
```

Configure the required environment variables in the backend environment file:

```env
GEMINI_API_KEY=your_api_key
```

Start the development server:

```bash
npm run dev
```

If the backend is maintained separately, start it using the commands specified in its `package.json`.

Do not commit API keys or credentials to the repository.

## Research Motivation

DiabeDash explores the use of gamification and conversational AI in child-focused nutrition education. The project provides a foundation for investigating whether interactive challenges and contextual feedback can support nutrition knowledge and dietary decision-making awareness.

Potential evaluation areas include usability, engagement, knowledge retention, and learning outcomes.

## Future Development

- Adaptive gameplay and personalised educational feedback
- Expanded, evidence-informed nutrition content
- Learning progress tracking
- Accessibility improvements
- Structured usability and educational evaluation
- Collaboration with nutrition and paediatric healthcare professionals

## Limitations

DiabeDash is an educational project, not a diagnostic or therapeutic medical device. It does not measure blood glucose, prescribe diets, or replace professional medical advice.

Its educational effectiveness and potential behavioural benefits require appropriate evaluation before any claims of improvement can be made.

## Research Direction

**Proposed title:** *DiabeDash: Design and Evaluation of a Gamified, AI-Assisted Platform for Nutrition Education and Diabetes Self-Management Awareness in Children.*

The research aims to examine the platform's usability, engagement, and potential to support nutrition learning through interactive digital experiences.

---

*DiabeDash — Interactive learning for nutrition awareness.*

