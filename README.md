🛰️ AG-SADS v1.0
Aviation GPS Spoofing Awareness & Defense Simulator

By Dybbuk Research — Cyber-Physical Security

📌 Overview

AG-SADS (Aviation GNSS Spoofing Awareness & Defense Simulator) is a browser-based, multi-module educational platform that demonstrates how GPS spoofing attacks impact aircraft navigation, airport operations, and airspace safety.

This project is entirely safe, client-side, and designed purely for:

Cybersecurity students

SOC analysts and threat intelligence teams

Aviation researchers

Awareness & training programs

Portfolio demonstration

AG-SADS does not transmit RF, interact with real aircraft, GNSS receivers, or any real avionics.
All simulations run locally in the browser.

🎯 Objective

Modern aircraft rely heavily on GNSS/GPS for:

Navigation

Positioning

Landing approach

Altitude reference

This makes aviation vulnerable to GPS spoofing—a cyber-physical attack where false signals manipulate a receiver’s position.

AG-SADS helps learners understand:

How spoofing attacks are simulated

What anomalies appear in data

How aircraft drift looks visually

How 3D models represent deviation

How SOC teams detect signal tampering


🧩 Included Modules
1. Live GPS Tracker (Simulator)

Visual comparison of:

True vs. spoofed flight paths

Map-based drift animations

Real-time coordinate changes

Useful for demonstrating how spoofing alters navigation during flight.

2. Anomaly Detection Engine

Mathematical detection of:

Signal drift

Euclidean distance errors

Impossible jumps

Unrealistic heading shifts

Time drift patterns

Helps SOC analysts understand spoofing indicators.

3. Spoof Control Panel (Attack Simulation)

Safe and local-only spoof injection simulator:

Offset latitude/longitude

Modify altitude values

Simulate high drift / low drift

Manipulate speed & course

⚠️ Purely educational — no interaction with real GNSS hardware.

4. 3D Flight Model (Three.js Visualization)

A 3D aircraft model showing:

Real-time movement

Path deviation due to spoofing

Height/altitude variations

Rotational & directional changes

Helps visualize spatial impact of spoofing in airspace.

5. Algorithmic Spoof Detector

Custom logic detecting:

Path inconsistencies

Heading variance

Sudden GPS jumps

Nonlinear movement patterns

6. Machine Learning Spoof Detector

(Upcoming module)

Uses ML techniques to classify:

Legitimate navigation

Spoofed navigation sequences

Time-series anomalies

7. Training & Threat Intelligence Hub

Includes:

GNSS spoofing basics

Real-world aviation incidents

Mitigation strategies

Air traffic safety guidance

SOC reporting templates
