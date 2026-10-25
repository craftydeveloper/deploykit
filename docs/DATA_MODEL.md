# Data model

## Proposed fields

Release records need an environment, version, check result, owner, and rollout note.

The examples are synthetic contract examples and are not loaded automatically. Before changing persistence, inspect the current serialized state and write a migration that preserves user data. Validate imported records and avoid storing credentials.