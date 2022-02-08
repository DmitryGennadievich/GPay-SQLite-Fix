# GPay-SQLite-Fix #
A magisk module to allow Google Pay to work on rooted phones

A simple Magisk module to provide the GPay (Google Pay) SQL Fix featuring the original work of BostonDan as described here:

https://forum.xda-developers.com/apps/magisk/magisk-google-pay-gms-17-1-22-pie-t3929950

in a simple format and using service.d to run the SQLite script and set database permissions

Please see my original post about the module below (or via clicking XDA icon if viewing this via Fox MM) 
for requirements, pre-installation checks and troubleshooting steps BEFORE you install this module, 
some of these steps may (probably wont) work if done out of order!

https://forum.xda-developers.com/t/working-magisk-with-google-pay-as-of-gms-17-1-22-on-pie.3929950/page-9#post-79643248

Especially of note, the module requires a working SQLite3 binary, and one is provided by me for exactly that purpose
on my repo here:

https://github.com/stylemessiah/SQLite3UniversalBinaries

### The GPay (Google Pay) SQL Fix features the work of: ###

- **BostonDan** (original method)
- **braveheartleo** - for the chattr suggestion (removed in later versions)
- **Didgeridoohan** - for the working method to hide Google Play Services via magiskhide in a script
                      loop & again during switch to MMM-EXT module format
- **Zackptg5** - for the MMM-EXT module format and help switching to it
- **Skittles9823** - for help during switch to MMM-EXT module format
- **jcmm11** - for help during switch to MMM-EXT module format
- **osm0sis** - for help with adding magiskhide or zygisk denylist detection


**Please note:** the included LICENSE **only** covers the module components provided by the excellent work of Zack5tpg's 
Magisk Module Extended, which is available for here for module creators

https://github.com/Zackptg5/MMT-Extended/


All other work is credited above and **no one may fork or re-present this module as their own for the purposes of trying to 
monetize this module or its content without all parties permission. The module comes specifically without an overall license 
for this intent.**



### Project Stats ###

New Alt-Repo Stats:

![GitHub release (latest by date)](https://img.shields.io/github/v/release/stylemessiah/GPay-SQLite-Fix?label=Release&style=plastic)
![GitHub Release Date](https://img.shields.io/github/release-date/stylemessiah/GPay-SQLite-Fix?label=Release%20Date&style=plastic)
![GitHub Releases](https://img.shields.io/github/downloads/stylemessiah/GPay-SQLite-Fix/latest/total?label=Downloads%20%28Latest%20Release%29&style=plastic)
![GitHub All Releases](https://img.shields.io/github/downloads/stylemessiah/GPay-SQLite-Fix/total?label=Total%20Downloads%20%28All%20Releases%29&style=plastic)

Original Repo Stats (before repo was erased recently):

GitHub All Releases: 35k
