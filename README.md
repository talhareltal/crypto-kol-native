# crypto-kol-native

Before you pay a KOL, get Claude to tell you if it's worth it.

Built for crypto CMOs and founders who'd rather find out a KOL is wrong for them before the invoice, not after.

More of this, daily: **The Crypto Media Club** on Telegram: [t.me/CryptoMediaClub](https://t.me/CryptoMediaClub)

## The test

A KOL agency sends you this (made-up names):

> "15 KOLs, 4M combined followers, $40K. Half paid in your token. Includes @lumenwhale, 180K followers."

Sounds like reach. Before paying, a good growth lead checks:

- **Are their followers your future users?** Right market, right interests, real people.
- **What did their last sponsored post do?** Did people ask about the product, or just post rockets? Is that project still alive?
- **Is the deal sane?** Paying in tokens means paying someone to sell your token.
- **Can you measure it?** Signups and users who stay, not views.

Most AI tools count followers and call it a great deal. This skill makes Claude check first.

## What you can ask it

- "Should we use KOLs for our launch, or something else?"
- "Here's a post this KOL did for another project. Was it any good?"
- "Here's our KOL shortlist. Who's worth it?"
- "An agency offered us this package. Sign or walk?"
- "We ran a KOL campaign last month. Did it work?"

## What you get back

Short and direct. Something like:

> **Verdict:** Red flag.
> **Why:** Undisclosed paid post, pasted brief, replies that look like a trade.
> **Signals:** No disclosure. Same copy as four other KOLs. Views far above real engagement.
> **Do this:** Pass. Or ask for a disclosed post where they use your product, paid in cash, with a tracked link.

## What's inside

```
SKILL.md                        voice, rules of thumb, routing, output format
references/
  should-you-use-kols.md        which goals KOLs fit, and which they don't
  vetting.md                    audience, engagement, track record, behaviour
  post-review.md                was a KOL's past sponsored post any good
  deal-terms.md                 pay, deliverables, content, protection
  measuring.md                  did the campaign work
examples/
  post-review-teardown.md       what good output looks like
  failure-autopsy.md            what bad output looks like
```

Claude only loads the reference file the task needs.

## Install

**Claude (app):** zip the folder and upload it under Skills in settings.

**Claude Code:**
```
git clone https://github.com/talhareltal/crypto-kol-native ~/.claude/skills/crypto-kol-native
```

**Other agents:** copy the folder into your agent's skills directory (`.agents/skills/` for the cross-agent standard).

## Rules of thumb

- Followers are a price tag, not a result.
- Replies tell you more than likes. Read them.
- A KOL who promotes everything recommends nothing.
- Paying in tokens means paying someone to sell your token.
- An undisclosed ad is a legal risk with your logo on it.
- Judge a KOL by what happened 30 days after their last campaign, not 30 minutes after.
- No KOL campaign beats a bad KOL campaign.

## What it won't do

- Give legal or financial advice. Token promotion has rules: talk to counsel.
- Call a named KOL fake or a scammer. It shows you the signals.
- Help write sponsored posts designed to look unpaid, or plan price talk.

## Also

For earned media (press releases, pitches, coverage): [crypto-media-native](https://github.com/talhareltal/crypto-media-native).

## About

Built by [Tal Shmuel Harel](https://x.com/TalHarelTal), co-founder of Chainstory. Chainstory doesn't sell KOL campaigns, so no horse in this race.

All examples are invented. Any resemblance to a real KOL is a coincidence.

MIT license.
