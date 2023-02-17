# Getting Started With ServerProtector

To get started with ServerProtector, first you need to invite the bot using [this](https://discord.com/oauth2/authorize?client_id=785828822414393345&permissions=313540&scope=bot) link.

Once you have added ServerProtector to your server, you need to setup ban syncing, owner and staff roles and the log channel.

> the prefix for ServerProtector is `@ServerProtector` (A mention of the bot)

To enable ban syncing, use the `sync enable` command (see [commands/sync](/commands/sync#enable))
- Before you can use ban syncing, you need to have your server approved, please join the support server [here](https://support.serverprotector.me) to have your server approved for ban syncing
- You can still use ban logging and other features without having your server approved

To set the owner and staff roles, use the `config staff/owner` command followed by the role you want to assign staff/owner permissions to (see [commands/config](/commands/config#staff))

To set the log channel for known banned users, use the `config channel` command (see [commands/config](/commands/config#channel))

After setting these options, the bot will automatically sync existing bans and sync new bans, and will log known user bans in the channel you selected with the `config channel` command. 