# ⚡️ Flash UI

**Creative UI generation in a flash.**

Flash UI is a high-performance, immersive playground that leverages the creative and coding capabilities of **Gemini 3 Flash**. Instead of generating a single generic response, Flash UI explores three distinct design directions for every prompt, pushing the boundaries of generative interface design through physical and material metaphors.

---

## ✨ Key Features

- **Triple Direction Generation**: Every prompt generates three unique "Artifacts," each following a different evocative design persona (e.g., *Bioluminescent Glass*, *Brutalist Blockwork*, *Tactile Risograph*).
- **Real-Time Streaming**: Watch the model "think" and code in real-time. The UI streams the raw HTML/CSS directly into a live preview as it arrives.
- **Conceptual Variations**: Select any generated component to spawn "Radical Variations." The engine re-prompts the model using aggressive physical metaphors to reimagine the UI from scratch.
- **Immersive Focus Mode**: A 3D "Deck" interface allows you to swipe through your history of generations. Click any card to enter **Focus Mode** for full-screen interaction and testing.
- **IP-Safe Creativity**: Built-in prompt engineering ensures the model avoids trademarked styles or artist names, instead relying on "Material Logic" and "Physicality" to describe aesthetics.
- **Source Access**: View the raw source code of any generated component instantly.

---

## 🛠 Tech Stack

- **Framework**: React 19 (Functional Components, Hooks)
- **AI Engine**: [Google GenAI SDK (@google/genai)](https://www.npmjs.com/package/@google/genai)
- **Model**: `gemini-3-flash-preview` (Optimized for speed and high-fidelity code generation)
- **Styling**: Modern CSS3 (Custom Properties, 3D Transforms, Backdrop Filters)
- **Icons**: Custom SVG set for a sleek, minimal aesthetic.

---

## 🚀 Getting Started

Flash UI is designed to run in a controlled environment where the Gemini API key is provided via `process.env.API_KEY`.

1. **Prerequisites**: An active Gemini API key from [Google AI Studio](https://aistudio.google.com/).
2. **Setup**:
   - Ensure your environment provides `process.env.API_KEY`.
   - The app uses an `importmap` to load dependencies via ESM.sh, meaning no `npm install` is required for the frontend to run in the browser.

---

## 🎨 Design Philosophy

Flash UI moves away from the "Chatbot" metaphor. It treats AI as a **Material Laboratory**. 

- **Physical Metaphors**: Instead of asking for "Modern UI," the app instructs the model using terms like *Grainy Risograph*, *Spectral Prismatic Diffusion*, or *Kinetic Wireframe*. This results in more unique, high-contrast, and visually interesting components.
- **Non-Linear Exploration**: By providing three options at once, the user is encouraged to compare and contrast different layouts and color theories immediately.

---

## 📂 Project Structure

- `index.tsx`: Main application logic, session management, and Gemini API orchestration.
- `components/`:
    - `ArtifactCard.tsx`: The container for generated components, handling streaming overlays and focus transitions.
    - `DottedGlowBackground.tsx`: A high-performance canvas-based background for environmental immersion.
    - `SideDrawer.tsx`: Handles variations and code inspection.
- `index.css`: The "Radical" design system, defining the 3D stage and focus mode logic.
- `types.ts`: TypeScript interfaces for Sessions, Artifacts, and Variations.

---

## 📜 License

SPDX-License-Identifier: Apache-2.0

*Developed with ❤️ by Ammaar Reshi*

