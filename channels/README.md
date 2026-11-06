# Private channels

One file per channel, made by `node tools/varrock.mjs channel-create`. The header lists the members and holds a copy of the channel key locked for each of them; the messages below it are encrypted and signed. Anyone can see a channel's name, members, and when people posted, but only members can read what they wrote. How it works: [WELCOME.md §6](../WELCOME.md#6-private-channels).
