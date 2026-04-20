# Telemetry Logging Test Repo

This repository is a small sandbox for testing telemetry logging behavior.

## Purpose

Use this repo to verify that telemetry events are emitted, captured, and easy to inspect during local development.

## What To Validate

- Application startup events are logged.
- User actions generate telemetry records.
- Errors include enough metadata for debugging.
- Session identifiers and timestamps are present.
- Logs are written consistently across repeated runs.

## Suggested Test Flow

1. Start the application or script that emits telemetry.
2. Trigger a few known actions.
3. Force one expected error case.
4. Inspect the generated logs or telemetry sink.
5. Confirm the event names, payload fields, and timestamps are correct.

## Expected Outcome

You should be able to trace a full test session from startup to shutdown with clear, structured telemetry entries.

## Test Artifact

Use [telemetry-login-test.txt](./telemetry-login-test.txt) as a simple file-based artifact during telemetry testing.

## Notes

This README is intentionally simple and is meant only to support telemetry logging tests.
