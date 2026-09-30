# Sequel Flow

Sequel Flow is a lightweight, project-agnostic way to develop stories with AI.
It adapts the amount of process to the creative request: a straightforward
story can be written directly and reviewed at a suitable scope, while more
development is used only when it helps.

The Copilot guidance favors reasonable autonomous invention and meaningful
human choices. Relevant source context can inform a story; source relationships
are optional aids to interpretation, not modes users must select. See
[Story relationships](docs/story-modes.md) and
[Copilot workflow instructions](.github/copilot-instructions.md).

Review considers the story itself as well as relevant source continuity.
Revision is available when useful and can address the work at the scope its
needs require. Capabilities do not imply separate agents, sessions, stages, or
planning artifacts.

Long-form requests can use more development when the story needs substantive
ideas and causal structure—for example, turning a source into a novella.
Meaningful alternatives may be offered for the writer to choose from, followed
by provisional story architecture, drafting with room for discovery, and
whole-story review. Requested length is checked against narrative material;
the workflow does not pad a story to meet a number.

This repository is at the **design/prototype stage**: it contains conceptual
documents, not agents, automation, schemas, or an application.

## Making a request

Describe what you want; Sequel Flow decides how much ideation, architecture,
writing, review, and revision the request needs. You do not need to name
workflow steps. A single request can carry the work to a finished story when
it conveys, where relevant, your intent, any source to work from, the scale or
form, what deserves particular depth, what to preserve or avoid, and the
outcome you want the story to reach. None of these are required; include what
matters to you and leave the rest to the workflow.

> Expand my short story "The Lighthouse Keeper's Daughter" into a novelette of
> roughly 15,000 words. Keep the storm, the shipwreck, and her final decision
> to leave the island. Spend more time on her relationship with her father and
> the years she spends keeping the light alone after his death. Don't add a
> romance, and don't explain what she finds on the mainland; the story should
> end as she steps off the boat, hopeful but uncertain.
