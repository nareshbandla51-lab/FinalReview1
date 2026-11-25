# NextPlay – Upgraded Gaming Tournament Portal

## Features
- Welcome page and animated 3D-style gaming page.
- Player and organizer account types.
- Three playable browser mini-games: Reaction Rush, Tic Tac Toe vs computer, Memory Match.
- Organizer tournament creation: game, format, date, time, prize pool, capacity and entry fee.
- Player tournament registration with capacity checks.
- Team creation and member email list.
- Organizer match scheduling and result publishing.
- Tournament list, player registrations and leaderboard.
- Local Storage persistence.

## Run in VS Code
1. Extract the ZIP and open the `NextPlay_Upgraded` folder in VS Code.
2. Open Terminal in that folder.
3. Run `npm install`
4. Run `npm run dev`
5. Open the localhost URL shown by Vite (usually http://localhost:5173).

## Demo walkthrough
1. Create an account with account type **Tournament organizer** to create tournaments, update schedules and publish results.
2. Log out and create another account as **Player** to register, create a team and play games.
3. Browser games are playable inside the website.

## Important limitations
This is a front-end prototype. Data is saved in the current browser's Local Storage; different browsers/devices do not share data. Authentication is not secure. It does not include real online multiplayer, payment processing, or verified prize distribution. A backend and database are required for a production multi-user portal.
