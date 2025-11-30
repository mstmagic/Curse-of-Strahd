# Writer's Guide

This guide defines how all written campaign files in `01-Campaign` should be structured and presented so that a brand new, inexperienced Dungeon Master can run Curse of Strahd by reading verbatim.

## 1. Overall Principles

1. The DM is assumed to be:
   - New to D&D and to Curse of Strahd.
   - A weak or shy actor.
   - Reliant on the text in front of them.

2. Therefore, **every file must be runnable as a script**:
   - Clearly separate *DM-facing instructions* from *spoken narration and dialogue*.
   - Provide pronunciation notes for unusual names when they first appear.
   - Include emotion, tone, and pacing guidance.

3. **Lore accuracy is mandatory**:
   - Always cross-check significant details with the source markdown files in `SourceMaterial/Curse of Stahd Book Markdown/`.
   - Never contradict the book’s locations, NPCs, or timeline.
   - You may elaborate (background, scenes, optional adventures), but not retcon core lore.

4. **Horror tone**:
   - Maintain a Gothic horror feel: dread, melancholy, beauty mixed with decay.
   - Use all five senses in descriptions.
   - Let hope exist, but it should feel fragile.

5. **Extremely explicit guidance**:
   - Assume the DM does not improvise well.
   - Every important moment must have example lines to read or lightly adapt.
   - Keep the language simple and direct when addressing the DM.

## 2. File Naming and Scope

1. Each file in `01-Campaign` should cover **one clear playable unit**:
   - A location (e.g. "Village of Barovia – Town Square").
   - A chapter-level segment (e.g. "Into the Mists – Road to the Gates").
   - An adventure stage/step (e.g. "Death House – Basement Ritual Climax Part 1").

2. Files must be in **chronological and level-appropriate order**.

3. If a file grows too long to be practical at the table:
   - Split into parts and mark them clearly with a numeric suffix, e.g.:
     - `08-Death-House-Basement-and-Ritual-Chamber-Part-1.md`
     - `09-Death-House-Basement-and-Ritual-Chamber-Part-2.md`

4. Filenames format:
   - `NN-Short-Descriptive-Title.md` where `NN` is a zero-padded sequence number.

## 3. Internal Document Structure

All campaign files should broadly follow this structure (numbered headings):

1. **Overview and DM Briefing**
   - High-level purpose of this file.
   - Where it sits in the campaign timeline.
   - Expected party level, difficulty notes, and any required prep.

2. **Scene List / Flowchart**
   - Bullet list of the scenes in this file in order.
   - Mark which are *Required* vs *Optional*.
   - Note obvious decision points and branches.

3. **Scenes (One Subsection per Scene)**
   - Each scene gets its own numbered subsection: `3.1`, `3.2`, etc.
   - Within each scene, maintain the following micro-structure:

     3.x.1 **Scene Setup (DM Only)**  
     - Brief DM summary: where the scene starts, what the players probably did just before it.  
     - State of the world/NPCs when the scene begins.  

     3.x.2 **Read-Aloud Narration**  
     - Boxed-style text (markdown blockquotes) for the DM to read verbatim or nearly verbatim.  
     - Use present tense, second person ("you") directed at players.

     3.x.3 **NPCs in This Scene**  
     - For each NPC, include:
       - Name (with pronunciation).
       - Role in the story.
       - **How to voice them** (pitch, tempo, accent suggestions).
       - **How to act them** (posture, gestures, eye contact, tics).
       - 3–8 sample **dialogue snippets** that can be dropped into conversation.

     3.x.4 **Player Interaction Prompts**  
     - Several open and closed questions the DM can ask.  
     - Always include variations of **"What do you do?"**.  
     - Label a few **Silence Prompts**: instructed pauses for the DM to simply look around the table and wait.

     3.x.5 **Likely Player Choices and DM Responses**  
     - Bullet list of common actions and how the world responds.  
     - Provide short scripts the DM can read when responding.  
     - Note which responses trigger checks, saving throws, or combat.

     3.x.6 **Checks, Saving Throws, and Consequences**  
     - List all expected checks with DCs where appropriate.  
     - Clearly distinguish: ability checks, skill checks, saving throws.  
     - Describe the consequences of success and failure in concrete terms.

     3.x.7 **Encounters and Battlefield Layout**  
     - List all monsters/NPCs: quantity, stat block references, and roles.  
     - Provide a clear, theatre-of-the-mind battlefield description **and** optional grid notes when helpful.  
     - Include opening lines for the DM when combat starts.  

     3.x.8 **Loot and Rewards**  
     - List gold, items, and unique treasures, with book page or section references when possible.  
     - Include **prices** when relevant (especially in towns/markets).  

     3.x.9 **Campaign Triggers & Strahd Hooks**  
     - Note which campaign flags change here.  
     - Any Tarokka-related triggers (e.g. location of sunsword, symbol, tome).  
     - Any **Strahd interaction opportunities** (see section 5 below).

4. **Safety Valves and Difficulty Adjustments**
   - Since the DM and players may be inexperienced, each file should end with a short subsection that explains:  
     - How to **scale encounters up or down**.  
     - Non-lethal failure options or escape valves.  
     - Suggestions for how to narrate near-TPK situations without undermining horror.

