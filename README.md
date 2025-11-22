# NFLDex-Discord-Bot-Privacy-Policy

# Things to Note

**“Application” or “Discord Application”** refers to the NFLDex Discord bot and its associated owners and servers.

**“Data”** refers to information stored by an individual instance of the bot, including personal data.

**“Bot” or “Instance”** refers to the running copy of the NFLDex application and its associated data.

**“Player”** refers to any virtual item intended for collection within NFLDex, such as NFL player cards, team tokens, or similar virtual resources.

**“Application Owner”** refers to the individual with direct control over the Discord application, including authentication access and instance-related data.

**“NFLDex Staff Team” or “Staff Team”** refers to the application owner and the users they authorize to assist with moderation or management.  
A list of staff members is available on the Official NFLDex Discord Server.

---

# Open Source

NFLDex is built upon the open-source code available at:  
https://github.com/laggron42/BallsDex-DiscordBot

A copy of the license (MIT) can be found within that repository.

The NFLDex instance runs an unmodified copy of this open-source code.  
While the version may not always be the latest, **no local modifications** will be made unless announced.  
Any changes will be communicated in the Official NFLDex Discord Server.

Users may review the source code to understand how data is managed, along with this policy.

---

# What Data Is Collected?

NFLDex collects the following information from Discord:

- **User IDs** — Used to identify users within the NFLDex database  
- **Server (Guild) IDs** — Used to store server-specific settings  
- **Channel IDs** — Used to determine where players can spawn  

Additionally, NFLDex generates and uses the following internal data:

- **A list of players owned by each user**  
- **A history of trades involving players**, including previous owners of each player  

---

# How the Data Is Stored

All data is stored on a PostgreSQL server hosted on a Docker Desktop Virtual Machine operated by **Bing**, the owner of the NFLDex instance.

All communication between the bot and the database is handled locally using Tortoise ORM.

---

# Access to the Data

The only persons allowed to access the data are the **application owners**.

The application owner may interact with the bot and its administrative interface.  
Only **Bing** has direct access to the hosting machine.

The F1dex moderation teams do not have access to the data.

The data may never be made available to the public, and its access must be secured accordingly.

---

# Your Rights

You may request a copy of your personal data or request deletion of your data.

To do so, you may contact the Application Owner by joining the [Official NFLDex Discord Server](https://discord.gg/xNpZkq9ErU) and sending a direct message to **Bing or Joey**.

Requests may also be submitted directly to **one of the owners** if available.
