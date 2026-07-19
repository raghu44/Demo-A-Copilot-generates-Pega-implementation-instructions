# Part of Guidelines for Using MCP and Pega
https://www.youtube.com/watch?v=nGIGTk0-mZ0
## MCP Requirements
- MCP is not required for this process.
- You can place your Blueprint export, requirement documents, screenshots, and rule inventory in the VS Code folder.
- Copilot can then produce the following:
  - Property names and types
  - Class placement
  - Activity steps
  - Data transform logic
  - When-rule conditions
  - REST payloads
  - Implementation documentation

## Manual Rule Creation in Pega
You would create the rule manually in Pega.

## Example Prompt for Pega Design
> Act as a Pega Lead System Architect.
>
> Review the requirements and documents in this workspace.
>
> For the Learning Reimbursement Request case type, design a test property:
>
> **Property name:** CopilotTestStatus
> **Type:** Text
> **Applies-to class:** MyOrg-SYVLearn-Work-LearningReimbursementRequest
>
> Also design an activity named `SetCopilotTestStatus` that:
>
> 1. Sets `.CopilotTestStatus` to "Created through Copilot design".
> 2. Adds a history note.
> 3. Does not commit explicitly.
> 4. Can be run manually for testing.
>
> Provide:
>- Exact Pega rule names
>- Ruleset placement
>- Activity steps
>- Methods and step-page details
>- Testing procedure
>
> Do not change any files or external systems.
