#Guide to Twitch Moderation Tool

Link to discord support server : https://discord.gg/EgTM5ynWhz

1. Dashboard
   * Total Users : Shows you current users in your chat
   * Messages : Shows you total messages (While App is connected) and how many messages per minute
   * Moderation Actions : Shows you total Flagged messages since app has been connected
   * Connect Bot : This connects the app to discord (Saves Data so you dont have to re-enter it each time you open the app)
       * Twitch Channel : The Channel Username to connect to
       * Client ID : Your Client ID found from the Application you made on dev.twitch.tv
       * Client Secret : The secret you generated from the Application you made on dev.twitch.tv
           * Reset Session : This is if you need to relink due to new features being added and needing new permissions to be enabled
           * Cancel : This exits connecting menu
           * Authorize and Start : This redirects you to the Twitch auth (if first time/Reset Session has been used) or Starts the connection (If previously connected)
  * Live Chat Monitor : Shows the connected Channels messages (Shows Global Emotes if downloaded)

2. Moderation
   * Auto-Delete Violations : Enable/Disable Auto-Deletion of messages that get flagged
   * Banned Words : Single words you want flagged
   * Word Combinations : 2-4 Words that could be seperated or throughout a message you want flagged 
     [E.g: Quality, Check, www | Quality Stream, Check here www .example. com | This will get flagged]
   * Banned Sentances : This flaggs a WHOLE sentances [Example: Copypasta's]
   * Violation Logs : This shows you the user, Their message and the reason it got flagged with an option to ban the user

3. Banned Users : Auto Refreshes if not in section
   * Refresh List : This will refresh the list if you havent left the section
   * Current Bans : This shows Banned users and their reason they were banned. Has unban button to unban the user
  
4. Settings
   * Emote Tools : Downloads all twitch global emotes, This allows the live chat monitor to display twitch global emotes with fast render
