# Zedu Channel Motion — HNG15 Task 2

A **standalone, independently recreated Channel Directory UI concept** for demonstrating a restrained whimsical animation improvement to Zedu. This is **not official Zedu source code** and **is not connected to production**.

## What was improved
- Subtle staggered entrance for channel results
- Gentle hover lift and directional interaction cue
- Smooth input focus state and immediate search response
- Support for motion reduction (`prefers-reduced-motion`)
- Responsive layout for mobile and desktop

## Interaction demo
Open `index.html` in your browser. Search for `general`, ` general `, or another channel name. Try sorting, filtering for joined channels, hovering over cards, and dismissing the information banner. All data is sample data.

## Deploy
Upload this repository to GitHub. Import it into Vercel with **Framework Preset: Other**, root `./`, no build command and no output directory override.

## Present to reviewer
Show the recreated Zedu Channel Directory alongside real Zedu for visual context. Explain that the animated result list and hover effects are the design contribution. The design is a mock; actual integration needs Zedu source access and approval. Avoid presenting this as live production changes.

## Added interaction: joining a channel

Click **Join +** on any unjoined channel to see a small, contained celebration and a clear **You joined!** confirmation. The state updates in this browser session only; it does not modify a real Zedu account. Motion respects the device's reduced-motion setting.
