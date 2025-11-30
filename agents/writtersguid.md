# Writer's Guide for Curse of Strahd Campaign Expansion

1. Purpose
   - Provide ultra-detailed, step-by-step, read-aloud friendly material for an inexperienced, low-confidence DM.
   - Maintain strict fidelity to Curse of Strahd lore, tone, geography, NPC motivations, and timelines.

2. General Style
   1. All files are Markdown.
   2. Headings use numeric progression starting at 1 for top-level sections (e.g., `# 1. Title`, `## 1.1. Subtitle`, `### 1.1.1. Detail`).
   3. Voice is descriptive Gothic horror with moments of tragic humanity and rare dark humor.
   4. Keep rules text compatible with 5e and the printed Curse of Strahd book.

3. File Structure
   1. One file per location, chapter, adventure, or discrete adventure step.
   2. Files are organized chronologically and by expected character level progression.
   3. Each file contains, at minimum:
      - Narration blocks clearly labeled as **Read-Aloud**.
      - DM-only sidebars labeled **DM Note**.
      - Complete scripted NPC dialog.
      - Acting and voice notes for major NPCs and monsters.
      - Likely player questions/responses and suggested DM replies.
      - Encounters with enemy lists, stat references, and battlefield guidance.
      - Saving throws and skill checks with DC suggestions.
      - Loot and prices consistent with setting scarcity.
      - Campaign triggers and Strahd interaction hooks.
      - Roleplay prompts and intentional silence prompts.

4. Read-Aloud Conventions
   1. Mark all read-aloud text with a bold label, e.g.
      - `> **Read-Aloud:** The fog curls around your boots...`
   2. Use present tense, second person (“you”) for sensory immersion: sight, sound, smell, touch, taste.
   3. Avoid game jargon in read-aloud text (no “DC”, “hit points”, etc.).

5. Acting & NPCs
   1. For each important NPC, include a section:
      - **Personality at a Glance** (3–5 bullets).
      - **Voice & Mannerisms** (how to sound, posture, pacing).
      - **What They Want Right Now**.
      - **Secrets & Fears** (if relevant).
   2. Provide several sample dialog blocks for key scenes.
   3. For Strahd, ensure portrayals match the book: a proud, tragic tyrant, charismatic and cruel, treating the characters as playthings or would‑be champions.

6. Player Interaction & Prompts
   1. Every scene should offer multiple prompts:
      - Closed questions ("Do you step inside the house?").
      - Open questions ("What do you do?").
      - Exploratory hooks ("Who looks at the portraits? Who listens at the door?").
   2. Mark intentional silences:
      - `> **Silence Prompt:** Say nothing for 10–15 seconds and make eye contact. Let players speak first.`
   3. Anticipate likely player choices and give short branching notes.

7. Encounters & Checks
   1. For each encounter, specify:
      - Recommended party level.
      - Enemy list (names + where to find full stats in Monster Manual or CoS appendices).
      - Battlefield description, including terrain and verticality.
      - Trigger conditions and possible ways to avoid or defuse combat.
   2. For ability checks / saving throws, include:
      - Ability & DC (e.g., **DC 13 Wisdom (Perception) check**).
      - What success and failure mean narratively.

8. Loot, Prices & Economy
   1. Barovia is poor and grim; magic items are rare.
   2. Coin rewards are modest unless the book specifies otherwise.
   3. When adding items, respect tone: tarnished silver, religious icons, homemade charms, etc.
   4. When listing prices, use PHB/CoS baselines and note Barovia’s scarcity with a markup when appropriate.

9. Campaign Triggers & Optional Content
   1. Clearly label optional side quests as **Optional Adventure**.
   2. For each trigger, use a dedicated subheading, e.g., `### 2.3. Campaign Triggers`.
   3. Include Tarokka-dependent conditions, e.g.
      - `- If the **Mists** card was drawn for the Enemy**, then ...`
   4. Provide **Strahd Visit Options**: scripts for if Strahd appears now and if he does not.

10. Logging & Progress
   1. After writing new sections, update `agents/writter.md` with a dated log of what was produced or revised.
   2. Update `agents/progress.md` with:
      - Section identifier & title.
      - Status (Draft / Writer‑Revised / Completed).
   3. Do not alter the critique files of other roles.

11. Lore Fidelity
   1. Always cross‑check locations, names, relationships, and timelines with the markdown book files in `SourceMaterial/Curse of Stahd Book Markdown`.
   2. Do not contradict established canon from the book.
   3. Expansions should feel like extended director’s cuts of existing scenes, not rewrites of core events.
