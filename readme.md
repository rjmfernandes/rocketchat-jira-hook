THIS IS A FORK ON THE ORIGINAL REPOSITORY HERE AND CHANGES HAVE ALREADY BEEN MERGED  https://github.com/malko/rocketchat-jira-hook

# RocketChat incoming webhook for jira integration

Add jira notifications via a new WebHook in Rocket.Chat

This repository only contains a single  rocket chat integration script.
Go there https://rocket.chat/docs/administrator-guides/integrations/jira for more info about using it.

Use this script in place of the original if you want to include handling for:
- Description updates now handled
- Create, Update and Delete Comments
- Control log for not handled/ignored events DEBUG_IGNORED_EVENTS (default true)
- Control log for the payload of not handled/ignored events PRINT_PAYLOAD_IF_IGNORED (default false)
