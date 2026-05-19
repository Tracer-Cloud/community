# Discord Moderation

OpenSRE uses `<TBD: moderation bot, e.g. Sapphire / Barnacle / Carl-bot>` to manage moderation needs.

## Moderation Area

See the [README](README.md) for the current Community Staff areas, leads, and elevated permission groups.

Here are some common commands you would use to moderate the server.

- `/ban` - This permanently (or temporarily) removes a user from the server and prevents them from joining back. They will not be able to speak or read messages. You must specify a user and a reason, and a duration is optional (the user will be unbanned after the time ends), otherwise it will default to permanent.
- `/mute` - Times out a user. They will not be able to speak for the duration of the timeout but will still be able to read messages. You must specify a user and reason, and it's recommended to specify a duration, otherwise it will default to an hour.
- `/warn` - This does not impair the user's ability to talk in the server. It's simply a mark on their record. More of a "stop doing that" before escalating to a mute or ban. Requires a user and reason.
- `/caselist` - This lets you see a user's history of warns/mutes/bans from different moderators.

When you're moderating, please keep in mind that the user can see everything you put in except for the mod notes section.

- Reason = the main reason they see and that's logged in previews like `/caselist`
- Verified Proof = the message that was reported
- Proof = anything you type in as evidence

## GitHub Moderation

Some users here have access to moderate users on GitHub. Maintainers or community staff can ping them for situations on GitHub in #github-moderation, and full guidelines are kept there.

## Appeals

Users can appeal their mutes and bans at `<TBD: appeals URL>`.

Community Staff can review these either in the #appeal channel or on the appeals dashboard at `<TBD: appeals dashboard URL>`.

Users can also report a moderator through that same form.

Appeals should be handled by someone other than the originating mod. If you issued the action, do not review that appeal — ask another mod or your lead/admin to handle it.

When you accept or deny an appeal, the user will see the reason you put in, in the format `Your appeal was accepted. ${reason}`.

## Working in Chat

`<TBD: utility-bot commands for redirecting users in chat, e.g. /say-help, /say-showcase. Link to the commands source if applicable.>`

Additionally, the Server Guide has a large amount of common questions about the Discord server itself. This can be found at the top of the channel list.

## Activity Expectations

Stay reasonably active and engaged with the community. This can include sending messages, being present in voice, answering support questions, or participating in mod discussions.

Check staff update announcements and react to them once read. Any reaction is fine; this helps leads confirm staff are seeing important updates.

### Inactivity / Leave of Absence (LOA)

If you will be away for multiple days or unable to complete your duties, post an inactivity log in the appropriate staff channel and ping your lead, so leads can reassign coverage. There is no hard limit to LOA length, but please avoid radio silence.

Format:
- Dates: 12th June 2025 - 1st July 2025
- Reason: Optional. If you don't want to share publicly, DM a lead or the Admin.

Consider muting server notifications while you are away.

### Activity Warnings

If you appear inactive for an extended period, you may receive an activity warning by DM. The warning will link the activity expectations and LOA guidance, and you will have two days to respond. Leads/Admin will discuss your availability from there.

Repeated inactivity after a warning may result in removal from Community Staff.

## Biggest Rules

If you didn't read anything else, read this:

- When in doubt, mute for 1 hour with the phrase "pending moderation". Do not ban users instantly.
- If you are unsure, ping online moderators in #moderators or the relevant staff channel and ask them for help.
- If you are moderating someone for a specific message, report it using the regular report flow and then take action from there. This way we have a record of the specific message alongside the regular reason for the mod action, which is extremely helpful for appeals and transparency.
- If you're doing a voice moderation, you must (if at all possible) use the voice-report command so we have a log for if/when they appeal or complain in the Admin's DMs.
- DO NOT use the native Discord moderation tools. Always use the moderation bot's commands, because otherwise we have no transparency and the user gets no information about why they were moderated.
