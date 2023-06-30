# Pizza Tower FMOD Studio Project Recreation

[![Open Issues](https://badgen.net/github/open-issues/Raltyro/Pizza-Tower-fspro-Recreation)](https://github.com/Raltyro/Pizza-Tower-fspro-Recreation/issues)
[![Open Pull Requests](https://badgen.net/github/open-prs/Raltyro/Pizza-Tower-fspro-Recreation)](https://github.com/Raltyro/Pizza-Tower-fspro-Recreation/pulls)
[![License](https://img.shields.io/github/license/Raltyro/Pizza-Tower-fspro-Recreation?logo=github)](LICENSE.txt)
[![FMOD Studio Version](https://badgen.net/badge/FMOD%20Studio%20Version/2.02.00%20-%202.02.17/orange)](https://www.fmod.com)

[![PT FSPRO Repository Image](.github/readme/banner-fspro.png)](https://gamebanana.com/tools/13432)

This project/tool aims to be atleast somewhat 1:1 recreation and to make improvements/fixes to Pizza Tower sounds,
while making them easier to mod in the sounds by just opening this with FMOD Studio instead of using other unofficial tools,
allowing for any custom events/sounds/groups/etc to be able being added in the game!

To start with this, read the wiki here!  
https://github.com/Raltyro/PT-FSPRO-Recreation/wiki

## Opening the project
First of all, the program that needs to open this is [FMOD Studio](https://www.fmod.com) (which what Pizza Tower uses for it's sounds),
it's free! It need to be the version above than 2.02.00. And ofcourse, you'll need to have a knowledge on how to use FMOD Studio to modify

[![Downloading FMOD Studio Preview](.github/readme/download-fmod.png)](https://www.fmod.com/download)

[Here a quick Youtube Video on how to use FMOD Studio](https://youtu.be/7A1HMOsD2eU)

After installing FMOD Studio, don't open the project yet, it needs to have the Pizza Tower Assets first, to do that,
extract the Pizza Tower banks files at `sound\Desktop` to wav with the [Unofficial FMOD Banks Tool](https://gamebanana.com/tools/12100)  
([or you can grab the compressed version of the assets here instead](https://mega.nz/file/gQwDULaJ#rdS4_qkBaTA7i9y87lAO4z3ZJBi0MvlG5jz5-sf_o4M))

Put it into the repository `Assets` folder, and you should be good to go to open this with FMOD Studio!

## Modifying
When modifying the project, please to make sure to use the event templates that's provided in event tabs when your adding a new events, without these, the events thats been made from scratch would have unexpected changes (that is being unaffected with ingame volumes, effects, not in the right mixer bus, etc)

![PT FSPRO Event Defaults](.github/readme/event-defaults.png)

any Pull Requests that doesn't do this will be ignored/held for reviews until it get resolved.

## Credits
* [Raltyro](https://github.com/Raltyro) ([Gamebanana](https://gamebanana.com/members/1777465), [Twitter](https://twitter.com/Raltyro)) - Maintainer
* [AwfulNasty](https://github.com/AwfulNasty) ([Gamebanana](https://https://gamebanana.com/members/2539314)) - MAJOR Contributions on adding bunch of sfx events, linking this fspro with PT original banks, and etc
* [theCarso](https://github.com/theCarso) - Contributions on helping to make linking this fspro with PT original banks possible (Making an automated script on applying the GUIDs)
* [SlawekNowy](https://github.com/SlawekNowy) - Contributions on helping to make linking this fspro with PT original banks possible (Exporting the GUIDs)
* [MeliaDev](https://github.com/MeliaDev) ([Gamebanana](https://gamebanana.com/members/2657982), [Twitter](https://twitter.com/darkdagirl)) - Contributions help on adding events
* [thecubitosishere](https://github.com/thecubitoishere)  ([Gamebanana](https://gamebanana.com/members/2513917), [Twitter](https://twitter.com/TheCubitoIsHere))- Contributions help on adding events

Without these Contributors, this project wouldn't be possible without them!
Thank you everyone for those who contributes this project!