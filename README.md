# RichPresenceUpdated
Version: 2.0.6 | Downloads: 256,331 | Added: 12/19/22 | Last Updated: 12/19/22 
AutoStartRichPresence
Automatically starts a custom Rich Presence application when you start Discord. Now with support for multiple rich presence profiles!

Setup Tutorial: https://www.youtube.com/watch?v=JIUOreTNj-o

Example

https://discord.com/channels/@me/1021589577548443648

DM me @ jugg#0001 or create an issue at https://github.com/lacahpone/RichPresenceUpdated/issues) for support.

Troubleshooting
"Rich Presence client ID authentication failed. Make sure your client ID is correct."
Check your client ID in the plugin settings to make sure that it matches the client ID for your Rich Presence app in your Discord Applications page.
Close Discord, then open the Task Manager (or whatever process manager your OS has) and force kill any remaining Discord processes. Sometimes, Discord orphans some processes for unknown reasons and it messes with IPC.
Your computer was not connected to the Internet when the plugin started. Make sure you are connected to the Internet and restart the Discord client.
"Failed to set Rich Presence activity."
You have another application running that has its own Rich Presence, which is conflicting with this plugin. Close all other applications that use Rich Presence and restart the Discord client.
Your computer was not connected to the Internet when the plugin started. Make sure you are connected to the Internet and restart the Discord client.
Ensure that your button labels are less than 32 characters long. The button URLs should not be excessive in length.
Wait 24 hours. Discord may take a while to process your images.
The Rich Presence is not showing 10 seconds after it was started, and there are no visible errors.
Make sure the plugin is on.
Go to User Settings > Game Activity and turn on Display currently running game as a status message. If it was already on, turn it off, wait 5 seconds, and turn it back on.
Disable the experimental RPC event injection setting if you have it enabled, and restart Discord.
Wait 3 hours while your Discord client is continuously open. Sometimes, Discord may take a long time to display or update your Rich Presence.
Buttons do nothing when clicked on.
The Discord client does not allow clicking your own buttons. Ask someone else to test them, or use an alternate account.
None of these solutions work.
