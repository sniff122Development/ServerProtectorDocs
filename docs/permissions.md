# ServerProtector's Permissions

This page will outline the permissions ServerProtector requires in your server and why they are required.

## View Audit Log
ServerProtector requires view audit log permissions to be able to fetch ban reasons for users you have banned

## Ban Members
For a bot (or user) to be able to access the ban list on Discord, they require the Ban Members permission. ServerProtector will not ever ban anyone from your server without explicit permission beforehand.

## Send Messages
The bot obviously needs to be able to reply to commands from you and your staff. If you want to deny ServerProtector to view a specific channel, remove its Read and Send Messages permission in the channel

## Embed Links
This permission allows the bot to send embed messages (like the ban log, replies to commands, etc)

## Attach Files
This permission isnt required right now but may be used in future for features like evidence attaching

## Add reactions
This permission is used by the ban profile command to provide a reaction menu to scroll through a user's ban profile if they have a multitude of bans

## Use External Emojis
This permission is not used right now but will allow the bot to use any emoji. This may be used to have different reactions or other emoji uses

# Note:
No bot needs the Administrator permission. This is potentially dangerous, especially if someone were able to gain unauthorised access to the login token for the bot. Only give the minimum permissions for the functions you will use for the bot. This guidence covers all bots you may use in your server, not just ServerProtector.