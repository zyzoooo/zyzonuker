# zyzonuker

# Overview
This script is a Discord bot designed for server management tasks. It includes commands to perform various administrative actions, including role and channel creation, banning members, and more. The bot is configured with a specific user ID that grants access to its powerful commands. To understand the script better its HIGHLY recommended to review the source code

## FYI: to set the guild it preforms the commands in, DM the bot ur using "!set_guild (ID)" and then type the commands in that server

## Features:

!zyzo: Changes the server's name, deletes all channels, and bans all members except the bot's user
!set_guild: Targets a specific server for further commands
!create_role: Creates multiple roles in the targeted server
!create_channel: Creates multiple text channels in the targeted server
!webhook_spam: Creates webhooks in all text channels and sends spam messages
!delete_channel: Deletes all channels in the targeted server
!delete_role: Deletes all roles in the targeted server, except the default role and the bot's highest role
!ban: Bans all members in the targeted server except the bot's user



## Configuration:
Bot Token: Replace "token goes here" with your bot's token
Authorized User ID: Replace "user id here" with your Discord user ID to grant control of the bot



## Usage:
Commands: Prefix commands with !. Available commands include !zyzo, !ban, !webhook_spam, !delete_channel, !delete_role, !create_channel, !create_role, and !set_guild
Permissions: Only the user with the specified AUTHORIZED_USER_ID can execute the commands



## Requirements:
Python 3.8 or higher
discord.py library
Notes
Security: Ensure only trusted users have the AUTHORIZED_USER_ID to prevent misuse
Logging: The bot logs errors and critical messages


## Use responsibly and avoid malicious activities.
