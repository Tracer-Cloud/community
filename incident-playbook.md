# Incident Playbook

Use this as a quick-response guide. Always use the configured moderation bot's commands, not native Discord moderation tools.

### **__If you do any moderation actions because of something in the Voice Channels, please use the voice-report command as well so there is evidence of it for when people complain to the Admin or leads.__**

## Common Moderation Cases

These are punishment times we should standardize on for these common offenses.

### Self Promotion outside of #showcase

```mermaid
flowchart TD
    A[First Offense] --> B{Only message<br/>and joined within 2 weeks?}
    B -->|Yes| C[Ban]
    B -->|No| D[24 hour mute]
    D --> E[Second Offense]
    E --> F[Ban]
```

Discord invites are not allowed anywhere, including #showcase.

### #showcase forum moderation

#showcase is a forum channel for members to show off projects, setups, and other promotional work. It is intentionally moderated more lightly than general chat. Promo that would be removed elsewhere is allowed here, as long as it follows the rest of the server rules.

Remove or moderate #showcase posts for Discord invites, crypto/trading/prediction-market content, NSFW or graphic content, harassment, spam, trolling, or anything that is clearly unsafe for the community. Escalate repeat #showcase abuse to a lead or the Admin.

### #introductions moderation

#introductions is for member introductions only. Remove promotional posts, project advertisements, link drops, and recruitment messages. Light enforcement: delete the message and DM the user to redirect them to #showcase or the relevant channel. Repeat offenders should get a standard self-promotion mute.

### Trolling in chat

If they are a brand new join, they should be banned. Otherwise, they should get a 24 hour mute.

### Crypto / Trading / Prediction Markets

If they're joking about it, use a 1 hour mute.

If they're serious about it, instantly ban.

__**This is a firm rule, no exceptions.**__

### Hot Mic

Right click and disconnect. If they rejoin with the same, mute for 30 minutes.

### Soundboard Spam

If automod does not handle it, mute for 1 hour.

### Any Rule 3 violations (harassment / hate speech)

First offense is a ban for 24 hours unless it was particularly egregious, in which case skip to a permanent ban. Second offense is a permanent ban.

### Recruiting for jobs / "Does anyone need a developer"

Instant ban.

### Doxxing / personal data

Remove content immediately and ban involved users. Then escalate to the Admin right away.

### Security report leaking into public channels

If a user posts what looks like a security vulnerability, exploit, or sensitive disclosure in a public channel:

1. Delete the message immediately.
2. DM the user to redirect them to the private security reporting flow in [SECURITY.md](SECURITY.md).
3. Notify the Admin and any maintainers on the security contact list.

### Other

Use your best judgement. If a mute is longer than 3 days, it should be a temporary ban instead.
