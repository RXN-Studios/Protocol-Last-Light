# State Machine & Atmosphere Logic

The game transitions between two primary states that dictate both the backend logic and the sensory experience.


### 🏠 STATE: HOME (Safe Zone)
* **Visuals:** Warm colors and steady lighting.
* **Logic:** Oxygen regenerates, and Fuel consumption is monitored via the UI.
* **Audio:** Soft ambient synth.

### 🌑 STATE: AWAY (Danger Zone)
* **Visuals:** Desaturated colors with vignette edges and "Corrosion" particles.
* **Logic:** Oxygen depletes; the depletion rate increases the further the player travels from (0,0).
* **Audio:** Oppressive low-frequency hums and rhythmic thumping.

### 📉 The "Dread" Variable
A hidden variable that tracks time spent in the dark. High Dread causes:
* Sluggish movement.
* UI flickering.
* Audio whispers and heartbeat sounds.
