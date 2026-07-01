# SIREN: Detecting When a Sensor Is Quietly Failing, Without Being Told

This repository contains the paper *SIREN*, presented at the Artificial Intelligence National Summit (AINS 4.0).

## Abstract

Modern multimodal systems rely on multiple sensors (camera, audio, motion, etc.) to make decisions. However, sensors can fail silently: they continue producing outputs that look valid but are no longer meaningful.  

This paper introduces **SIREN**, a lightweight method to detect such failures without requiring explicit failure labels or missing-sensor indicators. It evaluates each sensor using three independent signals: cross-sensor agreement, temporal consistency, and standalone plausibility.

A sensor is trusted only if it passes all three checks, enabling more robust fusion and safer behavior under uncertainty.

## Authors

- El Jazi Amal  
- Guirat Eya  

ESPRIT

## Presentation

Presented at: **Artificial Intelligence National Summit (AINS 4.0)**

