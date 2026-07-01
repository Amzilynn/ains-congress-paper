SIREN: Detecting When a Sensor Is Quietly Failing, Without Being Told

This repository contains the research paper SIREN, presented at the Artificial Intelligence National Summit (AINS 4.0).

📄 Paper Overview

Modern multimodal systems rely on multiple sensors (camera, audio, motion, etc.) to make decisions.
However, a major challenge arises when a sensor fails silently—it continues producing data that looks valid but is actually unreliable.

This paper introduces SIREN, a method designed to detect such silent failures without requiring explicit failure labels or missing-sensor indicators.

*Key Idea

SIREN evaluates each sensor using three independent reliability signals:

Cross-sensor consistency: Does the sensor agree with the others?
Temporal consistency: Does it remain consistent with its own recent history?
Plausibility check: Does the signal look normal for that sensor?

A sensor is trusted only if it passes all three checks. Otherwise, it is down-weighted or replaced during fusion.

* Core Contributions
Detecting silent sensor failures without any missing-data flags
A three-check reliability framework for robust sensor evaluation
A safe fusion mechanism that adapts to unreliable inputs
A collapse detection + abstention strategy when the system becomes uncertain

*Motivation

In real-world environments, sensors often degrade without clear failure signals:

A camera may still stream but in darkness
A microphone may capture only background noise
A motion sensor may freeze at a constant value

SIREN addresses these cases by focusing on behavioral reliability rather than explicit failure detection.

📌 Authors
El Jazi Amal
Guirat Eya


📍 Venue

Presented at: Artificial Intelligence National Summit (AINS 4.0)

