# PIO Breakfast — Project Context

## Current Project
Web app for ALJ's PIO Breakfast event (attendance, registration, scheduling).
- Stack: Vanilla HTML/CSS/JS, JSONBin API for data storage
- Colors: dark teal `#28424d`, blaze orange `#ed6b13`

---

## Saved References

### ppt-master
- Repo: https://github.com/hugohe3/ppt-master
- What it does: AI-powered tool (Python 3.10+) that converts any document (PDF, Word, images, text) into native editable PowerPoint files using Claude / GPT-4 / Gemini
- Key features:
  - Real DrawingML shapes (not flat images) — fully editable in PowerPoint
  - Supports custom PPTX templates (can embed ALJ branding)
  - Animations, transitions, speaker notes
  - Image generation via gpt-image-2
  - Runs locally — data stays on device

### Planned Use
Build a professional PPTX generator for ALJ work domains:
- Auto-generate event recap presentations from pio-breakfast data
- Potential domains: HR reports, event summaries, executive briefings
- Template idea: ALJ-branded PPTX with teal/orange color scheme
- Data source: JSONBin data from pio-breakfast → feed into ppt-master pipeline