## 4. Style of Narration and Dialogue

1. **Narration**:
   - Use evocative but clear language.
   - Frequent sensory details: what they see, hear, smell, feel (temperature, textures), sometimes taste.
   - Avoid purple prose that would be hard for a nervous DM to read aloud.

2. **Dialogue**:
   - Write in natural, conversational lines.
   - Include emotional beats: hesitation, bitterness, sly amusement, etc.
   - For important NPCs, provide **mini monologues** and several short responses.

3. **Acting Notes**:
   - Give the DM **simple physical cues**:  
     - "Look down at your hands as you speak."  
     - "Clasp your hands as though in prayer."  
     - "Lean back slightly and half-smile."  
   - Keep instructions short and easy to remember.

4. **Prompts and Silence**:
   - Every scene needs at least 3–5 explicit **prompts**.  
   - Mark at least one **Silence Prompt** per major scene:  
     - Example: *[Silence Prompt: Look at each player in turn, then quietly ask, "Who steps forward first?"]*

## 5. Strahd Interactions

Strahd is the heart of the campaign. The DM should have **many optional chances** to bring him on stage without breaking the book’s structure.

1. **Types of Interactions**:
   - **Distant Observation**: bats on the ceiling, wolves behaving strangely, carriage wheels in the dark.  
   - **Illusory / Dream Visits**: Strahd in dreams or reflections.  
   - **Direct Social Encounters**: polite conversations, invitations, veiled threats.  
   - **Overt Displays of Power**: commanding wolves, casting spells, mocking the party.

2. **Usage Guidelines**:
   - Every file should include **0–3 clearly labeled Strahd hooks** tied to his interests.  
   - Mark them as **Optional – Strahd Appearance** or **Required – Strahd Reaction**.  
   - Tie them to logical moments: when they thwart his servants, protect Ireena, claim major relics, or defy his will.

3. **Tone of Strahd**:
   - Highly intelligent, patient, and amused.  
   - Speaks politely most of the time, with occasional flashes of cruelty.  
   - Avoid slapstick humor; use dark irony or elegant contempt.

4. **Example Notation**:
   - *Campaign Trigger – Strahd’s Interest in the Party Increases ( +1 ):*  
     - Note cumulatively when they defeat key enemies or show unusual resolve.  
   - *If the Seer placed the [Tome/Sunsword/Icon] in this location in your Tarokka reading, Strahd may personally observe the party here.*

## 6. Optional Side Adventures and Retracking

1. Barovia is open in structure, but we must keep inexperienced DMs from losing the core story.

2. To help, include **clearly marked optional adventures**:
   - Label them: **Optional Side Trek – [Name]**.  
   - Purpose: steer the party gently back toward core objectives (Ireena, Vallaki, artifacts, Castle Ravenloft).

3. Design guidelines for side treks:
   - 1–3 scenes, easy to drop in anywhere geographically appropriate.  
   - Low prep: simple maps or theatre-of-the-mind only.  
   - Provide at least one **clear clue** or **NPC** that points back to the main story.

## 7. Progress Tracking and Scores

1. All written sections must be listed in `agents/progress.md`.
2. For each section, include:
   - File name.  
   - Short description.  
   - Status (Not Started / Draft / In Review / Revisions / Complete).  
   - A row for scores and notes from each role:  
     - Writer  
     - Master Dungeon Master  
     - Inexperienced Dungeon Master  
     - Player  
     - Editor

3. Scoring rules:
   - Each role gives a **score out of 10** and short notes.  
   - Section is **considered complete** only when:  
     - The Writer marks it "Complete" **and**  
     - Each role’s score is **5 or more** **and**  
     - The average score is **7 or more**.

4. Editing responsibilities:
   - Only the **Writer** alters campaign text and the overall layout of `agents/progress.md`.  
   - Other roles may **only edit their own score and notes**.

## 8. Specific Guidance for Early Campaign (Into the Mists & Death House)

1. **Starting Point**:
   - The campaign text begins when the players enter the Mists and become trapped in Barovia.  
   - Assume the DM uses unique narration for the trap sequence; our files start at or immediately after that moment.

2. **Death House**:
   - Treat as a richly detailed, horror-heavy introductory dungeon.  
   - It should feel dangerous, but we must provide **multiple escape valves** for level 1–3 characters.  
   - Emphasize the tragic story of the children and cult rather than only jump scares.

3. **After Death House**:
   - Provide structured scenes that move the characters toward **The Village of Barovia**.  
   - Include at least one **optional early Strahd observation** to show that he is aware of them.

## 9. Writing Process Expectations

1. Before writing a new campaign file:
   - Skim or reread the relevant sections of the source book.  
   - Review existing `01-Campaign` files to maintain tone and continuity.

2. While writing:
   - Continually ensure headings follow numeric progression (1, 2, 3; 3.1, 3.2, etc.).  
   - Mark all **Optional** content clearly.

3. After writing:
   - Update `agents/writter.md` with what was done in that session.  
   - Update `agents/progress.md` with status changes for sections.

## 10. Future Additions

As new patterns or needs emerge (for example, a standard Strahd cameo template, or common player detours), this guide should be updated by the Writer while preserving all prior sections unless they are clearly obsolete.
