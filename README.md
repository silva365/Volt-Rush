# Volt-Rush

# Bolt Bot

A small arcade game where you steer a little robot around a workshop floor,
collecting battery cells before its charge runs out.

## How to play

Open `bolt-bot.html` in any modern browser (Chrome, Safari, Firefox, Edge).
It works offline, though the fonts need an internet connection to load. Click **Power up** to start.


## Controls

| Action | Keyboard | Touch |
| ------ | -------- | ----- |
| Move   | WASD or arrow keys | Drag anywhere on the floor |
| Pause  | P | — |
| Start / restart | Enter or Space | Tap the button |

## Rules

- Your charge drains all the time, a bit faster when you move fast.
- **Battery cell**: +22% charge, +1 point.
- **Gold cell**: shows up now and then for a few seconds. Fills the battery to 100% and gives +3 points.
- **Sparks**: bounce around the floor. A hit costs 25% charge and knocks you back.
- Every 5 cells adds another spark, and the drain speeds up slightly.
- The run ends when the charge hits 0%.

Your best score is saved in your browser.

## Files

- `bolt-bot.html`: the whole game in a single file (HTML, CSS and JavaScript, no dependencies)
