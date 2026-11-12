# OSTF Scale Editor v1.0

**Visual Scale, Key & Mode Editor for Max for Live**

OSTF Scale Editor is a free Max for Live MIDI device designed to make editing scales, keys, modes, and performance scale assignments in **Open Song Timeline Format (OSTF)** files easier, faster, and more intuitive.

Instead of manually editing complex OSTF parameters, users can select chords, explore compatible scales, compare alternatives, visualize musical relationships, and apply scale assignments directly to their songs.

The device supports a wide range of musical genres, including Jazz, Pop, Rock, Blues, R&B, House, Techno, Trance, and other electronic and contemporary music styles.

**The primary purpose is OSTF editing.** Music theory analysis and intelligent scale recommendations are provided as additional tools to support creative decisions, not replace them.

---

## Main Features

### Visual Scale Editing

- Edit scale assignments directly within OSTF songs.
- Select individual chords and assign scales.
- Work with song-wide, section-level, chord-level, and performance-related scale information.
- Visualize existing scale assignments across a song timeline.
- Review scale changes and musical context.
- Apply selected scales without manually editing OSTF text.

### Direct Scale Assignment

A straightforward editing workflow:

1. Open an OSTF song.
2. Select a chord from the timeline.
3. Choose a scale from the available candidates.
4. Click **SET SCALE**.
5. Save the updated OSTF file.

Manual scale selection is supported independently of automatic recommendations.

The editor includes protection for existing assignments and provides visual information about the selected editing range.

### Chord Scale Analysis

Explore scales in relation to the selected chord.

Features include:

- Chord-tone compatibility analysis
- Available tension information
- Scale-tone visualization
- Comparison of alternative scales
- Harmonic context analysis
- Chord-scale relationship explanations
- Identification of potentially conflicting notes

Useful for Jazz harmony, modal improvisation, and contemporary music production.

### Key & Mode Editing

Explore scales within the broader tonal context of a song.

- Analyze song-level tonal relationships.
- Compare scales against the current key.
- Explore major, minor, and modal options.
- Consider harmonic continuity across chord changes.
- Work with section-level tonal context.
- Support modal and non-functional harmonic approaches.

This is particularly useful for Pop, Rock, House, Techno, Trance, and other styles where maintaining a consistent tonal center can be more important than changing scales for every chord.

### Performance Scale Editing

Explore scales for musical performance and expression.

Supported concepts include:

- Melodic improvisation
- Lead phrases
- Riffs
- Blues-oriented performance scales
- Pentatonic approaches
- Modal playing
- Performance-oriented scale colors

Performance scale suggestions are distinguished from shared harmonic assignments where appropriate.

### Genre-Aware Scale Recommendations

OSTF Scale Editor considers the musical style when presenting scale alternatives.

Supported genre families include:

- Jazz
- Pop / J-Pop
- Rock
- Metal
- Blues
- R&B
- Hip-Hop
- House
- Techno
- Trance
- Ambient
- Reggae
- Electronic

Genre-aware recommendations help prioritize different approaches to harmony, modes, and performance.

Recommendations are intended as creative guidance. They do not represent absolute rules of music theory.

### Scale Comparison and Audition

Compare multiple scale candidates visually and musically.

- Side-by-side scale comparison
- Chord-tone and color-tone visualization
- Pitch-class comparison
- Keyboard visualization
- Musical-context comparison
- A/B audition support
- Genre-aware audition phrases

These tools help evaluate how different scales may affect the musical character of a passage.

### Scale Map Workspace

A visual workspace for understanding and managing scale assignments across an OSTF song.

- Timeline-based scale mapping
- Song, section, and chord context
- Existing assignment visualization
- Range-based scale editing
- Assignment inspection
- Editing guidance and warnings

### Automatic Scale Assignment

The **AUTO-SET SONG** function can generate scale assignments across a song using musical context and genre-aware recommendations.

Automatic assignment considers factors such as:

