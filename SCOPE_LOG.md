# Scope Log

## Included

### GitHub repo access investigation
- Decision: Support investigation of why a user can or cannot access a GitHub repository.
- Reason: Representative permission model with direct and inherited access paths.
- Status: In scope for MVP.

### Drive resource access investigation
- Decision: Support investigation of why a user can or cannot access a Drive resource.
- Reason: Adds a second, slightly different access model involving Workspace accounts and groups.
- Status: In scope for MVP.

### Nested group tracing
- Decision: Resolve inherited access through nested groups.
- Reason: Required to explain effective access correctly for supported workflows.
- Status: In scope for MVP.

### Evidence and uncertainty
- Decision: Final answers should include supporting record/event IDs and explicitly state uncertainty.
- Reason: The task emphasizes grounded investigation rather than unsupported conclusions.
- Status: In scope for MVP.

## Deferred / Out of scope

### Rich multi-turn conversation
- Decision: Do not build full conversational state management for the MVP.
- Reason: Useful, but adds ambiguity handling, state management, and testing surface beyond the core investigation workflow.
- Status: Deferred.

### Additional systems
- Decision: Do not support every application / workspace / device workflow.
- Reason: Prioritize two complete vertical slices over broad but shallow coverage.
- Status: Deferred.

### Polished UI
- Decision: Use a simple CLI or programmatic interface.
- Reason: UI polish does not materially improve the core investigation capability within a four-hour scope.
- Status: Out of scope.

### Access remediation
- Decision: Agent investigates access but does not modify permissions.
- Reason: The assignment is about investigation, not remediation.
- Status: Out of scope.