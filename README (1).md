# Filter station: showcase build

One file, `index.html`. No accounts, no configs, nothing to install.

## Put it online (2 minutes, free)
1. On github.com create a new public repository and upload `index.html`.
2. Settings → Pages → Deploy from a branch → `main` / root → Save.
3. Open the address it gives you on the laptop **and** the phone.

Solo or offline: just double-click `index.html` on the laptop. It works alone, without syncing to other devices.

## Hidden controls (nothing on screen shows them)
| Action | Laptop | Phone |
|---|---|---|
| Flip Clean / Needs cleaning | **T** | hold the water 1 second |
| Filter wear on/off (warning appears and clears) | **F** | hold "Flow rate" 1 second |
| Hide / show the turbidity text | **H** | hold "Filter station" 1 second |
| Restart everything | **Shift + R** | not available |

Loading the page on a laptop also restarts everything. A phone just joins the running session.

## What to expect on stage
- 30 seconds after a restart the screen finishes flooding and the systems start.
- The turbidity text says only "Clean" or "Needs cleaning". The water turns murky over about 3 seconds, and the text switches halfway.
- The filter warning shows about 2.5 seconds after F, once efficiency drops below 80%. Press F early to match your hardware.
- Flow rate drifts live inside 0.16 to 0.20 L/min and is identical on every device.
- Call service dials +91 98102 03440 on phones. Laptops show the number only.

## How devices stay in sync
Devices pass small messages through the free public relay ntfy.sh, so there is nothing to set up. It keeps recent messages for 12 hours, so a phone that joins late catches up. Anyone who knows the topic name inside the file could send messages to it, so keep the file's address to yourselves. If the venue network blocks ntfy.sh, each device still works on its own, just not in sync.

All values on screen come from these controls, not from sensors.
