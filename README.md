# Toastmasters-Pathways-JSON-Format
There are 11 educational directions in Toastmasters' proprietary training program called Pathways. Each direction is called a Path. There are 11 pathes in the plrogram, each path is composed of five levels, each level includes a variety of projects. We develop this JSON file to include all the level and projects for future usage.

## Recent additions

**October 2025 enhancement requirements** — The 6 current Pathways paths (Dynamic Leadership, Engaging Humor, Motivational Strategies, Persuasive Influence, Presentation Mastery, Visionary Communication) now include an `enhancements` object on each level. Enhancements apply to members who started or are completing levels after October 2025 (`"required_after": "2025-10"`) and specify required `meeting_roles` and `ed_series` (Educational Leadership series presentations) per level.

**Vintage paths** — Two legacy pre-Pathways programs are included with `"type": "vintage"`:
- *Basic Training for Toastmasters* — the original 12-speech manual program
- *Communication Series: Entertaining Speaker + Storytelling* — the Competent Communication + specialty manual track

