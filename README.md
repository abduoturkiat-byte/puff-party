# Puff Party

A free party game that runs in the browser. 20 marshmallows, 12 sweet rounds, one cherry on top.

**Play:** https://abduoturkiat-byte.github.io/puff-party/

## How to play

- Move: the joystick on the bottom left (or WASD / arrow keys)
- Turn the camera: drag on the right side of the screen (or Q / E), double-tap to reset
- Jump: the Jump button (or Space)
- Dive: the Dive button (or Shift)
- Dance: the Dance button (or F)

Every show mixes 5 of the 12 rounds, and each one is harder than the last. Finish in the top spots,
or stay on your feet, to reach the final and grab the cherry on top. Tap **Style** on the main menu
to pick your colour and hat.

## Rounds

Obstacle Race, Jelly Bridge, Cocoa Rapids, Grill Dash, Whisk Whirl, Candy Wall, Taffy Tag,
Sweet Swap, Choco Flood, Sprinkle Storm, Cookie Crumble, and the final, Cherry on Top.

## Online with friends

1. Tap **Play online**, then **Create room**.
2. Tap **Invite friends** and send the link (or tell them the 4-letter code).
3. When everyone is in, tap **Start**. Bots fill the empty spots, up to 20 players.

Online play is peer to peer: the person who creates the room hosts the game on their device,
and the others connect to them directly. Public Nostr relays and WebTorrent trackers are only used
so the players can find each other. Some mobile networks block direct connections; if friends can't
connect, try again with everyone on Wi-Fi. Everyone needs the same version of the game, so reload
the page if a friend can't join.

## Files

- `index.html`: the whole game
- `lib/three.min.js`: three.js r128
- `lib/p2p.js`: Trystero 0.26 (Nostr and BitTorrent strategies), bundled
- `lib/LICENSES.md`: licenses for the bundled libraries
