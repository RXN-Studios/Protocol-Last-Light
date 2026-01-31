# State Machine & Atmosphere Logic

[cite_start]The game transitions between two primary states that dictate both the backend logic and the sensory experience[cite: 273, 274].


### 🏠 STATE: HOME (Safe Zone)
* [cite_start]**Visuals:** Warm colors and steady lighting[cite: 279].
* [cite_start]**Logic:** Oxygen regenerates, and Fuel consumption is monitored via the UI[cite: 280].
* [cite_start]**Audio:** Soft ambient synth[cite: 299].

### 🌑 STATE: AWAY (Danger Zone)
* [cite_start]**Visuals:** Desaturated colors with vignette edges and "Corrosion" particles[cite: 282].
* [cite_start]**Logic:** Oxygen depletes; the depletion rate increases the further the player travels from (0,0)[cite: 283, 284].
* [cite_start]**Audio:** Oppressive low-frequency hums and rhythmic thumping[cite: 283, 299].

### 📉 The "Dread" Variable
A hidden variable that tracks time spent in the dark. High Dread causes:
* [cite_start]Sluggish movement[cite: 298].
* [cite_start]UI flickering[cite: 298].
* [cite_start]Audio whispers and heartbeat sounds[cite: 289, 300].
