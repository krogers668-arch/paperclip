# Killing It Kinda

An AI team that helps run **Killing It Kinda**, a digital brand about the little things in life: noticing beauty and humor in tiny details and embracing the bittersweet.

The founder is the CEO and final decision maker. A small team of AI agents works behind the scenes on planning, content, the Etsy shop and new products. Nothing is published, priced or spent without the founder's approval.

## How it works

Hub-and-spoke: the founder sets direction, the Chief of Staff turns it into a weekly plan, and three specialists do the work and report back.

```
Founder (CEO, you)
└── Chief of Staff
    ├── Content & Marketing Lead   (Substack, TikTok)
    ├── Etsy & Sales Lead          (Etsy shop, pricing)
    └── Product Designer           (new products)
```

| Agent | Reports to | Owns | Skills |
| --- | --- | --- | --- |
| Chief of Staff | Founder | Plans, calendar, weekly brief, approvals | paperclip, kik-brand-voice |
| Content & Marketing Lead | Chief of Staff | Substack, TikTok | paperclip, kik-brand-voice, kik-visual-identity |
| Etsy & Sales Lead | Chief of Staff | Etsy listings, pricing, sales | paperclip, kik-brand-voice, kik-visual-identity |
| Product Designer | Chief of Staff | New product briefs (digital first) | paperclip, kik-brand-voice, kik-visual-identity |

## Organized by platform and product

| Project | Owner | What lives there |
| --- | --- | --- |
| Operations | Chief of Staff | Monthly plan, weekly brief, decisions |
| Substack | Content & Marketing Lead | Weekly newsletter |
| TikTok | Content & Marketing Lead | Faceless-first launch, filming packages |
| Etsy Shop | Etsy & Sales Lead | Listings, pricing, shop health |
| Product Development | Product Designer | One task per product idea |

## Lean mode

The team is set up to use as little as possible while still moving the business forward:

- Every agent runs on Sonnet (set in `.paperclip.yaml`), with monthly caps of $10 for the Chief of Staff and $5 for each specialist.
- Only one routine runs on a schedule: the **weekly founder brief**, Mondays 8am US Eastern. The Chief of Staff then starts the single highest-priority unblocked issue and assigns it.
- Specialists have no timers. They wake when the Chief of Staff assigns them an issue.

## 90-day plan

| Milestone | Target | Issues |
| --- | --- | --- |
| M0 Setup | This week | Import the team and set the caps (founder) |
| M1 Etsy relaunch | First week of December | Shop cleanup pack, E-Cards listing, icon and banner, publish (founder), holiday planner decision, poem lines (founder), Poem Cards |
| M2 Founding batch | December to mid-January | Payment and form, poem template, outreach (founder), order tracker, batch review |
| M3 Voice back on | January | Substack topic list, first letter, TikTok launch plan, first two posts (founder) |
| M4 Next product | February | Rank the catalog, build the winner |

Founder tasks have no assignee; the Chief of Staff lists them in the Monday brief, three at most, each 30 minutes or less. Labels (M0 to M4), priorities and blockers are set in `.paperclip.yaml`.

## Getting started

```sh
paperclipai company import companies/killing-it-kinda
```

## References

- [Agent Companies specification](https://agentcompanies.io/specification)
- [Paperclip](https://github.com/paperclipai/paperclip)
