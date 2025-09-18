# Kochi-Metro-Maintenance-System
Kochi Metro – AI-Driven Train Induction Planning & Scheduling

This repository contains the design prototype and supporting assets for the Smart AI-based train scheduling and induction system developed for Kochi Metro Rail Limited (KMRL). The solution addresses current operational challenges by combining AI, IoT, Cloud-first architecture, and Human-in-the-loop decision support into one platform.

🏷Repository Tagline (GitHub description)
“AI-powered metro train induction & scheduling prototype with live route visualization, cloud-first design, and human-in-the-loop controls for Kochi Metro Rail Limited.”

•Repository Contents
prototype.fig (or .make) → Full Figma design prototype.


•How to Open the Prototype

Go to Figma Web
 (recommended) or open the Figma Desktop App.
Click Import File.
Select the prototype.fig (or .make) file from this repository.
The project will load into your Figma workspace for viewing and editing.

•Key Features of the Prototype
Kochi Metro Route Visualization
Includes Blue Line (Aluva → Tripunithura) and Pink Line (JLN Stadium → Infopark II) with all stations.
Accurate alignment of metro routes with GPS-informed map structure.
What-If Simulator (Interactive)
Supervisors can simulate different scenarios (maintenance delay, branding priority, clearance pending, mileage balancing).
Visual animated representation of trains moving across tracks, reversing correctly at line ends.
Cloud-First Architecture Design
Auto-scaling environment to prevent performance bottlenecks.
Cloud-native integration for AI engine, IoT sensor feeds, and visualization dashboard.
Human-in-the-Loop Control
Supervisors can override AI suggestions with a visual, intuitive UI.
Shadow Mode Deployment → AI validates its schedule against human-created schedules before taking over live operations.
IoT + Resource Agents Concept
Each train acts as an autonomous agent, reporting status via IoT sensors.
Resources (maintenance slots, stabling bays) modeled as resource agents, allowing conflict-free scheduling.

•Why This Solution?

KMRL currently faces challenges in induction planning due to fragmented spreadsheets, WhatsApp logs, and manual decision-making. This prototype demonstrates a scalable, reproducible, and AI-driven approach that solves:

Reducing unscheduled rake withdrawals (telecom/clearance issues).
Balancing mileage for components → lowers lifecycle costs.
Meeting advertiser branding commitments → prevents penalties.
Minimizing shunting operations → improves safety & reduces energy.

•Mitigation Strategy

Shadow Mode Deployment → AI runs in parallel with humans until validated.
Cloud-First Architecture → Auto-scaling ensures performance even during fleet growth.
Human-in-the-Loop UI → Supervisors retain final authority with override tools.

•Future Roadmap

Integrate real-time GPS tracking of trains using IoT sensors.
Deploy live Leaflet.js + Lottie-based animated dashboard with zoomable metro map.
Implement AI feedback loops to improve scheduling accuracy over time.
Extend to multiple depots with multi-line scaling.

•Notes

.fig and .make files are both valid Figma formats. If you downloaded .make, simply re-import into Figma Web and export as .fig.
For live web prototype hosting, designs can be exported into React/HTML via Anima/Locofy plugins and deployed on GitHub Pages / Vercel.


