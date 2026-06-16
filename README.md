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
$ script/report-as-printables-download
$ mv default default.original
$ ln -s snorca-profiles default
```
## Periodic Updates
```
$ cd ~/.config/Snapmaker_Orca/user/snorca-profiles
$ git pull
```
