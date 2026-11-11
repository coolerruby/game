# Roblox Game Project — Beginner Roadmap

This roadmap is a first 14-day learning sprint toward a small playable Roblox prototype. The game concept is not chosen yet, so keep the prototype simple and adapt tasks once the concept is decided.

## Day 1 — Setup
- [ ] Install Roblox Studio and open it
- [ ] Confirm GitHub repository access
- [ ] Connect this repository to v0 (in v0's GitHub import flow)
- [ ] Inspect repository structure before generating files
- [ ] Create a project notes document

## Day 2 — Game concept
- [ ] Choose a genre and core fantasy
- [ ] Define the main gameplay loop in one sentence
- [ ] Identify the first tiny playable objective
- [ ] Sketch the first map and visual style

## Day 3 — Roblox Studio basics
- [ ] Learn Explorer and Properties panels
- [ ] Create a Baseplate place
- [ ] Add parts, materials, and a SpawnLocation
- [ ] Play-test movement

## Day 4 — Luau basics
- [ ] Learn variables, functions, conditions, and events
- [ ] Run a simple script and read the Output window
- [ ] Understand Script vs LocalScript at a beginner level

## Day 5 — First environment
- [ ] Build a small starting area
- [ ] Add a clear objective location
- [ ] Test movement and map boundaries

## Day 6 — Core gameplay loop
- [ ] Implement one simple objective
- [ ] Add a reward or feedback
- [ ] Add a basic win/completion condition
- [ ] Play-test the full loop

## Day 7 — UI
- [ ] Create a simple title/menu screen
- [ ] Add a working Play button
- [ ] Add a minimal HUD
- [ ] Check legibility and mobile layout

## Day 8 — Progression
- [ ] Add a basic points or XP counter
- [ ] Show feedback when the player earns points
- [ ] Test edge cases

## Day 9 — Saving
- [ ] Learn Roblox DataStore basics
- [ ] Enable Studio API access only for a test experience as needed
- [ ] Implement and test safe save/load behavior
- [ ] Never put secrets in client scripts

## Day 10 — Polish
- [ ] Improve lighting and materials
- [ ] Add simple animations/effects where appropriate
- [ ] Keep effects readable and performance-friendly

## Day 11 — Companion website (optional)
- [ ] Use v0 to scaffold a simple game landing page
- [ ] Add game description and placeholder artwork
- [ ] Add a Play link only after the Roblox experience URL exists
- [ ] Keep the website separate from Roblox gameplay code

## Day 12 — QA
- [ ] Test the game from a fresh player session
- [ ] Test UI at different screen sizes
- [ ] Test progression and saving
- [ ] Fix and retest bugs

## Day 13 — Release preparation
- [ ] Prepare a game icon and thumbnail
- [ ] Write a clear, accurate game description
- [ ] Review Roblox publishing and privacy settings with a parent/guardian
- [ ] Check Roblox community and safety rules

## Day 14 — Prototype milestone
- [ ] Share a private test build or publish when ready
- [ ] Gather feedback from trusted testers
- [ ] Record the top 3 improvements
- [ ] Plan the next sprint

## Tool roles
- **Roblox Studio:** build and run the actual Roblox experience.
- **Luau:** scripting language for Roblox.
- **GitHub:** version history and project documentation.
- **v0:** optional companion website/UI prototyping; it does not directly build the Roblox 3D game.
- **Neon:** optional PostgreSQL for a separate website backend only if there is a real need. Start with Roblox's built-in player data services for game progress.

## First v0 prompt
Inspect this empty repository before changing anything. Explain its structure and propose a safe setup for a beginner's Roblox project plus an optional Next.js companion website. Keep Roblox Studio/Luau game files conceptually separate from website code. Do not add a database or authentication yet. Do not make changes until you explain the proposed structure.
