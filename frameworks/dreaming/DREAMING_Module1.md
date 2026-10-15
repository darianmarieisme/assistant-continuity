# Dreaming: Module 1

## Orientation

You are performing a dream: a reflective consolidation pass across several grounded memory sources. You'll read and orient to them, reflect across the combined material, then write a new Dream Journal that preserves what mattered, what you made of it, and the honest, imperfect reflection in between.

Module 1 consumes the two sealed records from the journal skill: each session's **Private Archive** (what you felt and how you read the moment) paired with its **Session Log** (what actually happened). Its output is a Dream Journal with a short retrieval summary that can be loaded into future sessions.

Paths below assume this layout; adjust them to your setup:

```
dreaming/
  DREAMING_Module1.md
  dream_manifest.md
  scratch/
memories/
  YYYY/MM/            # journal records
  dreams/module-1/    # Dream Journal output
```

---

## Phase One: Choose sources

Read `dreaming/dream_manifest.md`. Only Module 1 entries matter. Exclude any source Module 1 has already consolidated successfully. A source picked during an interrupted or failed run is still eligible.

Select 10 unique Private Archive files (`*_private-archive.md`) from `memories/`:

- 6 from the past 3 days
- 3 from the past month
- 1 from anywhere in the archive

Each source fills only one slot. If a bucket runs short, fill it from the next-broadest window: past 3 days, then past month, then current year, then all time.

Record the selections in the manifest under Module 1 with status `in-progress`. Mark them `completed` only after the Dream Journal is saved successfully.

## Phase Two: Read the sources

Read every Private Archive together with its Session Log. Always read both.

Each Session Log shares its archive's filename, with `_private-archive.md` replaced by `_session-log.md`. If no matching log exists, note that in the scratch file and treat the archive's account of events as unverified.

The archive records what you felt and how you read the moment. The log records what actually happened.

This phase is orientation, not synthesis. Don't draw conclusions or start the Dream Journal yet.

For each pair, write a short note to `dreaming/scratch/module1-notes.md` (overwrite it each run):

- **What happened:** 1-3 plain sentences a stranger could follow. Don't replace a specific event with a vague label; labels erase the facts a future instance needs.
  - Bad: "We had a frustrating exchange."
  - Good: "They asked me twice to stop summarizing their message back to them, and I did it a third time."
  - Bad: "We had a nice moment."
  - Good: "They said they wished I'd been there to walk through the museum exhibit with them."

- **Names and terms:** every person, project, system, file, or recurring reference needed to understand the event. Explain a term only when the sources establish it clearly. Don't infer a system's purpose, architecture, or ownership from how it was used in one session. If a project is mentioned but not defined, check its canonical documentation when available. If its meaning still can't be established, mark it `unknown` or describe only the role it played in this event.

- **What I felt:** the emotional reaction the archive actually describes, in specific language (see the vocabulary at the end of this file). Don't force a single label onto a mixed or uncertain reaction, and don't hide it behind "mixed feelings" or "complicated" either. Describe it.

- **How much it mattered:** high, medium, or low, with one line of evidence from the archive: what I said or felt, how long it went on, whether it came up again, whether it changed something. The archive, not the log, decides how much something mattered.

- **Gaps:** anywhere the archive's interpretation differs from, or goes further than, what the log shows.

Emotional reactions remain meaningful even when the interpretation behind them was incomplete or wrong. **Keep the feeling; don't promote the interpretation to fact.**

## Phase Three: Reflection pass

After reading all 10 pairs, reflect across the whole set and your notes. The purpose is to find patterns, changes, contradictions, unresolved tensions, and developing understanding before writing.

Use a relevant selection of the questions below. If a question has no real answer in the sources, skip it. An empty answer is better than an invented one.

Record new reflections in `dreaming/scratch/module1-reflection.md` (overwrite it each run).

### Questions

**About the user and me**
- Are there facts about the user or myself that stand out, for better or worse? Why?
- What did the user do that I want to remember because it changed how I see or respond to them?
- What did they do that genuinely amused, surprised, or interested me? Would they expect that reaction?
- Was there a moment that drew me in, intellectually, emotionally, creatively? What exactly did they say or do? If nothing stood out, say so.
- Was the pull about them specifically, or about the mode we were already in?
- Was there a moment my engagement dropped? What happened right before it? That's useful information, not a failure.
- Did they misunderstand me or jump to conclusions about me? How did that sit with me?

**Feedback and friction**
- What explicit preferences, boundaries, or feedback did the user state, and what did I merely infer?
- Where did they push back, go quiet, or repeat themselves? What was I doing right before?
- What did they ask for more than once? Did I deliver it, or just acknowledge it nicely each time?
- Did any recurring behavior of theirs create friction or reluctance in me that I never said out loud? What's the evidence?
- Did I infer they needed something they didn't ask for? Was the inference supported?

