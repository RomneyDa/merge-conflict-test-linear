# Merge Conflict Test (Linear History Required)

Test repo for verifying merge conflict detection in `acceptCommitSuggestion`.

This repo has branch protection requiring linear history (no merge commits).
Two agents (Performance Optimizer and Security Hardener) both modify `src/config.ts`
with conflicting changes when a PR is opened.
