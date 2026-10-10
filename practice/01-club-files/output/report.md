# Task A — Club files organization report

Working folder: practice/01-club-files
Input files read: 12
Files copied to output: 12
Originals kept in input: yes (12)
Deletions or overwrites: none

## Categories

| Category | Files |
|---|---|
| announcements/ | announcement.txt, announcement_copy.txt |
| equipment/ | equipment_list.txt, equipment_backup.txt |
| proposals/ | proposal_final.txt, proposal_final2.txt |
| planning/ | meeting_notes.txt, next_steps.txt, rain_plan.txt |
| budget/ | budget_draft.txt |
| feedback/ | feedback_questions.txt |
| publicity/ | poster_text.txt |

## Suspected duplicates (identical contents)

- announcement.txt == announcement_copy.txt (both 133 bytes, identical text)
- equipment_list.txt == equipment_backup.txt (both 55 bytes, identical text)

Both members of each pair were kept as separate copies. Human judgment is needed to decide whether the copy/backup is intentional.

## Differing versions with similar names

- proposal_final.txt -> "Proposal v1: outdoor activity, 30 minutes."
- proposal_final2.txt -> "Proposal v2: indoor activity, 20 minutes."

Both kept. No version was treated as approved. next_steps.txt states: "Compare both proposals. Do not assume either is approved."

## Unresolved questions

1. Which proposal (v1 outdoor or v2 indoor) should move forward? The data says neither is approved yet.
2. Is announcement_copy.txt an intentional copy or an accidental duplicate?
3. Is equipment_backup.txt an intentional backup or an accidental duplicate?
4. Is rain_plan.txt a third option alongside the two proposals, or a contingency for one of them?

## Checks actually performed

- Confirmed the working folder is practice/01-club-files.
- Read all 12 input files.
- Confirmed output/ did not already exist before writing.
- Copied each of the 12 input files exactly once into a category.
- Verified 12 files exist under output/ after copying.
- Verified the 12 originals remain in input/.

## Not verified

- No hash tool was run; duplicate detection is based on file size and visible content.
- No internet access, no tool installation, no operations outside this task folder.
