# FreeSpace Academy 🛰️

### *Teach Space. For Free. For Real.*

![Version](https://img.shields.io/badge/version-1.0-blue)

---

<p align="center">
  <b>No Paywalls. Just Learning.</b><br>
  Immersive tools for understanding the space domain
</p>

---

## 🚀 Download ORCA Flyer

👉 **[Download ORCA Flyer v1.0 (Windows)](LINK_TO_RELEASE)**

> No installation required. Download → Extract → Run.

---

## 🎥 What is this?

**ORCA Flyer v1.0** is part of the **ORCA Suite**, developed under **FreeSpace Academy (FSA)**.

It allows you to:

* Visualize thousands of satellites in real time
* Explore Earth orbit, cislunar space, and Lagrange points
* Analyze what’s overhead from any location on Earth
* Experience the space domain in an intuitive, interactive way

<!-- Add GIF here later -->

<!-- ![ORCA Demo](your-gif-link.gif) -->

---

## 🧩 The ORCA Suite (Expanding)

FreeSpace Academy is building a full ecosystem of tools:

* 🛰️ **ORCA Flyer** – Domain awareness & visualization *(this repo)*
* 🧠 **ORCA Designer** – Constellation builder *(coming to GitHub)*
* 🔴 **ORCA Red** – Adversary simulation *(coming soon)*
* 📐 **ORCA Orbital Mechanics (OM)** – Fundamentals visualizer *(coming soon)*

---

## ⚡ Quick Start

1. Download ORCA Flyer
2. Extract the `.zip`
3. Run the `.exe`
4. Explore space

---

---

# 🛰️ ORCA FLYER TECHNICAL DOCUMENTATION

*(Detailed reference below)*

---

# orca-flyer

# ORCA Flyer – 3D satellite ride-along viewer for visualizing Earth orbit.

ORCA FLYER v1.0
"Orbital Flyer" Edition
=======================

```
                Real-Time 3D Satellite Visualization
          Copyright (c) 2025-2026 Cameron Cunningham
                     All Rights Reserved
```

================================================================================
INTRODUCTION
============

ORCA Flyer v1.0 is a comprehensive 3D satellite tracking and visualization
application built with Python and Panda3D. It provides real-time visualization
of Earth-orbiting satellites, cislunar spacecraft, and Lagrange point missions.

ORCA Flyer v1.0 is part of the ORCA Suite — the core toolset of FreeSpace Academy.

================================================================================
FEATURES
========

SATELLITE TRACKING

* Real-time TLE-based tracking for 12,000+ Earth satellites
* SPICE ephemeris integration for cislunar spacecraft
* Lagrange point spacecraft visualization (Sun-L1, Sun-L2, Moon-L1, Moon-L2)
* Country and constellation filtering
* Searchable satellite database

VISUALIZATION

* Dynamic 3D Earth with realistic textures
* Moon position and phase rendering
* Sun position with atmospheric glow effects
* Orbital regime color coding (LEO, MEO, GEO, HEO)
* Satellite "baseball card" information panels
* Country flags for satellite attribution

LOCATION ANALYSIS

* "What's Overhead?" analysis for any location on Earth
* 40 pre-loaded major world cities
* Manual latitude/longitude input
* Elevation, azimuth, and distance calculations
* Export analysis results to text file

NAVIGATION

* WASD + mouse camera controls
* Xbox controller support
* Edge indicators for off-screen celestial objects
* Save/load camera view states

================================================================================
CONTROLS
========

KEYBOARD:
W/A/S/D     - Move camera forward/left/back/right
Q/E         - Roll camera
Arrow Keys  - Look around
Scroll      - Zoom in/out
Space       - Play/Pause time
Shift       - Cycle simulation speed
F           - Focus search box
H           - Toggle controls guide
L           - Toggle location panel
Escape      - Close dialogs

MOUSE:
Left Click  - Select satellite
Scroll      - Zoom

XBOX CONTROLLER:
Left Stick  - Move camera
Right Stick - Look around
Triggers    - Zoom in/out
A Button    - Select
B Button    - Deselect
Start       - Toggle play/pause

================================================================================
DATA SOURCES
============

TLE DATA:

* CelesTrak (celestrak.org)
* Space-Track (space-track.org)

EPHEMERIS:

* NASA NAIF SPICE kernels
* JPL planetary ephemerides

TEXTURES:

* NASA Visible Earth
* Solar System Scope

================================================================================
REQUIREMENTS
============

SYSTEM REQUIREMENTS:

* Windows 10 or later
* Dedicated GPU recommended
* Xbox controller optional

================================================================================
CREDITS
=======

DEVELOPMENT:
Cameron Cunningham - Lead Developer

SPECIAL THANKS:

* Anthropic Claude - Development assistance
* NASA/JPL - SPICE toolkit and ephemeris data
* CelesTrak - TLE data services
* Panda3D community - Engine and support

================================================================================
CONTACT
=======

For non-urgent questions or educational use inquiries, you may contact the
author at: [orca.flyer.contact@gmail.com](mailto:orca.flyer.contact@gmail.com)

Response is not guaranteed.

================================================================================
VERSION HISTORY
===============

v1.0 (2026)

* Official v1.0 release of ORCA Flyer
* First stable public GitHub distribution
* Integrated into FreeSpace Academy ecosystem
* Branding and documentation overhaul
* Foundation for ORCA Suite expansion

v0.9.1 (2026)

* Updated branding to ORCA Flyer
* Preparation for public GitHub distribution

v0.9.0 (2026) - "Orbital Flyer" Edition

* Initial public release
* Real-time satellite tracking
* Cislunar spacecraft visualization
* Location overhead analysis
* Xbox controller support
* Edge indicators for celestial objects

================================================================================
