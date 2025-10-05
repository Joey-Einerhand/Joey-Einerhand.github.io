---
title: "Discord Multiclient Launcher"
subtitle: "Easily launch multiple seperate discord clients <br> 10+ Github stars, 1000+ downloads <br> Powershell"
project_type: "(Powershell Script)"
is_old_project: no
page_type: "project_for_frontpage"
banner_image: "/assets/images/discordmulticlientlauncher/banner.png"
display_priority: "4"
hide:
  - navigation
  - toc
---
<h1 class="text-center">[Powershell Script] Discord Multiclient Launcher</h1>

![Full Logo](../assets/images/discordmulticlientlauncher/banner.png){ align=right width=50% }
<br>
<b>Code and .exe available on :material-github: [Github.](https://github.com/Joey-Einerhand/discord-multiclient-launcher)</b>
<br>Currently at 10+ stars and 1.000+ downloads!

A Powershell script to lauch multiple discord clients, with the ability to log into each client with a different account.</p>


I had a problem: I wanted to launch multiple instances of the chat app Discord, each with a different account logged in.  Launching the chat application multiple times automatically logged you into your already logged-in discord account. Logging out of one of the clients logged you out of all.
There is a solution. Namely, going into Discord's install directory. 
For example, `\AppData\Local\Discord\app-0.0.309\Discord.exe`. <br>
This login problem is solved by making a 'shortcut' of this EXE and adding `--multi-instance` in the `Target:` property of the shortcut (This solution was suggested on [reddit](https://www.reddit.com/r/discordapp/comments/kk6rp7/how_to_actually_easily_multiclient/))

New problem: As you can see, the URL to the discord.exe example above includes the version number `app-0.0.309`! This means that every time discord is updated, the above process needs to be repeated. A new shortcut for a new .exe has to be created, etc.

This project is a powershell script which automatically determines the highest discord version installed (There can be multiple installed at one time) and starts the appropriate .exe with the `--multi-instance` flag, so the user never has to manually follow the above process again; The user only has to download the .exe version of the script and execute it.

This project was written in Powershell and is build to an .exe with Github Actions.

<br>

