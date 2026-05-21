# Assessment Responses

### 1. How to Run
Open the `index.html` file at the root of the project directly within any desktop or mobile web browser. No local setup commands, installations, or node configurations are needed.

### 2. Stack & Design Choices
I chose a Vanilla HTML/CSS/JavaScript setup to build a lightweight, single-page UI. Avoiding frameworks kept the load speed instant and clean.
* **Visual Choice 1:** Dynamic color shifts map directly to current state changes—a soft red background accents focus blocks, transitioning to calm green during active break sessions, and an amber layer for global user pauses.
* **Visual Choice 2:** The primary numerical display properties leverage `font-variant-numeric: tabular-nums` matching a substantial `5rem` sizing layout. This keeps changing characters perfectly aligned, preventing jarring screen shifting.

### 3. Responsive & Accessibility
* **Responsiveness:** Managed via responsive Flexbox constraints combined alongside explicit container styling limits (`max-width: 400px`), optimizing rendering flow on layouts scaling from 360px phones up to wide monitors.
* **Accessibility Highlight:** Strict structural element layouts with high color contrast scores matching clean background pairs ensure reliable text parsing properties.
* **Skipped Highlight:** Advanced keybinding macros were purposefully omitted to safeguard native browser structural screen reader control operations.

### 4. AI Usage Disclosure
* **Tool Used:** Gemini AI
* **What I asked:** "I am a complete beginner who only knows basic HTML/CSS/JS. I have a critical university exam day after tomorrow and less than two hours to spare. Please provide a functional, single-file Pomodoro timer template so I can submit this placement assessment on time."
* **What it gave me:** A complete single-file structure processing internal interval countdown handlers and dynamic localStorage tracking.
* **What I modified / My approach:** Due to my upcoming exam constraints, I did not modify or rewrite the functional logic. I am submitting this code with complete transparency to show how I approached a major time clash, using AI as a delivery aid.

### 5. Honest Gap
The primary gap is my deep structural understanding of the core JavaScript mechanisms handling the timer's loop logic. While the application executes perfectly, I cannot personally explain every line of the browser interval arrays. I am explicitly aiming for placement in the **Beginner Track** of the fellowship so I can dedicate the upcoming weeks to mastering these exact concepts from scratch.
