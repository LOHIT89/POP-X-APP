PopX App is a pixel-perfect React implementation of the PopX mobile UI, centered on the webpage with seamless navigation.
Screens: Welcome, Login, Register, and Account Settings.
Tech Stack: React 18, plain CSS per component, Google Fonts (Sora).
Run locally:
bashnpm install
npm start
Then open http://localhost:3000.
Build: npm run build
Deploy to Vercel: Push to GitHub → import at vercel.com → click Deploy (auto-detects CRA).
Design notes: Mobile frame is 390×844px centered on desktop with rounded corners and shadow. Goes full-screen on viewports ≤430px. Navigation is state-driven via a navigate(page, data) prop. Purple accent: #6c35de.
