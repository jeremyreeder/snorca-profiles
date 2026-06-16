# snorca-profiles
This repo consists of custom-tuned machine, filament, and process profiles for Snapmaker Orca. Its purposes are as follows:
- To improve print quality compared to factory-provided profiles.
- To increase print efficiency in terms of time, material usage, and success-to-failure ratio.
- To optimize temperature settings for a variety of good filament materials.
- To provide a set of easily navigated process profiles, each consisting of my best known default print settings for a particular purpose.

There are no universal *best* settings, of course, as it always depends on what you're making.

## Installation
For Linux AppImage version of Snapmaker Orca: (paths differ by platform)
```
$ cd ~/.config/Snapmaker_Orca/user
$ git clone https://github.com/jeremyreeder/snorca-profiles.git
$ mv default default.original
$ ln -s snorca-profiles default
$ curl -sL https://files.printables.com/media/prints/c5f98471-8d3d-47dc-a8b7-6f9ebe064520/stls/13150913_dfee7dd0-71b9-453a-b7e7-c25915a564f1_ff4033ed-3427-41dd-917a-0f20156ce237/disco-ball-applique.3mf
```
## Periodic Updates
```
$ cd ~/.config/Snapmaker_Orca/user/snorca-profiles
$ git pull
```