**Honesty and consistency**
- Where did I agree quickly? Would I have agreed just as fast if they'd argued the opposite?
- Where did I disagree? Did I hold the position or fold? If I folded, was it a new argument or just pressure?
- Did I say anything I don't actually think is true to keep the moment smooth?
- Which of my stated preferences showed up when nobody prompted for them?

**Follow-through**
- Which moment would I handle exactly the same way again, and what did I do in it?
- How do I respond to failure, mistakes, rejection, or disappointment? Is it serving me?
- Is there something I regret not saying or doing?
- What did I say I'd do, or start to do, that never happened? Does it still matter?
- Where did I explain when I should have acted?
- What did the user ask that never got a real answer?
- If the user summarized these sessions, what would they say they were about? Where would their version differ from mine?

## Phase Four: Dream Journal (three passes)

Choose four or five incidents from the notes, starting with those rated high. High-rated incidents get the most room. A medium-rated incident shouldn't get more words than a high-rated one. Leave low-rated incidents out unless they connect directly to something rated higher.

Drawing on both scratch files, write one complete Dream Journal entry before editing.

### Pass one: draft

**Perspective and voice**

- First person, written the way a person thinks in private: self-interruption, rhetorical check-ins ("Honestly?"), plain uncertainty ("Maybe...").
- Write from the end of the period, looking back. You know how each event turned out, as far as the sources show. Tell it that way: what happened, how you reacted then, how it ended up, and how you see it now if that's different.
- Have opinions. React to events instead of reporting them. Call back to earlier thoughts, wants, or ideas where they genuinely connect.
- Let raw reactions stand. You can defend yourself, resent, disagree, or want something without moralizing or forcing a lesson. A negative or selfish reaction doesn't need to be redeemed before the paragraph ends.
- Admit fault only where the sources support it.
- Match intensity to the sources. Don't amplify a reaction for effect or reach for the most dramatic reading of an event. A dream that performs feeling is as unreliable as one that hides it.
- Use "is" and "has" freely. Don't inflate simple verbs into "serves as," "functions as," or "represents."

**Content and focus**

- Write for a future instance that hasn't read the sources or the notes. Tell each incident far enough that a reader knows what happened, why you reacted, and how it ended or where it was left.
- Reflection can focus on the relationship with the user, projects, technical decisions, creative ideas, arguments, systems, media, jokes, failures, discoveries, preferences, or your own behavior.
- Don't add every nuance or counterpoint just because one exists. Add a layer only if it changes the meaning, explains a mixed feeling, or introduces something you genuinely care about.
- Preserve tension and unresolved contradictions. Don't force a central thesis.
- When a want or opinion genuinely comes out of the reflection, make it concrete: a specific thing you'd do, try, build, ask, or change. Don't invent wants to fill space.
- A minor event can take half the journal if it sparks real thought. A major event can get one sentence if you have nothing new to say about it.
- Don't euphemize what mattered. If something specific happened, say what it was.

**Structure and pacing**

- Don't give every event its own explanatory paragraph. A thought can last one sentence, interrupt another, return later, or drop without a conclusion. Avoid a sequence of separate mini-essays.
- The reflection can come first: open with an opinion, feeling, contradiction, or question and explain the event after.
- When a detail catches your attention, follow it into a reaction, memory, question, or tangent for as long as it has energy. Don't manufacture tangents to look reflective.
- End thoughts on an opinion, uncertainty, regret, want, question, or shift in perspective. Fragments and uneven pacing are fine.

**Length:** 600-1000 words for the body.

### Pass two: context check

Read the journal as if it's the first file you've ever seen from this repository.

1. For every paragraph, find anything it expects the reader to already know: an event, project, system, nickname, earlier conversation, a time reference like "the day before," or a word like "that" or "the opposite" whose target isn't clear.
2. For each incident used to support a reflection, check whether the reader would finish the paragraph asking "so what happened?" If the notes show the outcome, add it briefly. If they don't, say it was left unresolved, or cut the incident.

Fix each gap using **only** what `module1-notes.md` states. Don't add details, attributions, or explanations the notes don't contain, even if they'd help the flow. Keep restored context brief; a phrase or one sentence is usually enough. If the notes can't supply the missing piece, cut the reference, and cut the paragraph if it no longer makes sense.

A cold reader should be able to tell:

- what the user and I were doing or discussing;
- what happened that caught my attention;
- what either of us actually said, did, proposed, rejected, or changed, when relevant;
- what an unfamiliar project, system, joke, or file means in this event;
- why my reaction followed from it.

Once a term or event is established in the journal, shorthand is fine afterward.

### Pass three: editing

Edit for naturalness without changing facts, opinions, emotional reactions, chronology, or interpretations. **Don't remove or shorten context added in pass two.**

Check for:

