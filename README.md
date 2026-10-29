# Puff Party

A free party game that runs in the browser. 20 marshmallows, wobbly obstacle rounds, one crown.

**Play:** https://abduoturkiat-byte.github.io/puff-party/

## How to play

- Move: drag on the left side of the screen (or WASD / arrow keys)
- Jump: the Jump button (or Space)
- Dive: the Dive button (or Shift)

Every show mixes rounds that get harder as you go. Finish in the top spots, or stay on your feet,
to reach the final and grab the crown.

## Online with friends

1. Tap **Play online**, then **Create room**.
2. Tap **Invite friends** and send the link (or tell them the 4-letter code).
3. When everyone is in, tap **Start**. Bots fill the empty spots, up to 20 players.

Online play is peer to peer: the person who creates the room hosts the game on their device,
and the others connect to them directly. Public Nostr relays and WebTorrent trackers are only used
so the players can find each other. Some mobile networks block direct connections; if friends can't
connect, try again with everyone on Wi-Fi.

## Files

- `index.html`: the whole game
- `lib/three.min.js`: three.js r128
- `lib/p2p.js`: Trystero 0.26 (Nostr and BitTorrent strategies), bundled
- `lib/LICENSES.md`: licenses for the bundled libraries
