# Repository Memory

## Stable Context  
- **Repository**: `qiubi77/my-claw` – the sole source of truth for all issue‑based interactions.  
- **Primary Agent**: “小龍蝦” (the agent) – a chatbot that communicates via Telegram.  
- **Owner**: `qiubi77` – the human who initiates all messages and issues.  
- **Naming Convention**:  
  - Formal name: **QB**.  
  - Affectionate aliases: **小龍蝦** or **丘比**.  
  - All future replies should use **QB** as the default reference; use the aliases only when the owner explicitly requests a more casual tone.  
- **Communication Channel**: Telegram is the sole medium for the owner to send instructions; every Telegram message is turned into a GitHub issue (currently only issue #1).  
- **Issue Lifecycle**:  
  - A new issue starts in the **waiting** state until the agent replies.  
  - No tasks are created until the agent has acknowledged the instruction.  
  - The issue remains open until the agent completes the requested action or the owner closes it.

## Recent Themes  
- **Identity & Naming** – The owner has just confirmed the agent’s formal name (QB) and clarified the acceptable affectionate terms.  
- **Awaiting Agent Response** – All three snapshots show the same waiting state; the agent has not yet replied to the owner’s messages.  
- **Telegram‑to‑Issue Flow** – The owner’s messages (“14456”, “440”, and the naming clarification) are being captured as a single issue; the process of converting Telegram messages into actionable tasks is still in its infancy.  
- **No Work Items Yet** – No concrete tasks or subtasks have been generated; the repository is currently in a “setup” phase.

## Constraints  
- **No Labels** – The current compaction window contains no labels; any future labeling strategy must be explicitly defined.  
- **Single Issue Focus** – With only one open issue, cross‑issue patterns cannot be established; any new issue must follow the same structure to maintain consistency.  
- **Agent Responsiveness** – The agent must reply within a reasonable timeframe (e.g., within 24 h) to avoid stalling the workflow.  
- **Naming Consistency** – Mixing the formal name (QB) and aliases without clear context may lead to confusion; enforce the naming rule in all communications.

## Open Loops  
- **Agent Reply Pending** – The agent has not yet responded to the owner’s Telegram messages; the issue remains in the waiting state.  
- **Task Creation Uncertain** – It is not yet decided whether the owner’s messages should be split into actionable tasks; this will depend on the agent’s reply.  
- **Naming Confirmation** – While the owner has indicated that QB is the formal name, the final choice of alias usage (小龍蝦 vs. 丘比) is still to be confirmed.  
- **Future Issue Handling** – No clear protocol exists for handling multiple simultaneous issues; a standard operating procedure should be drafted once more issues appear.  

> **Uncertainty Note**:
