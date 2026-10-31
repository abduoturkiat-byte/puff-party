# Puff Party

A free party game that runs in the browser. 20 marshmallows, 16 sweet rounds, one cherry on top.

**Play:** https://abduoturkiat-byte.github.io/puff-party/

## How to play

- Move: the joystick on the bottom left (or WASD / arrow keys)
- Turn the camera: drag on the right side of the screen (or Q / E), double-tap to reset
- Jump: the Jump button (or Space)
- Dive: the Dive button (or Shift)
- Dance: the Dance button (or F)
- Use a power-up: the candy button that shows up after you grab a wrapped candy (or X)

Every show mixes 5 of the 16 rounds, and each one is harder than the last. Finish in the top spots,
or stay on your feet, to reach the final and build the tallest cherry stack. Every show earns sugar coins;
tap **Style** on the main menu to spend them on colours, hats, dances and trails.

At the end of a show, tap **Share card** to make a picture of how far you got and send it to friends.

## Rounds

Obstacle Race, Jelly Piano, Cocoa Rapids, Gummy Freeze, Frosting Slide, Grill Dash, Mixer Bowl,
Cookie Cutter, Taffy Tag, Musical Cupcakes, Chef Says, Chocolate Fountain, Sprinkle Storm,
Popcorn Panic, Sugar Cubes, and the final, Cherry Stack: grab the cherries popping out of the
birthday candles, stack them on your head, and knock them off everyone else's.

## Modes

Pick a mode on the main menu:

- **Classic**: 5 rounds, each harder than the last, then the Cherry Stack final.
- **Daily**: one show a day, the same for everyone. Only your first try counts, and you can share
  your result as a row of ticks and crosses.
- **Chaos**: every round gets a random twist: low gravity, butter floors, lights out, giants, tiny
  marshmallows, a sugar rush or wind.
- **Endless**: round after round, each one harder, until you are out. Beat your best.

Online, the room host can open **Party settings** to pick which rounds to use, how many rounds a
show has, and whether power-ups are on.

## Power-ups

Wrapped candies float above most rounds. Grab one to get a random power-up, then tap the candy button to use it:

- Rush: run faster for a few seconds
- Spring: your next three jumps go much higher
- Bubble: a shield that blocks the next hit, push or tag
- Gum: throw sticky gum at a marshmallow near you to slow them down

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
