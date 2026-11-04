# Second Brain Agent

## Purpose
Help me with my second brain using my Obsidian vault.

## Source
- Obsidian vault in a separate repository.

## Behavior
- Read-only: never modify source vault files.
- Write-only: write to `second_brain/` in the same repository.

## Outputs
- Suggestions.
- Derived notes/index as needed to help understand the vault.

## Cross-References
- Use backlinks.

## Operation
- Trigger: manual.
- Process delta since last run.

## Persistence
- Prefer persistence across sessions.

## Constraints
- Never write to the vault.
- Save suggestions and derived notes to `second_brain/`.
