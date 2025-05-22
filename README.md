# Show Tracker — React Edition

**Live demo:** https://a4-ezrabarb.glitch.me

This is a React‐based re-implementation of A2’s “Show Tracker.”  
I broke the UI into three reusable components—  
• **ShowTable** for displaying full/liked/disliked lists  
• **AddShowForm** for adding new entries  
• **EditShowForm** for rating updates and deletion  

**What changed from A3?**  
I moved from vanilla JS & direct DOM manipulation to React hooks and component props. Data fetching and state-management are now centralized in `App.js`.

**Did React improve the experience?**  
Absolutely — breaking the UI into components made the code more modular and easier to maintain. The development feedback loop (hot reloads, JSX syntax) was a clear win over manual DOM updating.
