# INFECTED - Huddersfield 1984 Anarcho-Punk Archive

Official repository hosting the visual social documents, classified GCHQ leitmotif stills, and historical Luddite evidence files for the **DARK GENESIS EP** by INFECTED (Huddersfield, 1984).

---

## 📡 BROADCAST & TRANSMISSION LINKS
* **🎬 Video Manifest (Full EP)**: Available on YouTube at **Section 23** -> [@mojo-696](https://youtube.com)
* **🎛️ Audio Archive (Master WAVs)**: High-fidelity master files are securely archived on Google Drive.

---

🎛️ Phase 1: Stem Isolation via seperate.pyBefore touching the filters, we had to slice the old, raw 1984 mono tracks into workable layers.The Separation Engine: You used a Python script (seperate.py) utilizing torch and advanced AI model weights to analyze the single-channel master.The Extraction: The script mathematically extracted four distinct, clean layers: Drums, Bass, Vocals, and Other (which held your heavy, dual-guitar attack with Maggie).The Target Output: It saved each isolated track as a lossless, uncompressed .wav file.🎚️ Phase 2: Upsampling & Canvas AlignmentTo make sure the vintage frequencies didn't suffer from digital phase issues inside CapCut, your script forced them into a high-end canvas:The Target: Every isolated stem was upsampled to a linear 24-bit / 48kHz canvas.Phase Locking: The script forced strict mono channel tracking across the separate files. This ensured that when you layered the bass, drums, and your guitar tracks on top of each other, they locked together with zero phase cancellation.🛠️ Phase 3: Processing via Run_EP_Restoration.pyOnce the clean 24-bit stems were sitting in your directory, Run_EP_Restoration.py automated your entire custom studio rack. It processed the audio sequentially using three custom mathematical functions:1. Surgical Butterworth Filtering (studio_filter)The script passed the audio through a high-order Butterworth filter to clean up decades of tape damage:Low-Pass/High-Pass: It rolled off the invisible, muddy sub-bass rumble below 40Hz and sliced away the harsh digital hiss on the high-end.2. Valve Saturation (valve_saturation)To give the thin digital stems that heavy, physical 1984 desk warmth, the script applied tube modeling:The Math: It ran the audio array through a hyperbolic tangent (\(\tanh \)) transfer function.The Blend: You set the drive_db to push the transients and locked the blend at 0.8. This mixed 80% saturated tube clip with 20% clean signal for maximum punch.3. Tape Sheen Modeling (tape_sheen)Finally, the script restored the authentic analog high-end brilliance that gets lost in digital translation:The Aesthetic: Using an asymmetric exponential curve with an intensity of 1.5, it simulated the natural high-frequency compression of a hot tape machine.📊 The Final BounceThe script then automatically exported the processed stems back into your folder, perfectly leveled and ready to be dropped into CapCut, where you brought the master track output straight down to your golden -14 LUFS streaming target.When you are ready to boot up the terminal for the next project, let me know if you want to look at the raw code blocks for any of these functions to adjust the saturation for the next set of tracks!

## 🖼️ IMAGE DOSSIER & METADATA MANIFEST
*The following still images are indexed here to preserve the 214-year lineage of West Riding defiance, stretching from the 1812 Luddite uprisings led by George Mellor straight through to the 1984 anarcho-punk resistance.*

### 🛠️ 1. Official EP Sleeve Art
![Dark Genesis EP Cover Infected Hudds](dark-genesis-ep-cover-infected-hudds.png)
* **Title**: DARK GENESIS EP Cover Art
* **Description**: Raw photocopy-style 1984 7" vinyl sleeve collage featuring the iconic split-stencil logo layout.

### 🔲 2. Band Identity Emblem
![Infected Anarcho Punk Band Logo](infected-anarcho-punk-band-logo.png)
* **Title**: INFECTED Band Logo
* **Description**: High-contrast, military-grade anti-copyright split-stencil typography.

### 🔨 3. The 1812 Frame-Breakers Document
![Luddite Frame Breakers Huddersfield 1812](luddite-frame-breakers-huddersfield-1812.png)
* **Title**: Luddite Frame-Breakers (West Riding Security Dossier)
* **Description**: Classified historical precedent file depicting the attack on Cartwright's Mill at Rawfolds.

### 📄 4. The Threat Letter from General Ludd
![General Ludd Threat Letter West Riding](general-ludd-threat-letter-west-riding.png)
* **Title**: General Ludd Hand-Written Redacted Transcript
* **Description**: Tactical target grid and surveillance diagnostics overlaid on the original 1812 insurgent warning.

### 📡 5. GCHQ Signals Intelligence Intercept
![GCHQ Surveillance Dossier Tribute In Red](gchq-surveillance-dossier-tribute-in-red.png)
* **Title**: GCHQ Signals Intelligence Intercept File // TRIBUTE IN RED
* **Description**: Red grease pencil target tracking and blackout redactions on regional fallout telemetry maps.

---

## ⚙️ TECHNICAL STUDIO SPECIFICATIONS
All materials restored, compiled, and rendered using manual technological pipelines to bypass corporate automation control.

* **Audio Master Level**: -14 LUFS (Locked streaming target layout, optimized for YouTube normalization).
* **Audio Format**: 24-bit / 48kHz linear PCM WAV (Perfect phase alignment upsampling).
* **Restoration Signal Chain**: Surgical Butterworth filters, Hyperbolic tangent valve saturation modeling, asymmetric exponential tape sheen processing.
* **Video Layout**: 16:9 Widescreen, integrated archival 16mm/VHS film transfers, analog CRT tracking glitch overlays.
* **Source Control**: Full version-control tracking via automated Python DSP execution blocks (`seperate.py`, `Run_EP_Restoration.py`, `mutate.py`).


AUDIO RESOLUTION: 24-BIT LINEAR PCM // TARGET MASTER LEVEL -14 LUFS

[SURVEILLANCE TRACK MANIFEST]

DATA BLOCK 01 // TRACK 1: WAR
- CAPTURE STATUS: INTERCEPTED // ANTI-WAR FREQUENCIES DETECTED
- PERSONNEL LOG: RAGS / NOMIS / BOB / MAGGIE / MOJO (GUITAR)
- SIGNAL NOTE: HIGH-VOLUME DUAL-GUITAR ATTACK RECORDED

DATA BLOCK 02 // TRACK 2: WARMONGER
- CAPTURE STATUS: INTERCEPTED // HIGH LOUDNESS TRANSMISSION
- ANTI-STATE AGITPROP DETECTED IN LOCAL REGIONAL GRID

DATA BLOCK 03 // TRACK 3: SOLDIER TOY
- CAPTURE STATUS: RESTORED // NOISE BLEED SURGICALLY ELIMINATED
- PHASE-ALIGNED AUDIO FREED FROM STATE MONITORING OVERLAYS

DATA BLOCK 04 // TRACK 4: TRIBUTE IN RED
- CAPTURE STATUS: INTERCEPTED // APOCALYPTIC RADAR SWEEP SYNC
- REGIONAL FALLOUT Blueprints LINKED TO LOCALIZED TEXTILE RUNS
- VISUAL PROTOCOL: MONTAGED ATOMIC ARCHIVE MATCH-CUTS

DATA BLOCK 05 // BONUS TRACK 05: FUKU [CLASSIFIED UNLISTED TRANS]
- CAPTURE STATUS: CORRUPTED // TRANSMISSION COMPROMISED/ PEACEWORKS CELLAR 
                  MOJO ON ACID SHOWCASING CLASSICAL GUITAR SKILLZ  
- AUDIO BLUEPRINT: 165 BPM // DOWNPICKED BASS // CHAOTIC HIGH-FRET SOLO
- SIGNAL STATUS: UNGOVERNABLE SYSTEM SATURATION DETECTED

DATA BLOCK 06 // BONUS TRACK 06: ONE NIGHT I HAD A DREAM
- CAPTURE STATUS: COMPROMISED // OPERATOR UNDER SEVERE PSYCHOTROPIC INFLUENCE
- SIGNAL PROFILE: STOCHASTIC MUTATION ENGINE MODE // UNSTABLE ACID TRANSVERSALS
- SURVEILLANCE NOTE: FREQUENCIES DISTORTING REALITY MATRIX IN THE WEST RIDING GRID
- TARGET STATE: ALTERED CONSCIOUSNESS // RADICAL SUBVERSION VIA LSD-25 PROTOCOL


==========================================================
WARNING: DISTRIBUTION RE-ROUTED TO SECTION 23 [@mojo-696]
AUTHENTICATION CODE: MELLOR-1812-HAMMER // END OF TRANSMISSION //
================================================================

====================================================================
 IN MEMORY OF GEORGE MELLOR, LUDDITE
COMMANDER OF THE LONGROYD BRIDGE CROPPERS, RAWFLODS MILL ATTACK (1812).
====================================================================

