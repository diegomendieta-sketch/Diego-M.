# Sanitization of shared skill copies

Only the copies in `skills/personal/` were edited. Original installed skills were preserved.

- Replaced real staff names and source/log aliases with consistent fictional labels in the roster, schedule rules, and escalation examples. Schedule times, days off, timezone conversions, exclusions, and routing logic remain in place.
- Replaced customer/caller examples, property addresses and locations, private email examples, historical ticket identifiers, and concrete customer/property UUIDs with fictional examples.
- Replaced deployment, spreadsheet, Slack member/channel/group identifiers, and local report-project paths with configuration placeholders. Replace those placeholders with authorized values when installing these skills.
- Kept public role inboxes, public support contact information, channel names, tool names, and workflow rules needed to understand the skills.
- The report runner still requires its separate `agent_report` project package, and the schedule rules reference an external scope JSON. Those dependencies are not included in the skill folders.

Personal files changed:

- `skills/personal/agent-performance-report/SKILL.md`
- `skills/personal/agent-performance-report/assets/team_roster.csv`
- `skills/personal/agent-verification/SKILL.md`
- `skills/personal/send-available-report/references/schedule-rules.md`
- `skills/personal/xa-notes/SKILL.md`
- `skills/personal/xa-quick-slack/SKILL.md`
- `skills/personal/zendesk-record-retrieval/SKILL.md`
