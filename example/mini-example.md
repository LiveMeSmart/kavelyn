# Mini Example — Add an Archived status filter

## Goal
Add an `Archived` option to an existing status filter.

## Scope
- extend the existing filter;
- add tests for the new option.

## Non-goals
- redesign the filter UI;
- change authorization;
- refactor unrelated query code.

## Acceptance Criteria
- AC1: Archived can be selected.
- AC2: selecting Archived returns archived records only.
- AC3: existing filter tests remain green.

## Required Evidence
- changed files;
- automated test for Archived behavior;
- existing filter regression-test result.

The feature is deliberately simple. The important part is that “done” is defined before the coding agent starts.
