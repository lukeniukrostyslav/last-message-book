# BLOCK 27.7 — PUBLISHING PACKAGE INTEGRATION

Status: COMPLETE — 100%

Date: 2026-09-19

## Integrated package map
The publishing package is now defined as one coherent release structure:

01_MANUSCRIPT/
- reader-facing manuscript assembled from Prologue + Chapters 01–40
- title page
- no development notes

02_METADATA/
- title
- language
- genre
- author/publication fields
- edition/publisher/ISBN/date/price/territories fields, explicitly unresolved where not confirmed

03_MARKETING/
- short blurb
- full synopsis
- pitch/positioning copy

04_QA/
- canon/continuity lock reference
- editorial completion references
- final word-count measurement to be recorded at release QA

05_MANIFEST/
- package contents
- source Git revision
- release status
- checksum/version fields

06_ARCHIVE/
- repository source/checkpoint references

## Integration rules
- The manuscript remains the source text; publishing documents do not alter canon.
- Marketing copy is separated into spoiler-light and spoiler-inclusive forms.
- Unconfirmed commercial metadata is never fabricated.
- The final measured word count must be taken from the actual assembled manuscript, not copied forward blindly.
- Release package cannot be declared publication-ready until Block 29 QA passes.

## Result
Block 27.7 integration specification is complete. No manuscript canon was changed.
