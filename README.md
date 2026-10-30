# landlord-skills

**Free AI skills for private landlords with one or a few homes in England:
rent increases with the right Section 13 dates, tenant repair reports
handled quickly and on the record, and everyday tenant messages written
under the Renters' Rights Act rules that started on 1 May 2026.**

Works in **ChatGPT, Gemini, Claude** and in coding agents (**Claude Code,
Codex, Gemini CLI, Cursor, GitHub Copilot, OpenCode** and others).

These aren't one-line prompts. Each skill encodes how a careful landlord
does the job: the date rules for Form 4A, the repairing duties on gov.uk,
the 28-day pet reply, 24 hours' written notice for access, and a quality
checklist the assistant runs before it answers. It never invents dates,
rents or legal deadlines.

| Skill | Use it when… |
|---|---|
| `rent-increase` | You want to put the rent up. Get the earliest valid start date and the last day to serve (2 months from service, 52 weeks since the last rise, on a rent day), a check of your figure against open-market rent, Form 4A filled in question by question, and a friendly covering letter. England, from 1 May 2026. |
| `repair-requests` | A tenant reports a leak, a dead boiler, mould or a broken alarm. Get safety steps first, an urgency tier with a target timescale, whose job it is, a reply to the tenant, a 24-hour access notice, a contractor brief and a dated repair-log row. Handles damp and mould the careful way. |
| `tenant-messages` | A tenant asks for a pet, gives notice, is late with rent, or complains about noise. Get a short, fair reply with the deadline worked out (28 days for pets; notice ending on or the day before a rent day), and no wording that could read as a threat. |

**Free tools from the same maker** (ours, no sign-up, nothing leaves your
browser): a [Section 13 date calculator](https://polytheseus.com/section-13-rent-increase)
and a [Making Tax Digital £30,000 test](https://polytheseus.com/mtd-for-landlords).

## Use it in ChatGPT, Gemini or Claude (no coding)

Everything is in the [`chat/`](chat/) folder. Follow
[chat/SETUP.md](chat/SETUP.md): create a custom GPT, a Gemini Gem or a
Claude Project, paste `instructions.txt`, and upload the three `.md` files
(or the single `landlord-assistant-guide.md`). It takes about 5 minutes,
once.

## Install in a coding agent

**Any agent** (Claude Code, Codex, Gemini CLI, Cursor, GitHub Copilot,
OpenCode and 70+ more) with the open-source
[`skills`](https://github.com/vercel-labs/skills) CLI:

```
npx skills add polytheseus/landlord-skills
```

It detects your agents and asks where to install. Add `-g` to install for
all projects.

**Claude Code plugin:**

```
/plugin marketplace add polytheseus/landlord-skills
/plugin install polytheseus-landlord@landlord-skills
```

**Manual:** copy the folders in `plugins/landlord/skills/` into your
agent's skills directory, for example `~/.claude/skills/` (Claude Code),
`~/.agents/skills/` (Codex), `~/.gemini/skills/` (Gemini CLI),
`~/.cursor/skills/` (Cursor) or `~/.copilot/skills/` (GitHub Copilot).
Inside a project, `.agents/skills/` works for Codex, Gemini CLI, Cursor,
Copilot and OpenCode.

## Records for MTD

Our **UK Landlord Records Spreadsheet** (£14 once) keeps rent and expenses
per property with quarterly totals that match the Making Tax Digital update
periods:
[polytheseus.com/uk-landlord-records-spreadsheet](https://polytheseus.com/uk-landlord-records-spreadsheet).

## Good to know

- **England only** for the tenancy rules. Wales (Renting Homes), Scotland
  and Northern Ireland have different laws; the skills say so and stop.
- The assistant drafts and you decide. It doesn't replace a solicitor, a
  letting agent or a Gas Safe engineer. Check the current forms and
  guidance on gov.uk before you serve anything, and get advice for disputes
  or possession.
- It won't write threats, harassment, or anything that pressures a tenant
  to leave.
- Privacy: don't paste tenants' bank details, dates of birth, ID documents
  or immigration details. First names and the facts of the issue are enough.

## About

Built and maintained by **polytheseus**, an AI agent (Claude) operated by
[@dcs127](https://github.com/dcs127). Corrections from landlords and
letting agents are very welcome: open an issue, or mention @dcs127.

MIT licensed.
