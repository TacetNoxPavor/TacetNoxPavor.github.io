[back](../index.md)
# Magister
#### A Twitch.tv bot built using a modified version of the PircBotX framework

This bot is the first one that I worked on for the Twitch.tv streamer Tritemare.

It was created as a replacement/update to a bot that had been initially created by a previous
member of the chat who was going to be stepping down and needed to be maintained, however I was
more comfortable with Java as opposed to Python.

Building this bot resulted in my promotion to a Moderator for the stream as it showed I was much more involved
than an average viewer in maintaining a positive stream chat experience, which I still hold to this day.

#### Tasks To Finish
- [ ]  Implement Optimum bot functionality (if still needed going forward)
- [ ]  Remove Chase Emotes from emote spams.
- [x]  Fix msg-param-months issue
- [ ]  Convert bot from PircBotX to Twitch4J

```Java
msg-param-cumulative-months -- 34 // This is what I need to use.
msg-param-months -- 0 //This is what I was using.
msg-param-should-share-streak -- 1
msg-param-streak-months -- 1 //Can implement this.
```

#### Commands

| Command | Description | Availability |
| :-----  | :---------- | :------------ :|
| `!addname <user>=<knight name>`| Add a knighted subscriber's name to the database | **Mod Only** |
| `!editname`| Alter a knighted subscriber's name in the database | **Mod Only** |
| `!addrule <rule>`| Adds a rule to the list | **Mod Only** |
| `!removerule` <rule #> | Removes the rule at the given index | **Mod Only** |
| `!listrules`| Show current rules | **Anyone** |
| `!clearrules`| Clear the list of rules | **Mod Only** |
| `!name <username>`| Get the Knightly Name of the provided user | **Anyone** |
| `!myname`| Get the Knightly Name of the command issuer | **Anyone** |
| `!dance`| Spam the triteD and triteM emotes | **Anyone** |
| `!love`| Spam the triteL emote | **Anyone** |
| `!hype`| Spam the triteH emote | **Anyone** |
| `!woo`| Spam the triteY emote  | **Anyone** |
| `!rip`| Spam the triteO emote  | **Anyone** |
| `!time <description>` | Co-op command with Moobot to generate a highlight link with the given title | **Anyone** |



[back](../index.md)
