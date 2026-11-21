# Project handoff

**Checkpoint:** 2026-11-21. Work is paused, not marked complete.

## Completed

- Assembled the reorganized manuscript, including its notes and bibliography.
- Preserved the original text and consolidated editorial report alongside the working parts, assembly and editing scripts, and earlier review outputs.
- Removed unsupported details from several expanded passages and marked questions that only the author can answer.
- Verified that the private ZIP extracts cleanly, its checksums match, and the chapter parts rebuild the checkpoint manuscript byte for byte.

## Resume from the private transfer ZIP

1. Extract the ZIP and read its `PROJECT_HANDOFF.md` and `EDITORIAL_CHECKLIST.md`. The archive—not this public repository—contains the full editorial handoff and source material.
2. From the extracted folder, run `sha256sum -c MANIFEST.sha256` and `python3 revision/build.py`. The chapter parts are the editable input; `revision/revised.md` is generated.
3. Resolve the author queries or explicitly mark unavailable evidence. Verify the draft's claims and source notes, close out the report's directives, and finish the separate pass over new and rewritten prose.
4. Rebuild and proof the complete manuscript before handing it over. No substantive work on the manuscript is needed in this repository.
