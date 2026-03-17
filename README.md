# CareRoute Ambulance Game

Top-down ambulance rescue MVP.

## Live URLs
- Game: https://watsoncsulahack.github.io/careroute-ambulance-game/
- Landing page: https://watsoncsulahack.github.io/careroute-landing-page/
- Web prototype (Android-parity flow): https://watsoncsulahack.github.io/careroute-prototype-web/

## Gameplay
- Auto-start engine once a run begins
- Arrow keys rotate ambulance
- Mobile tap-and-hold steering
- Start money: **$1000**
- Triangle obstacles: first at 5s, then one new obstacle every 3s (25s lifetime)
- Water splats: begin after 15s and spawn every 15s (30s lifetime); they slow momentum only
- Roadblocks: begin after 30s and spawn every 10s (8s lifetime); they block passage
- Cars: begin after 45s, refresh every 15s, stay 10s, and move at consistent medium speed
- Patients must be picked up within 10s, then dropped off within 10s
- Money drain is momentum-based (~$100/s at standstill down to ~$4/s at top momentum)
- Social leaderboard: submit your name + high score and compare at the event
