Game Design Document
Shadow Protocol
1. Game Concept
Shadow Protocol is a short top down stealth game where the player infiltrates a guarded facility, avoids enemy vision, steals classified data, and escapes.
The game focuses on observation, timing, and careful movement rather than combat. The player succeeds by watching patrol patterns, using cover, and choosing the right moment to move.
2. Genre and Platform
•	Genre: Top down stealth action
•	Platform: PC
•	Engine: Unity 6
•	View: Top down camera
•	Session length: 5 to 10 minutes
3. Player Experience
The player should feel like a careful infiltrator operating in a dangerous space. The experience should create tension through the risk of being seen, but it should always feel fair and readable.
The player should frequently be thinking:
•	“Where is the guard looking?”
•	“Can I reach that cover before the patrol turns?”
•	“Should I wait or move now?”
•	“I nearly got caught there.”
4. Core Gameplay Loop
1.	Observe the guards.
2.	Identify a safe route.
3.	Move between cover.
4.	Avoid enemy vision cones.
5.	Collect the data objective.
6.	Reach the extraction point.
7.	Complete the mission or restart after detection.
5. Core Mechanics
Player Movement
The player moves using WASD. Movement should feel responsive and precise. The player must be able to stop and change direction quickly because the game depends on timing.
Interaction
The player presses E to interact with important objects, such as the data objective and extraction point.
Enemy Patrols
Guards move between set patrol points. Their movement should be predictable so the player can learn the pattern and plan around it.
Vision Cones
Each guard has a visible vision cone. If the player enters the vision cone, they are detected. Walls and cover should block vision if this is achievable within scope.
Objective Collection
The player must reach the data object and collect it. Once collected, the extraction point becomes active.
Win and Loss
The player wins by collecting the data and reaching extraction.
The player loses if detected by a guard.
6. Level Design
The game contains one compact mission level.
The level should include:
•	A player start area.
•	A simple entrance section with one guard.
•	A central area with cover and patrol routes.
•	A data objective.
•	An extraction point.
•	Walls or obstacles that create safe and unsafe routes.
The level should teach the player naturally. The first guard introduces vision cones and patrol timing. Later areas combine multiple patrols and tighter movement windows.
7. Enemies
The game has one enemy type: Security Guard.
Guards should:
•	Patrol between waypoints.
•	Face the direction they are moving.
•	Display a visible vision cone.
•	Detect the player when the player enters their vision.
•	Trigger the failure state when detection occurs.
Advanced behaviour such as chasing, searching, sound detection, or multiple enemy types is outside the core version.
8. User Interface
The UI should clearly communicate the current objective.
Example UI messages:
Game State	UI Text
Start	Retrieve the data
Data collected	Reach extraction
Player detected	Detected
Mission complete	Mission Complete
A pause menu and restart button are useful but not essential for the first playable version.
9. Art and Audio Direction
The visual style should be simple, clean, and readable. The player, guards, vision cones, objective, extraction point, walls, and cover must be easy to identify.
Suggested placeholder colours:
Object	Suggested Visual
Player	Blue character
Guard	Red character
Vision cone	Transparent red cone
Objective	Yellow data object
Extraction	Green zone
Walls	Grey blocks
Audio should provide simple feedback for detection, objective collection, and mission completion. Full music and detailed sound design are stretch goals.
10. Minimum Viable Product
The minimum playable version must include:
•	Top down player movement.
•	Camera follow.
•	One playable level.
•	At least one patrolling guard.
•	Visible guard vision cone.
•	Detection and failure.
•	Data objective.
•	Extraction point.
•	Win condition.
•	Basic UI text.
11. Stretch Features
Stretch features may include:
•	Multiple guards.
•	Detection warning meter.
•	Hiding zones.
•	Sprinting.
•	Guard chase state.
•	Timer and ranking system.
•	Mini map.
•	Locked doors or keycards.
•	Improved art and animation.
•	Sound effects and ambient audio.
12. Out of Scope
The following are not part of the core version:
•	Full combat system.
•	Inventory system.
•	Multiple levels.
•	Complex enemy AI.
•	Online multiplayer.
•	Save/load system.
•	Research instrumentation.
•	Heart rate or sensor integration.
13. Success Criteria
The game is successful if:
•	The objective is clear.
•	The player can understand guard vision and patrols.
•	Detection feels fair.
•	The player can complete the mission through stealth.
•	The game can be completed in a short session.
•	Failure encourages the player to try again.
