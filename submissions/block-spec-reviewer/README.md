# Block-spec reviewer

Research note from the Grok Bot Boston Hackathon, 9 October 2026.

Finding: none of the five subjects enforces a block writing its own changelog before the next block can run. The closest public match is an instruction to the agent, not a gate.

Locked restatement: a memory block finishes its run by writing a changelog entry about what it changed, and the next block can't start until that entry exists.

Paste PROFILE.md into a Grok Bot description to reproduce the flow. The note is block-spec-note.md. Chat is not the record.

Original repo: https://github.com/mongo328/block-spec-reviewer
