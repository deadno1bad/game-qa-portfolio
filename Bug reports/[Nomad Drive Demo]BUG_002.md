# Bug Report

## Title
> [UI][Interaction][Highlight] Engine particle effects are highlighted together with the engine

---

## Environment

**Game:**
> Nomad Drive Demo

**Game Version / Build:**
> v1.3

**Platform:**
Steam
**Operating System:**
Windows 11
**Game Mode:**
Singleplayer
**Language:**
>RUS
## Preconditions
- Engine is installed in the vehicle
- Engine is running
- Engine temperature is high enough for particle effects to appear

## Steps to Reproduce

1. Install the engine.
2. Start the engine.
3. Increase the engine temperature until particle effects appear.
4. Aim the crosshair at the engine.
5. Observe the interaction outline.

---

## Expected Result

Only the engine mesh should receive the interaction outline.
Particle effects should not be highlighted.

---

## Actual Result

The interaction outline is applied to both the engine mesh and its particle effects.
---
## Reproducibility
Always (100%)
## Severity
Low
---
## Priority
P4 – Low
---
## Category
Graphics / Visual
---
## Attachments
<img width="1280" height="721" alt="image" src="https://github.com/user-attachments/assets/4cd3186d-4081-4e42-ab1a-38e48295a438" />

