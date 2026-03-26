# RECORD

A consolidated technical record covering design principles, development approach, version history, and planned work for *Lanterns Trail*.

---

## 1. Design Style

### Tone & Experience
- Quiet, exploratory movement; no urgency or failure states  
- Light responds to motion, and motion responds to light  
- Emotional rhythm built around wandering, discovery, and gentle illumination  
- The lantern acts as a companion rather than a tool  

### Visual & Audio Direction
- Soft, reactive lighting tied to player movement  
- Trails of light that linger briefly  
- Environmental elements that brighten or dim in response  
- Subtle audio cues linked to footsteps, illumination, or stillness  

### Interaction Model
- One path, one lantern, one relationship  
- Movement is expressive, not pressured  
- Player learns through motion and observation  
- Mechanics remain natural, unforced, and lightly responsive  

---

## 2. Development Process

### Repository Layout
- `game/` for scenes, logic, and GDevelop project files  
- `assets/` for sprites, audio, and visual elements  
- `builds/` for exported builds  
- `export/` for temporary GDevelop exports  
- `docs/` for internal notes and placeholders  

### Workflow Principles
- Slow, intentional development pace  
- Atmosphere and motion–light relationship take precedence over complexity  
- Early mechanics validated before expanding scope  
- All additions must preserve the quiet, responsive tone  

### Core Systems
- Lantern glow behaviour (brightness, colour, reach)  
- Light trails influenced by speed and direction  
- Ambient audio tied to movement and illumination  
- Environmental reactivity to motion  

---

## 3. Milestones

### Initial Setup
- Repository structure created  
- Minimal `.gitignore` added  
- Base folders for scenes, assets, and documentation established  
- Core idea of movement and light defined  

### Early Implementation
- Drafted lantern glow behaviour  
- Began exploring light trails and environmental response  
- Added early audio cues  
- Validated movement‑driven interaction model  

### Documentation
- Initial design notes compiled  
- Development log started  
- Roadmap drafted to guide early versions  

---

## 4. Version History

### Unreleased
- Project structure created  
- Initial documentation placeholders added  
- Early design constraints and tone definitions drafted  
- Exploratory mechanics (lantern glow, light trails) begun  
- Intentional, calm workflow established  

(Versioning begins at first playable prototype.)

---

## 5. Roadmap

### v0.1.0 — Prototype
- Implement stable lantern glow system  
- Add basic light trails tied to movement  
- Introduce ambient audio  
- Validate movement‑driven interaction model  
- Prepare first exportable build  

### v0.2.0 — Atmosphere Pass
- Refine glow behaviour and trail persistence  
- Add minimal environmental reactivity  
- Improve palette and lighting consistency  
- Explore optional expressive interactions  

### v1.0.0 — First Release
- Finalise core mechanic and tone  
- Add optional features (lantern types, subtle puzzles, colour shifts)  
- Ensure stable performance and deterministic behaviour  
- Document final architecture and constraints  
