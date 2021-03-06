# Chat++ - Improved chat for Our World of Text.
Chat++ is a script that extends the default OWOT chat to have tons
of new features and remove various annoyances. Give it a shot!

## Current feature list:
* manual chat filtering
* `/r` command to quickly reply to last DM
* ability to `/tell` using username with `@`
* ability to see anon colors
* gridsize aliases (default, square, half, and mixed)
* ability to clear chat with `/clear`
* `/whois <user|id>` which shows ID, chat color, account name, and last message time.

## Planned features:
* chat filter (with automatic filtering)
    * messages sent too quickly (including DMs)
    * identical messages sent within 90 seconds
    * filter out too many consecutive chars
* ability to ping users (can be disabled)
* client-side ranks (/`ranks \[list/add/del\] ...`)
* allow other users to see your custom rank
* formatted chat (no images)
* tabs for chat menu; ability to open multiple worlds
* /addchat command for the funne
* a /settings command for various things such as chatfield size defaults
* improved versions of existing commands
    * `/color text <color>` and `/color chat <color>` instead of just `/chatcolor`
    * `/warp world` and `/warp server`
    * improve `/whoami` command to have more details and a preview message
* ability to change chat font through `/settings`
* chat theme manager and auto-loading
    * ability to have chat theme sync with canvas theme
* `/me <message>` like IRC
* allows /clear to take an optional argument to clear a specific person's messages only