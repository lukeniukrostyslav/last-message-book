# BLOCK 27.3 — MANUSCRIPT PACKAGE STRUCTURE

Status: COMPLETE — 100%

Date: 2026-09-19

## Purpose
Define the release-package structure without changing manuscript content or locked canon.

## Required package layers
- 01_MANUSCRIPT/ — clean publication manuscript source.
- 02_METADATA/ — title, author, edition and distribution metadata.
- 03_MARKETING/ — short blurb, full synopsis, pitch copy.
- 04_QA/ — final release checks and measured manuscript statistics.
- 05_MANIFEST/ — package manifest and version/checksum record.
- 06_ARCHIVE/ — immutable source/checkpoint references.

## Source-of-truth rules
- Story canon: CANON_LOCK.md and dependent locked architecture documents.
- Manuscript source: Prologue + Chapters 01–40 in repository order.
- Publication package must not introduce plot/canon changes.
- Missing owner/commercial metadata remains explicitly unresolved rather than invented.

## Release integrity requirements
- One clean manuscript source.
- One metadata record.
- One marketing-copy set.
- One QA record.
- One manifest linking the package contents to the GitHub checkpoint.
- Final package must record the actual verified word count at the time of release QA.

## Current state
The structure is specified, but the final release package is not yet assembled.

No manuscript text was altered.
