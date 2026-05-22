# INFECTED - Huddersfield 1984 Anarcho-Punk Archive

Official repository hosting the visual social documents, classified GCHQ leitmotif stills, and historical Luddite evidence files for the **DARK GENESIS EP** by THE INFECTED (Huddersfield, 1984).
Anarcho Punk. PEACEWORKS WHOLEFOOD CO op.

"He who controls the past controls the future. He who controls the present controls the past."
George Orwell 1984

---

## 📡 BROADCAST & TRANSMISSION LINKS
* **🎬 Video Manifest (Full EP)**: Available on YouTube at **Section 23** -> [@mojo-696](https://www.youtube.com/@mojo-696)
* **🎛️ Audio Archive (Master WAVs)**: High-fidelity master files are securely archived on Google Drive.

---

## 🎛️ AUTOMATED AUDIO RESTORATION & STEM ISOLATION PIPELINE

The audio assets for the **DARK GENESIS EP** were salvaged from raw 1984 mono archive recordings and processed using a custom Python digital signal processing (DSP) pipeline. This system circumvents corporate DAW automation to preserve the raw, physical dynamics of the West Riding anarcho-punk sound.

---

### 🎚️ STAGE 1: AI STEM ISOLATION (`seperate.py`)
To isolate the original frequencies and eliminate track bleed, the single-channel mono master was processed using an automated separation script:
* **Framework**: Built on Python, utilizing `torch` and advanced source-separation neural model weights.
* **Extraction Matrix**: The single track was mathematically deconstructed into four distinct, isolated layers: `drums.wav`, `bass.wav`, `vocals.wav`, and `other.wav` (containing the dual-guitar tracking).
* **Output Canvas**: Stems were saved as lossless, uncompressed linear PCM files forced into a strict **24-bit / 48kHz mono architecture** to ensure absolute phase lock upon timeline reconstruction.

---

### 🛠️ STAGE 2: PROCESS & RESTORATION ENGINE (`Run_EP_Restoration.py`)
Once isolated, the 24-bit stems were passed sequentially through a custom automated studio rack script executing three core mathematical DSP models:

#### 1. Surgical Butterworth Filtering (`studio_filter`)
Removes decades of analog tape degradation, environmental rumble, and high-frequency digital artifacts without coloring the mid-range punk frequencies.
* **Low-Pass/High-Pass**: High-order Butterworth filters roll off sub-bass distortion below 40Hz and clean up harsh high-end magnetic hiss.

#### 2. Valve Saturation Modeling (`valve_saturation`)
Injects the characteristic thickness and harmonic bite of a driven 1980s analog mixing console.
* **Mathematical Function**: Audio arrays are processed through a **hyperbolic tangent ($\tanh$)** transfer function.
* **Mix Blend**: Configured with a heavy **drive_db** threshold and a **0.8 blend ratio** (80% saturated tube clip mixed with 20% dry transient signal) for maximum punch.

#### 3. Asymmetric Tape Sheen (`tape_sheen`)
Simulates the high-frequency compression and saturation characteristic of a hot tape machine head.
* **Aesthetic Model**: Uses an asymmetric exponential curve set to an **intensity factor of 1.5** to restore high-end brilliance lost during the digital upsampling process.

---

### 📊 STAGE 3: TIMELINE RECONSTRUCTION & STREAMING TARGETS
The restored, phase-aligned stems were imported into the CapCut editor environment for final arrangement, video sync, and volume leveling.
* **Loudness Master Level**: Evaluated and locked precisely at **-14 LUFS**. 
* **Target Optimization**: Tailored explicitly for streaming platform normalization protocols (YouTube: **Section 23 // @mojo-696**) to guarantee full transient dynamics remain uncompressed and unthrottled.


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

