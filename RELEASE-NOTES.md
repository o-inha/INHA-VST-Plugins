# RELEASE NOTES

## 2026-11-06 / Latest

### INHA Tear v1.4.10
- New cleaner layout / UI.
- FREEZE performance and accuracy improved.
- Improvements to very-long freezes.
  > Very-long freezes now use a longer audio segment as initial input, and will slowly update the stretched output audio indefinitely with new audio from the dry signal. This will result in a bit evolving and more natural sounding very-long stretch events.
- Sidechain support to trigger stretch events by transients from another track.
- OFFSET slider: slightly delays the start of all stretch events.
  > Sounds great for beats and such.

### INHA Stutter v2.0.6
- New trigger: transients.
- Sidechain support to trigger stutters by transients from another track.
- HOLD range knob
  > play N% of stutter, and silence for the rest of the stutter-time.
- Stutter and BEAT GUARD accuracy improvements.

### INHA Ryoji v1.4.1
- Audification improvements (phase rotation, crazy-peak reduction, etc.)

---

### Earlier:

<details>
<summary>2026-10-20</summary>

### ALL INHA PLUGINS
- Gear icon at bottom left to access plugin settings.
- Setting: DARK / LIGHT theme toggle.
- Setting: ZOOM / plugin size.
- Default zoom is now the bigger one.
- Both theme and zoom are saved globally for all past and future instances per plugin.

### INHA Ryoji v1.3.4
- Audification performance.
  > Data audification is now much faster. Selecting columns for left and right channel now works near real-time (no data re-analysis).
- SCRUB mode
  > freeze audio segment under the playhead for WSOLA-style control of speed and direction without affecting pitch or sounding very grainy.
- ADSR are now range sliders.
- Link A & R in GRANULATE mode for less tedious adjusting.
- New slider: Data-audified sample stereo width and balance.
- Toggle DENSITY between single value or range.
  > Range-value will pick a random value within range for each MIDI note, as before. Single-value mode will change DENSITY in real-time (MIDI notes are ignored).
- Small visual/UI bugfixes.
- Change DRAG EXPORTS locations in plugin settings.
  > Global and project-specific save location. All DAWs don't expose a *project location*; in these DAWs the second location will be plugin instance-specific.
</details>

<details>
<summary>2026-09-15</summary>

### INHA Ryoji v1.0.16
- Support for more audio formats:
  - WAV
  - AIFF
  - AIFF-C
  - MP3
  - AAC
  - FLAC
  - WMA
- Audio extraction from supported video formats:
  - MP4
  - M4V
  - MOV
  - AVI
  - WMV
  - 3GP
- Bugfix: Drag & drop didn't work correctly when plugin was in FL Studio's Channel Rack. Issue is fixed.
</details>

<details>
<summary>2026-09-07</summary>

### INHA Tear v1.2.5
- New trigger mode: ❄️ FREEZE
  > will stretch audio indefinitely when pressed/automated. Overrides any other stretch events for the duration of being applied.
- New feature: auto-mute dry signal for the duration of a stretch event.
  > Toggle by 🄰 button next to DRY knob label.
- DUCK (wet ducks dry) is now much more sensitive.
- Updates to factory presets.

### INHA Stutter v1.1.22
- Toggle triplet divisions separately for GRAIN and LENGTH.
  > The global 🅃 button from plugin header has been replaced by separate 🅃 buttons next to GRAIN and LENGTH knob labels.
- BEAT GUARD technical finetuning.

### INHA Dropout v1.0.3
- SYNC and SYNC / T (toggle triplet divisions) added.
  > synchronizes plugin to DAW tempo.
</details>
