---
title: 'Utilbot'
sidebar_position: 0
---

## Utilbot - v5.5.9
<span class="cl-timestamp">

*04.04.2021 - 22:00*

</span>

<span class="cl-added">New features</span>

- **Gateway**: The zlib compression is activated

<span class="cl-progress">Bug fixes</span>

- **MOTD**: The MOTD now loads normally again. We were hitting some rate limits, since we've activated sharding.

## Utilbot - v5.5.0
<span class="cl-timestamp">

*01.04.2021 - 23:30*

</span>

<span class="cl-added">New features</span>

- **Sharding**: The bot is now Sharding ready
- **Gateway**: The bot reports some data now to the Gateway

<span class="cl-progress">Bug fixes</span>

- **ClearCommand**: Command now uses bulk-delete endpoint
- **HelpDMCommand**: Response to Help Command is actually sended now
- **HelpDMCommand**: Removed deprecated method
- **HelpDMCommand**: Fixed Typo in the Command

## Utilbot - v5.4.0
<span class="cl-timestamp">

*30.03.2021 - 23:30*

</span>

<span class="cl-added">New features</span>

- **CORE**: Added Migrations
- **VOICE**: Added Regions to Node

<span class="cl-progress">Bug fixes</span>

- **CORE**: Fixed Database problems at startup
- **VOICE**: Fixed Volume Command

## Utilbot - v5.2.14
<span class="cl-timestamp">

*30.01.2021 - 00:05*

</span>

<span class="cl-added">New features</span>

- [<a href='https://jira.herrtxbias.net/browse/UT-62'>UT-62</a>] - Private Channel Creator (Generate Template)
- Added US Voice Nodes
- Added automatic node choice, based on the server region
- The bot now deafens himself, to save bandwith

## Utilbot - v5.2.13
<span class="cl-timestamp">

*18.01.2021 - 23:00*

</span>

<span class="cl-progress">Bug fixes</span>

- [<a href='https://jira.herrtxbias.net/browse/UT-61'>UT-61</a>] - Delete Rule / TeamList Message, if function gets disabled via the Webinterface.

## Utilbot - v5.2.12
<span class="cl-timestamp">

*18.01.2021 - 22:00*

</span>

<span class="cl-progress">Bug fixes</span>

- Internal bugfixes
- [<a href='https://jira.herrtxbias.net/browse/UT-37'>UT-37</a>] - Rule / Teamlist Message gets created, when these functions get enabled via the Webinterface.
- [<a href='https://jira.herrtxbias.net/browse/UT-59'>UT-59</a>] - Fixed Clear Command deleting one message too few.

## Utilbot - v5.2.11
<span class="cl-timestamp">

*18.01.2021 - 00:50*

</span>

<span class="cl-progress">Bug fixes</span>

- Fixed an Issue where the timestamp of a global ban wasnt't added.

## Utilbot - v5.2.10
<span class="cl-timestamp">

*16.01.2021 - 20:00*

</span>

<span class="cl-progress">Bug fixes</span>

- We have made some minor bugfixes and updated all the dependencies.

## Utilbot - v5.2.4-p4
<span class="cl-timestamp">

*22.11.2020 - 00:50*

</span>

<span class="cl-added">New features</span>

- We have **added the possibility to give an argument to the clear command**. Head over [here](/docs/moderators/clear) to get more Information.

## Utilbot - v5.2.4-p3
<span class="cl-timestamp">

*20.11.2020*

</span>

<span class="cl-progress">Bug fixes</span>

- Some minor Bugfixes, affecting the music player.

## Utilbot - v5.2.1
<span class="cl-timestamp">

*30.10.2020*

</span>

<span class="cl-added">New features</span>

- Connection to v1 of the own Utilbot Backend Gateway. 

## Utilbot - v5.1.23
<span class="cl-timestamp">

*25.10.2020*

</span>

<span class="cl-progress">Bug fixes</span>

- Implemented many Bugfixes.

<span class="cl-added">New features</span>

- Connection to the own Utilbot Backend Gateway. 

## Utilbot - v4.5.1
<span class="cl-timestamp">

*14.05.2020*

</span>

<span class="cl-progress">Bug fixes</span>

- Implemented many Bugfixes, like the "Member Edited" Event, or the Join / Leave Event.

<span class="cl-added">New features</span>

- Added the first endpoint for the new Webinterface

## Utilbot - v4.5.0
<span class="cl-timestamp">

*23.04.2020*

</span>

<span class="cl-progress">Bug fixes</span>

- Major Bug fixes (too many, to mention)
- Changed to TypeScript

## Utilbot - v4.2.4
<span class="cl-timestamp">

*20.04.2020*

</span>

<span class="cl-progress">Bug fixes</span>

- added whois command

## Utilbot - v4.2.3
<span class="cl-timestamp">

*20.04.2020*

</span>

<span class="cl-progress">Bug fixes</span>

- better organization of the code (it's modular now, so i don't need to restart the whole bot every time)

## Utilbot - v4.2.0
<span class="cl-timestamp">

*17.04.2020*

</span>

<span class="cl-progress">Bug fixes</span>

- fixed crash, during playing songs sometimes

<span class="cl-added">New features</span>

- Poll Feature

## Utilbot - v4.1.1
<span class="cl-timestamp">

*13.04.2020*

</span>

<span class="cl-progress">Bug fixes</span>

- Changed something in the `play / queue` command
- if a song is currently playing, `!play` will now add the searched song to the queue, instead of just starting it
- `!queue` will also start the queued song, if no song was playing before

## Utilbot - v4.1.0
<span class="cl-timestamp">

*10.04.2020*

</span>

<span class="cl-progress">Bug fixes</span>

- Fixed little bug in the !info command

<span class="cl-added">New features</span>

- added the Multi-Language Support
- added German as Language
- added English as Language (not all strings were already translated)

## Utilbot - v4.0.1
<span class="cl-timestamp">

*09.04.2020*

</span>

<span class="cl-progress">Bug fixes</span>

- Fixed the Song Queue

<span class="cl-added">New features</span>

- Implemented the new voice Backend Lavalink