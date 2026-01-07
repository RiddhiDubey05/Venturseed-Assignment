# Homepage Recreation (Nuxt 3 + Vue 3 + TailwindCSS)

This project recreates the Figma home page design using Nuxt 3.

## Tech Stack
*   **Framework**: Nuxt 3 (Vue 3)
*   **Styling**: TailwindCSS
*   **Language**: TypeScript

## Hosted Link
> ['https://695dfdf81d1643ea199706ab--rainbow-profiterole-9e236b.netlify.app/']

## Deliverables
*   **Repository**: [Link to this repo]
*   **Pixelay Evidence**: See `/pixelay` folder for desktop/mobile comparative screenshots and `notes.md`.

## Setup Instructions
1.  **Install dependencies**:
    ```bash
    npm install
    ```
2.  **Run Development Server**:
    ```bash
    npm run dev
    ```
3.  **Build for Production**:
    ```bash
    npm run build
    node .output/server/index.mjs

Notes on Tradeoffs:
- Coordinates vs Layout: The Figma design used absolute pixel coordinates. I interpreted these as standard sections (Header, Hero, Pricing, Footer) for better responsiveness and standard web flow.
- Visuals: Tailwind utilities and logic-based placeholders were used to match dimensions and styles where assets were abstract.
- Mobile Interaction: A responsive navigation menu was implemented.

=======
*   **Coordinates vs Layout**: The provided Figma dump contained absolute positioning coordinates. I interpreted these as standard sections (Header at top, followed by Hero, Pricing, Footer) rather than placing elements at absolute pixels, to ensure responsiveness and standard web flow.
>>>>>>> Stashed changes
*   Visuals: Logic-based placeholders and Tailwind utilities were used to match the described dimensions and styles (e.g., dashed borders, gaps) where assets were abstract.
*   Mobile Interaction: A responsive navigation menu was implemented.
