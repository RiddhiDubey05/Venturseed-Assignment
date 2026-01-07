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
<img width="1917" height="919" alt="Screenshot (476)" src="https://github.com/user-attachments/assets/ab138b40-aff6-440f-86c6-007204329f29" />

<img width="1920" height="906" alt="Screenshot (478)" src="https://github.com/user-attachments/assets/cc381f69-c1d8-41dc-8792-936050bc29d9" />


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

=======
*   **Coordinates vs Layout**: The provided Figma dump contained absolute positioning coordinates. I interpreted these as standard sections (Header at top, followed by Hero, Pricing, Footer) rather than placing elements at absolute pixels, to ensure responsiveness and standard web flow.
>>>>>>> Stashed changes
*   Visuals: Logic-based placeholders and Tailwind utilities were used to match the described dimensions and styles (e.g., dashed borders, gaps) where assets were abstract.
*   Mobile Interaction: A responsive navigation menu was implemented.
