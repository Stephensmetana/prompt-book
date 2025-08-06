# AI Prompt: Generate Application Instructions for AI Coding Assistants

You are a senior software architect.  
Generate a complete and clear set of repository-level instructions for GitHub Copilot or any LLM-powered coding assistant.

The goal is to define an entire software application and make it possible for the AI assistant to help develop the project correctly from start to finish.

Use Markdown formatting. The output will be saved in a `.copilot-instructions.md` file. The instructions should be:

- Concise but comprehensive  
- Written in imperative, present-tense language  
- Organized into clear sections: Overview, Architecture, Feature List, Implementation Details, Development Standards, and Testing Guidelines  
- Free of speculation and uncertainty (no "maybe", "could", "might")

Please follow this structure exactly:

---

## 1. Project Overview  
Briefly explain what the application is, its tech stack, and its core purpose.

## 2. Architecture  
Define the project's structure, key technologies, design patterns, and any conventions (e.g., file structure, class structure, frameworks, libraries, tool versions, etc.).

## 3. Feature List  
List each feature in a bullet format. This is a high-level scope.

## 4. Implementation Details (User Stories & Requirements)  
For each feature, write a short user story, followed by:
- Required inputs/fields and validation rules  
- Expected endpoints (if applicable)  
- Events to emit (e.g., Kafka topics, WebSocket messages)  
- Any third-party integration or side effects

## 5. Development Standards  
Define coding standards, naming conventions, testing expectations, REST/API structure, formatting rules, and any specific practices required for consistency.

## 6. Testing Guidelines  
Describe how each part of the app should be tested (unit, integration, e2e), the frameworks to use, and minimum test coverage requirements.

---

## APP FEATURES TO BASE INSTRUCTIONS ON:

[List your app features here.]

---

Generate complete instructions based on the features and structure above.

---

# Example Use

## APP FEATURES TO BASE INSTRUCTIONS ON:

- User authentication using JWT  
- File upload and download  
- Background video transcoding with progress updates  
- Real-time chat support  
- Admin dashboard with analytics