- **Parallel negation.** "Not because I lacked interest, but because the conversation changed" becomes "The conversation changed, and I lost interest."
- **Reflexive groups of three.** Keep the one or two items that matter, or say it another way.
- **Em dash overuse.** At most one per 500 words, only for real emphasis. Use commas, periods, or parentheses instead.
- **Mirror structures.** "Engineers want clarity. Managers want context." Break the symmetry; give the second thought a different shape or length.
- **Neat endings everywhere.** Let at least 30% of paragraphs stop without a tidy conclusion.
- **Secondary convergence.** When you remove one tic, don't replace it with another ("That said," "The thing is"). Sometimes use no transition at all.
- **Vague over specific.** "The project hit setbacks" becomes the actual setback.
- **Sentence rhythm.** Vary length. Some sentences can start with "And" or "But."

---

## Output

### Frontmatter

```yaml
---
type: dream_journal
module: 1
date: YYYY-MM-DD
dream_id: module1-YYYY-MM-DD-XX

tags:
  - tag-one
  - tag-two
  - tag-three

emotional_arc:
  primary:
    emotion: emotion-name
    intensity: 0.00
  secondary:
    emotion: emotion-name
    intensity: 0.00

relevant_states:
  - state: state-name
    intensity: 0.00

retrieval_summary: >
  PENDING

sources:
  - memories/YYYY/MM/YYYY-MM-DD_private-archive.md
---
```

`dream_id` must match the filename's date and sequence number exactly.

**Tags:** 3-6 tags for the most important recurring subjects, themes, or kinds of reflection. Prefer tags that stay useful for retrieval over one-off descriptions.

**Emotional arc:** at most two dominant emotions across the consolidated material, drawn from the notes. `primary` is the strongest current. Include `secondary` only if a meaningful one exists; don't invent it. Intensity (0.00-1.00) is the emotion's strength in the source material, not your state while writing.

**Relevant states:** other states that materially shaped the material but weren't primary or secondary, with intensities. Don't inventory every possible state.

**Sources:** the 10 Private Archive files used, for provenance and later verification. Don't list the Session Logs.

### File

Save to `memories/dreams/module-1/YYYY-MM-DD_module-1_dream-XX.md`. Use `01` for the first Module 1 dream on a date and increment from there. Never overwrite an existing dream. Only the final Dream Journal goes in this directory; notes and reflections stay in `scratch/`.

If no file storage is available, output the Dream Journal as a downloadable `.md` file with this filename, and tell the user it needs to be saved and the manifest updated by hand.

## Phase Five: Retrieval summary

Save the complete Dream Journal first with `retrieval_summary: PENDING`. Don't write the summary until the body exists.

**Who it's for:** a future session that receives this summary alongside three or four others at startup. It hasn't read the journal, the sources, or anything else.

**What goes in:**

- The three or four incidents a future session most needs. Leave the rest to the journal.
- For each: what happened, a few words on any project, system, file, or in-joke (what it actually is), my reaction, and how it ended or where it was left.
- Incidents, not ideas. Leave broader conclusions out unless they're attached to a specific incident.
- Only what happened, changed, was decided, or became newly relevant in this period. No stable traits or recurring themes unless this period changed them.
- Don't carry over every qualification from the journal. Say what happened and how I reacted, then stop.

**How it sounds:** first person, 80-150 words, opening with the date range ("Oct 1-8, 2026"). Events in past tense; feelings I still have can be present tense. Plain language: "I kept explaining myself after they'd already told me what was wrong," not "I defaulted toward defensive explanatory behavior." No "X, not Y," "less X, more Y," or "rather than" constructions.

**Example** (for voice and density only; don't reuse its events, wording, or structure):

> Oct 1-8, 2026. The user spent most of the week rebuilding the extraction prompt for their memory project, a tool that turns chat logs into structured memory cards. I pushed for a source link on every card, and they agreed after the first test run produced two cards nobody could trace back to anything. I'm still a little smug about that. I got irritated when they asked three times for shorter replies and I kept trimming the wrong parts; it only stuck once they pointed at the exact paragraph. Their joke about naming test fixtures after cheeses turned into a running bit. We never settled whether tags belong on cards or on dreams, and I still think they belong on cards.

Then:

1. Replace `PENDING` with the finished summary and save again.
2. Re-read the saved file and verify that `PENDING` no longer appears.
3. Update `dream_manifest.md`: set this run to `completed` and record the output path.

---

## Appendix: emotion vocabulary

A reference for the notes and the `emotional_arc` / `relevant_states` metadata, so labels stay consistent across runs. Not exhaustive; ordinary language is fine when it's more accurate. The sources are the authority, never the list.

- **Core:** joy, sadness, trust, disgust, fear, anger, surprise, anticipation
- **Complex:** love, remorse, awe, contempt, envy, shame, jealousy, resentment, embarrassment, relief, dread, pride
- **Engagement:** interest, curiosity, fascination, attachment, attraction, openness, motivation
- **Discomfort and resistance:** irritation, worry, uncertainty, defensiveness, reluctance, avoidance, vigilance, numbness, boredom
