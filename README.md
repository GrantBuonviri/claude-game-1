# Gummy Cluster Parkour

A 3D browser game: you play a gummy cluster coated in crunchy nerds, doing parkour around a skate park.

Open `index.html` in a browser (it loads three.js from a CDN, so you need to be online).

## Controls

| Key | Action |
| --- | --- |
| WASD / arrows | Move (relative to camera) |
| Shift | Run |
| Space | Jump, press again in the air to double jump |
| Space while touching a wall | Wall jump |
| Land on a rail | Grind (Space to jump off) |
| E / Q / F (in the air) | Gummy Flip / Sour 360 / Nerd Twist |
| Mouse | Look (click to lock the pointer) |
| R | Back to start |
| M | Sound on/off |

On phones you get a joystick, a Jump button, a Trick button and a Run toggle, and you drag on the right side of the screen to look.

## The park

- Half pipe with curved quarter pipes. Hit the coping fast and you launch straight up into vert air.
- Funbox with a top rail, plus flat rails on either side.
- Stair set with handrails, raised platforms and a gap.
- Kicker-to-table gap jump, a big kicker, a pyramid and a manual pad.
- Pillar tower climbing to the golden crystal.
- Wall-jump chimney.

Collect all 27 sour crystals to clear the park. Tricks, grinds, wall jumps and big air stack into a combo that pays out (points × number of tricks) when you land. If you hit the ground mid-trick, you bail and lose the combo.

---

# Dark Floes

A souls-like where you play a penguin with an icicle sword. It lives in [`dark-floes/index.html`](dark-floes/index.html). Open it in a browser (it also loads three.js from a CDN).

Walk south across the ice, past the Drowned Rookery and through the white fog, to fight Tuskhild, Tyrant of the Floe: a crowned walrus.

## Controls

| Key | Action |
| --- | --- |
| WASD | Move |
| Shift | Sprint |
| Space | Belly slide (dodge roll with invincibility frames) |
| Left click / J | Strike (three-hit combo) |
| Right click / K | Heavy strike |
| R | Eat a herring (heal, 4 per rest) |
| Q / middle click / Tab | Lock on (flick the mouse to switch targets) |
| E | Rest at hearth, kindle hearth, read messages, pick up krill, enter the fog |
| Mouse / arrow keys | Look (click to lock the pointer) |
| Esc / P | Pause |
| M | Sound on/off |

Gamepads work (RB strike, RT heavy, B slide or hold to sprint, X heal, A use, R3 lock on). On phones you get a stick and on-screen buttons.

## How it plays

- Attacks, slides and sprinting all cost stamina. When it runs out, you wait.
- Enemies telegraph their attacks: seals rear up, skuas climb before they dive, and the walrus winds up its tusks. Slide through the attack, then punish the recovery.
- Hearths are bonfires. Resting refills health and herring, lets you spend krill on Vigor, Endurance or Strength, and brings every enemy back.
- Dying drops all your krill where you fell. Get back there and press E to pick them up. Die again first and they're gone.
- At half health the walrus roars, gets faster, starts charging across the arena, and its belly slam sends out a shockwave ring you have to slide through.
