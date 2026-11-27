# Throttle Brawl

A browser bike-combat racer built for phones. Race 9 riders down a sunset highway, and knock them off their bikes on the way.

Everything is in one file (`index.html`): no build step and no dependencies. The art and sound are all generated in code.

## Controls

**Phone (motion)**
- Tilt left or right to steer. Turning the phone like handlebars works best in landscape.
- Tip the top of the phone down for gas, and tip it up to brake. The angle you hold it at during the 3-2-1 countdown becomes "cruise".
- Shake the phone to jump over barrels and traffic. You also can't be hit while you're in the air.
- The left button kicks and the right button punches. Both hit whichever rider is beside you. A kick has more reach and does more damage, and a punch is faster.
- Use Pause → Recenter tilt if the controls feel off.

**Desktop**
- ← → steer, ↑ gas, ↓ brake
- Space jumps, Z kicks, X punches, P pauses

If a phone has no motion sensor (or permission was denied), drag on the screen to steer and throttle, and tap to jump.

## Running it

Motion sensors only work over HTTPS. To play on a phone, turn on GitHub Pages: **Settings → Pages → Deploy from a branch → `main` / root**. The game then runs at `https://geekvikas.github.io/test/`.

On iPhone, tap START and allow "Motion & Orientation Access" when Safari asks.

Locally: `npx serve .` (or any static server) and open the URL. Motion needs HTTPS, so use the keyboard on desktop.
