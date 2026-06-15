# snorca-profiles
This repo consists of custom-tuned machine, filament, and process profiles for Snapmaker Orca. Its purposes are as follows:
- To improve print quality compared to factory-provided profiles.
- To increase print efficiency in terms of time, material usage, and success-to-failure ratio.
- To optimize temperature settings for a variety of good filament materials.
- To provide a set of easily navigated process profiles, each consisting of my best known default print settings for a particular purpose.

## Installation (for Linux AppImage version of Snapmaker Orca)
```
$ cd ~/.config/Snapmaker_Orca/user
$ git clone https://github.com/jeremyreeder/snorca-profiles.git
$ mv default default.original
$ ln -s snorca-profiles default
```
## Periodic Updates
```
$ cd ~/.config/Snapmaker_Orca/user/snorca-profiles
$ git pull
```