- Chord relationships
- Key and mode context
- Genre
- Harmonic continuity
- Existing scale assignments
- Potential conflicts

Manual editing remains available for situations where artistic preference differs from the recommendations.

### OSTF File Management

- Open OSTF files
- Save edited OSTF files
- Save As
- Undo / Redo
- OSTF text view
- Visual editing view
- Preserve unrelated song data wherever possible

The editor is designed to work with existing OSTF compositions rather than rebuild the song from scratch.

---

## How to Use

### 1. Load the Device

Place `OSTF_Scale_Editor_v1.0.amxd` on a MIDI track in Ableton Live.

The editor is designed to open in a separate window. The device view also provides an **Open** button.

### 2. Open an OSTF File

Click **Open** and select an OSTF song file.

The editor displays the song structure, chord timeline, and available scale information.

### 3. Select a Chord

Choose the chord you want to edit from the left-side timeline.

### 4. Choose a Scale

Review the available scales in the comparison area.

You can use the analysis and recommendation features as references or select a scale based on your own musical preference.

### 5. Apply the Scale

Click **SET SCALE** to assign the selected scale to the chosen chord.

For larger editing operations, use the Scale Map workspace and its range controls.

### 6. Save Your Changes

Use **Save** or **Save As** to export the edited OSTF song.

For important projects, keeping a backup of the original OSTF file is recommended.

---

## OSTF Compatibility

OSTF Scale Editor is designed for OSTF-based songwriting and arrangement workflows.

It can work alongside other OSTF devices, including:

- OSTF Composer
- OSTF Drum Arranger
- OSTF Bass Arranger
- OSTF Sequence Arranger
- OSTF Song Writer
- OSTF Editor
- OSTF Player

The device focuses on scale-related information while preserving other OSTF song data wherever possible.

Compatibility with newer OSTF versions may be limited to supported fields and operations. OSTF 4.2 content should be treated as read-only unless explicitly supported by the editor.

---

## Requirements

- Ableton Live with Max for Live
- A compatible Max environment
- Windows or macOS

Development and structural checks have been performed against the Max for Live device file. Full Ableton Live runtime verification has not been completed, and macOS compatibility has not been independently verified.

---

## Design Philosophy

OSTF Scale Editor follows three principles.

**1. Editing First**

The main purpose is to simplify and improve OSTF scale-data editing. Recommendations are secondary to direct user control.

**2. Musical Flexibility**

Different musical styles require different approaches to scale selection. Jazz chord-scale theory is useful, but it should not be imposed on every genre.

**3. Non-Destructive Workflow**

Scale editing should preserve existing compositions, notes, lyrics, tracks, and unrelated musical information whenever possible.

The goal is to make sophisticated OSTF editing accessible without sacrificing musical flexibility.

---

## Version History

### v1.0 — Initial Release

- Visual scale editor
- Chord Scale analysis
- Key & Mode editing
- Performance scale guidance
- Genre-aware recommendations
- Direct SET SCALE workflow
- Scale Map workspace
- Scale comparison and audition
- Automatic song-scale assignment
- OSTF file management
- Separate editor window

---

## Support Development

OSTF Scale Editor is developed and shared to support open music creation tools and the Open Song Timeline Format ecosystem.

If you find this device useful and would like to support continued development, you can buy me a coffee.

☕ **[Buy Me a Coffee — Yohsuke Nakano](https://buymeacoffee.com/yohsukenak)**

Your support helps encourage continued development, improvements, documentation, and new OSTF-compatible tools.

Contributions are entirely optional.

---

## Author

**Yohsuke Nakano**

GitHub: [yoh-nak](https://github.com/yoh-nak)

OSTF Scale Editor is part of the Open Song Timeline Format ecosystem.

Feedback, suggestions, and bug reports are welcome through GitHub Issues.

---

**OSTF Scale Editor v1.0 — Visual, flexible, and intuitive scale editing for Open Song Timeline Format.**
