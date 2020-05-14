[Discord]: https://github.com/Andre601/Discord-Links/blob/master/docs/server/discord
[Minecraft]: https://github.com/Andre601/Discord-Links/blob/master/docs/server/minecraft

[badge]: https://github.com/Andre601/Discord-Links/workflows/Deploy%20Site/badge.svg
[action]: https://github.com/Andre601/Discord-Links/actions?query=workflow:"Deploy+Site"

# Discord Links
[![badge]][action]

This is the repository of the Discord Links site, which contains invites to various Discord server.

The Server are split up into separate categories, which are listed below.

## Categories

- [Discord]  
Server revolving around Discord related stuff, being it official server by Discord or community-driven ones.
- [Minecraft]  
Server for Minecraft-related topics. From vanilla to modded Minecraft (i.e. Spigot).

Have an idea for a category not listed here?  
Open a new issue and let us know!

## Add Server
Do you know a server that should be added?  
Follow the below instructions to add it and make a Pull request!

### Structure
The Structure of a Server entry is simple:  
```markdown
----
#### <verified?/partnered?> <server name>
<description>

**Invite**:  
<discord invite>
```

- `<verified?/partnered?>` should be replaced with either `:discord-verified:` or `:discord-partner:` when the Discord is partnered/verified. Leave this away if the Discord isn't neither of those.
- `<server name>` is the official name of the Discord. The Server should be added in alphabetical order (The above text doesn't affect this).
- `<description>` should either be a short summary of the Discord, or a official tagline it has.
- `<discord invite>` has to be a `discord.gg` invite! Any other invite (including `discord.com/invite/`) are not allowed. If the Discord is verified/partnered, make sure to use the vanity URL they have.

#### Example
```markdown
----
#### :discord-verified: Discord Developer
Server all about development with/for Discord (i.e. Bot development).

**Invite**:  
https://discord.gg/discord-developers
```
