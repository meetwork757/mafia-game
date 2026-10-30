# Mafia Game - Multiplayer

Real-time multiplayer Mafia game for friends using PeerJS (no server needed beyond signaling).

## Features
- Create or join a room with a custom Room ID
- Enter username
- **Minimum 5 players**, maximum 10
- All players must click Ready
- Host starts the game when ready
- Random roles: **2 Mafia**, **1 Savior**, rest **Citizens**
- Private flashcard for your role (only you see it)
- Night phase: Mafia kill, Savior protect
- Day phase: Chat + Vote to eliminate someone
- Works on iPhone, Android, and desktop
- Spectators after elimination

## How to play
1. Enable GitHub Pages (Settings → Pages → Deploy from branch `main` / root)
2. Share the link: https://meetwork757.github.io/mafia-game/
3. One person Hosts (creates Room ID) and shares the ID
4. Others Join with the Room ID
5. Everyone enters name, joins, clicks Ready
6. When 5+ players are all Ready, Host starts the game
7. Each player sees their secret role on a flash card
8. Play night and day phases with chat and voting

Have fun!
