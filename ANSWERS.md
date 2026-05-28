1. How to run
This is a vanilla web application. No installation, compilers, or servers are required.

Steps: Download the index.html file and open it directly in any modern web browser (Chrome, Firefox, or Safari).


2. Stack & design choices
I used Vanilla HTML, CSS, and JavaScript.

The "Why": As a beginner, I chose the simplest stack possible to ensure I could focus on the user experience and meeting the specific project requirements without the overhead of a complex framework.

Interaction Decision 1 (Paused State): I added a .paused class that dims the timer to 20% opacity and scales it down. I did this because a static timer can look like a bug; the visual change makes it clear the clock is "resting."

Interaction Decision 2 (Daily History): I placed the history list directly under the timer. This creates a "progress bar" feel where the user can see their day's achievements at a glance, which is a key psychological motivator in the Pomodoro technique.

3. Responsive & accessibility
Device Handling: The app uses a flexible 90% width on mobile (360px) and caps at 420px on desktop. I used margin: 0 auto and flexbox to ensure the timer remains perfectly centered on any screen size.

Accessibility Handled: I used native <button> tags. This is a deliberate choice because buttons are accessible by default—users can navigate between "Start" and "Reset" using only the Tab key and trigger them with Enter.

Accessibility Skipped: I knowingly skipped "Screen Reader Aria-Labels" for the timer countdown. Because the numbers change every second, a screen reader might try to announce every single second, which can be overwhelming for a user.

4. AI usage
I used Gemini to act as my "Technical Lead" for this project.

What I asked: I provided the project requirements and asked for a functional Pomodoro timer that handles localStorage and "daily resets."

The Change: The AI initially gave me a very plain "Done" alert. I directed the AI to change this because the assessment asked for a "satisfying session-done moment." I asked for a CSS animation called pulse-success and a brief delay before the next cycle starts. This ensures the user actually notices and feels the reward of finishing a session.

5. Honest gap
My biggest gap is a deep, line-by-line understanding of Asynchronous JavaScript (how setInterval works behind the scenes). While the AI helped me build a working heart for the timer, I would need more study time to manually write the logic that keeps the timer perfectly accurate if the browser tab is minimized or put to sleep. With another day, I would also learn how to "Base64 encode" the audio file so the notification works perfectly even if the user has no internet connection.
