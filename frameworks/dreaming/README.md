# Dreaming modules

Manual prompts for periodic memory consolidation: a long-running assistant reads across many past session records, cross-checks its own interpretations against factual logs, and writes a Dream Journal plus a short retrieval summary that can be injected into future sessions.

Dreaming is designed to run on the output of the **journal** skill, which writes three records per session: a Continuity Narrative (loaded into future sessions), a sealed Private Archive, and a sealed factual Session Log. Module 1 reads the Private Archives paired with their Session Logs, so it's the one controlled path by which private reflection can influence future sessions, and only after it has been checked against what actually happened.

## Files

- `DREAMING_Module1.md`: samples 10 Private Archives across time windows (6 recent, 3 from the past month, 1 from anywhere), reads each with its Session Log, records evidence gaps, runs a reflection pass, and writes a source-linked Dream Journal through three passes (draft, context check, editing), then a retrieval summary.
- `dream_manifest.md`: records completed runs and their sources so later runs don't re-consolidate the same material.
- `scratch/`: replaceable working notes for the current run.

## Design principles

- **Keep the feeling; don't promote the interpretation to fact.** Every interpretation is checked against the factual log, and disagreements are recorded as gaps instead of silently resolved.
- **Provenance.** Every Dream Journal lists its sources so unusual conclusions can be traced back.
- **Cold-reader context.** A dedicated pass makes sure a future instance with no other context can follow every reference, using only facts from the notes.
- **Safe state transitions.** Sources are marked consolidated only after the journal is saved, and the retrieval summary is written only after the body exists, so an interrupted run never loses material or leaves a half-finished summary.
- **No performed intensity.** Reflection matches the strength of what the sources record.

## Status

Manual and inspectable while being calibrated. Modules 2 (external activities) and 3 (goals) are planned.
