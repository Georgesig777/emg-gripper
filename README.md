# EMG-Controlled Gripper

Real-time EMG signal processing on an STM32 (Nucleo-F446RE) to control a servo gripper.

## Status
Phase 1: Python filter prototype (in progress)

## Pipeline
raw EMG → band-pass → 50 Hz notch → rectify → moving RMS → control → servo

## Structure
- `python/`: filter design and offline validation on Ninapro DB2
- `firmware/`: STM32 C implementation
- `docs/`: engineering log and write-up

## Safety
Battery-powered sensor side only. No mains-connected equipment touches the electrodes.
