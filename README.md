# RackDesk

A tournament-night desk for pool halls. Built for a director running the board from a phone or laptop while tables are live.

No accounts. No install. Data stays in the browser until you export a backup.

## What it does

- **Chip tournaments** — winner stays, loser drops a chip, next player comes off the queue
- **Single elimination** — power-of-two bracket with byes and standard seed placement
- **Double elimination** — winners bracket, losers bracket, grand final + reset
- **Table board** — live matches, race-to, score posting, on-deck queue
- **Money** — prize pool from paid entries + added money, standard payout chart by field size
- **TV mode** — big board for a venue screen
- **Backup** — export / import JSON so a dead phone does not kill the night

## Use it

Open `index.html` or the deployed URL. Add names, mark who paid, start the tournament, post scores from the board.

Recommended night-of flow:

1. Setup — format, races, tables, fees
2. Players — paste the list, mark paid
3. Start tournament
4. Live on **Board**
5. Put a tablet or laptop on **TV** facing the room
6. Export a backup at the first break

## Formats and races

| Field size | Typical race | Notes |
|---|---|---|
| 2–6 | Race to 4–5 | Small field can play longer |
| 7–16 | Race to 3–5 | Bar default |
| 17+ | Race to 2–4, losers shorter | Keep the night inside last call |

Chip nights usually start everyone with 2 chips. 3 chips if the field is small and you want more games.

Payouts follow the common "pay about a quarter of the field" pool-hall chart (65/35 on 6–10 players, 40/30/20/10 on 15–20, and so on).
