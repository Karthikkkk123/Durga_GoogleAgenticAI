# Shiksha Saathi - Intelligent Educational Platform

## Overview

Shiksha Saathi is a comprehensive educational platform that combines multiple AI-powered features to enhance the learning and teaching experience. This project uses Lovable for frontend development and integrates various specialized features.

## Live Demo

- **Deployed Application**: [Shiksha Saathi Live](https://shiksha-saathi.lovable.app/)

### Demo Video
[![Shiksha Saathi Demo](https://drive.google.com/thumbnail?id=1Bl6um3JZG16G1PJA6j0fYeZxSu6HnLPL)](https://drive.google.com/file/d/1Bl6um3JZG16G1PJA6j0fYeZxSu6HnLPL/view?usp=sharing)

Click on the image above to watch the full demo video

## Getting Started with the Frontend

### Prerequisites

1. Node.js & npm - [Install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)
2. Git

### Installation and Setup

```bash
# Clone the repository
git clone <YOUR_GIT_URL>

# Navigate to project directory
cd shiksha-saathi-main

# Install dependencies
npm install

# Start development server
npm run dev
```

The application will be available at `http://localhost:5173` (or the port shown in your terminal).

## Project Structure

Our features are organized in the `Features/` directory:

### 1. EduAI Insights
**Purpose**: AI-powered teaching analytics and engagement monitoring
[Add detailed description of EduAI Insights feature here]

Key Components:
- Response Analysis
- Engagement Tips
- Metric Dashboard
- Summary Message Generation

### 2. Exam Guide (GradeWise)
**Purpose**: Intelligent exam grading and assessment system
[Add detailed description of Exam Guide feature here]

Key Components:
- Document Upload & OCR
- AI-Powered Grading
- Results Report Generation
- Student Profile Management

### 3. Frontend Navigation
**Purpose**: Educational content navigation system
[Add detailed description of Frontend Navigation feature here]

Key Components:
- Subject-wise Organization
- Topic Navigation
- Interactive Content Display
- HTML Optimization

### 4. Inclusive Assessment (EmotionLearn)
**Purpose**: Emotion-aware learning platform
[Add detailed description of EmotionLearn feature here]

Key Components:
- Voice Call Integration
- Student State Detection
- Interactive Quiz System
- Analytics Dashboard

### 5. Sahayak Story
**Purpose**: Multilingual content generation and translation
[Add detailed description of Sahayak Story feature here]

Key Components:
- Language Translation
- Content Generation
- Image Generation
- PDF Compilation

### 6. Studio (InterviewPrepAI)
**Purpose**: AI-powered interview preparation system
[Add detailed description of Studio feature here]

Key Components:
- Teacher Dashboard
- Question Generation
- Speech Processing
- Feedback Generation

## Technology Stack

- **Frontend Framework**: React with Vite
- **UI Components**: shadcn-ui
- **Styling**: Tailwind CSS
- **Type Safety**: TypeScript
- **State Management**: React Query
- **Routing**: React Router DOM

## Development Tools

There are several ways of editing your application.

**Use Lovable**

Simply visit the [Lovable Project](https://lovable.dev/projects/028a708b-3a28-4088-b12c-c5c00bb9bd79) and start prompting.

Changes made via Lovable will be committed automatically to this repo.

**Use your preferred IDE**

If you want to work locally using your own IDE, you can clone this repo and push changes. Pushed changes will also be reflected in Lovable.

The only requirement is having Node.js & npm installed - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)

Follow these steps:

```sh
# Step 1: Clone the repository using the project's Git URL.
git clone <YOUR_GIT_URL>

# Step 2: Navigate to the project directory.
cd <YOUR_PROJECT_NAME>

# Step 3: Install the necessary dependencies.
npm i

# Step 4: Start the development server with auto-reloading and an instant preview.
npm run dev
```

**Edit a file directly in GitHub**

- Navigate to the desired file(s).
- Click the "Edit" button (pencil icon) at the top right of the file view.
- Make your changes and commit the changes.

**Use GitHub Codespaces**

- Navigate to the main page of your repository.
- Click on the "Code" button (green button) near the top right.
- Select the "Codespaces" tab.
- Click on "New codespace" to launch a new Codespace environment.
- Edit files directly within the Codespace and commit and push your changes once you're done.

## What technologies are used for this project?

This project is built with:
#Backend: 
- FireStore Database
- Firebase Studio
- Vertex AI
- ADK (Agentic Development Kit)
- Google Cloud Platform
- Vertex Vision
- Google API
- Gemini Veo 3
- Gemini Imagen
- MCP Tool-Box
- ElevenLabs

#Frontend: 
- TypeScript
- React
- Vite
- Tailwind CSS
- HTML
- CSS

## Project Folder Structure

```
shiksha-saathi-main/
├── Features/
│   ├── Agentic/
│   │   └── develop/
│   │       ├── app.yaml
│   │       ├── main.py
│   │       ├── requirements.txt
│   │       ├── sahayak_analytics.py
│   │       ├── static/
│   │       └── templates/
│   ├── EduAI_Insights/
│   │   ├── src/
│   │   │   ├── ai/
│   │   │   ├── app/
│   │   │   ├── components/
│   │   │   ├── hooks/
│   │   │   └── lib/
│   │   └── docs/
│   ├── Exam_Guide/
│   │   ├── src/
│   │   │   ├── ai/
│   │   │   ├── app/
│   │   │   ├── components/
│   │   │   ├── hooks/
│   │   │   ├── lib/
│   │   │   └── services/
│   │   └── docs/
│   ├── Frontend-master/
│   │   ├── public/
│   │   │   ├── chemistry/
│   │   │   ├── maths/
│   │   │   └── [simulation files]
│   │   └── src/
│   ├── Inclusive_Assessment/
│   │   └── emotion/
│   ├── Sahayak_Story/
│   │   └── src/
│   └── Studio-master/
│       └── src/
├── public/
│   └── lovable-uploads/
├── src/
│   ├── components/
│   │   └── ui/
│   ├── hooks/
│   ├── lib/
│   └── pages/
├── package.json
├── tsconfig.json
├── vite.config.ts
└── [other config files]
```

Each feature in the `Features/` directory is a self-contained module with its own implementation, configuration, and documentation. The main frontend application in the root `src/` directory serves as the unified interface for all these features.

## Development Tools

