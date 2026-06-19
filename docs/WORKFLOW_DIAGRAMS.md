# Workflow Diagrams

These diagrams are public-safe and intentionally abstract. They describe the
boundary without exposing private implementation details.

## Workflow Overview

![Workflow overview](../assets/diagrams/workflow-overview.svg)

Source Mermaid:

```mermaid
flowchart LR
  A["Controlled listening inputs"] --> B["Private intake"]
  B --> C["Protected review"]
  C --> D["Mirror-safe metadata"]
  D --> E["Private Big Stick / Unburied review"]
  E --> F["Approved public-safe context, if Faith chooses"]
```

## Public / Private Boundary

![Public/private boundary](../assets/diagrams/public-private-boundary.svg)

Source Mermaid:

```mermaid
flowchart TB
  subgraph Public["Public Surface"]
    P1["Project story"]
    P2["Abstract visuals"]
    P3["Status and roadmap"]
    P4["Inquiry path"]
  end

  subgraph Private["Private Engine"]
    R1["Source code"]
    R2["Raw transcripts and uploads"]
    R3["Credentials and deployment"]
    R4["Private workflows and receipts"]
  end

  Private --> G["Review gate"]
  G --> Public
```

## Safety Notes

- Diagrams do not include endpoint names, tokens, system paths, or server
  topology.
- Diagrams do not describe private legal, family, medical, or admin records.
- Any future diagram that needs more detail should be reviewed before public
  release.
