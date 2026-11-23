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

## Gentle rhythm

| Routine | When (US Eastern) | Agent |
| --- | --- | --- |
| Weekly founder brief | Mondays 8am | Chief of Staff |
| Substack draft | Tuesdays 9am | Content & Marketing Lead |
| 2 TikTok filming packages | Wednesdays 9am | Content & Marketing Lead |
| Etsy listing or refresh | Thursdays 9am | Etsy & Sales Lead |
| Monthly plan | 1st of the month, 9am | Chief of Staff |

Change times or the timezone in `.paperclip.yaml`.

## Starter tasks

- Founder kickoff and 30-day plan (Chief of Staff)
- Substack audit and 8-week topic list (Content & Marketing Lead)
- Low-pressure TikTok launch plan with the first 6 filming packages (Content & Marketing Lead)
- Finish the Etsy relaunch: clean up old-shop leftovers and publish the first listings (Etsy & Sales Lead)
- First 5 product ideas (Product Designer)

## Getting started

```sh
paperclipai company import --from companies/killing-it-kinda
```

## References

- [Agent Companies specification](https://agentcompanies.io/specification)
- [Paperclip](https://github.com/paperclipai/paperclip)
