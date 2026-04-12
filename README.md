# Atheros  

## Version 1

<p align="center">
<img src="https://user-images.githubusercontent.com/29189359/173229414-33e5bf10-d047-43c5-afa6-99d2b681f0b5.png" width="360">
<img src="https://user-images.githubusercontent.com/29189359/173229700-826c8d8a-9f00-4e71-9963-e3f7c064e9a3.png" width="360">
</p>

## Version 2

<p align="center">
<img src="/etc/new-preview-dark.png" width="360">
<img src="/etc/new-preview-light.png" width="360">
</p>

<p align=center> Foobar Simple Compact ColumnUI Theme </p>

This is just a self-homemade Foobar2000 Theme.
V1.1 and onward uses Built-in ColumnUI Playlist View.
~~ Compatible with v2 32-Bit.~~ 
Only compatible with Version 2.x 64-Bit.

## Prerequisite

### Foobar2000 Version Requirement

Foobar2000 Version 2.25 Stable or Latest 64-Bit is Required

### Foobar Component  


- [Columns UI >= (1.6.0)](https://github.com/reupen/columns_ui "foo_ui_columns")
- [~~Spider Monkey Panel >= (1.3.0)(TheQwertiest)~~](https://github.com/TheQwertiest/foo_spider_monkey_panel "foo_spider_monkey_panel") `Unmaintained`
  - [Spider Monkey Panel (marc2k3)](https://github.com/marc2k3/spider-monkey-panel-x64)
- [~~Library Tree (Wil-B)~~](https://github.com/Wil-B/Library-Tree) `Unmaintained`
    - [Library Tree (Regorxxxx)](https://github.com/regorxxx/Library-Tree-SMP)
- [(Optional) Album List Panel](https://github.com/reupen/album_list_panel "foo_uie_albumlist") `use Library Tree for Album / Directory listing, otherwise use this component.`

- [Waveform Minibar Mod](https://wiki.hydrogenaud.io/index.php?title=Foobar2000:Components/Waveform_Minibar_(mod)_(foo_wave_minibar_mod) "foo_wave_minibar_mod")


## Installation  

- Extract ``release.7z`` and copy ``Atheros`` folder inside ``\foobar2000\themes``.
- Install Required Component from [Prerequisite](https://github.com/koushiroue/atheros#prerequisite) or Drag all files from ``components`` folder into foobar component preferences setting.
- Restart, Choose Column UI and enable theming.  
- Install `.zip` Script by using Spider Monkey Package Manager (TBA)
  - Right Click into Blank Spider Monkey Panel and select Configure Panel or;
    <img src="../main/etc/script.png" width="480">
  - Preferences > Layout > Spider Monkey Panel > Configure Panel  
    <img src="../main/etc/SMP.png" width="480">  
  - Select Package > Package Manager > Import > Select `.zip` script.
    <img src="../main/etc/SMP-packman.png" width="320">
- Import Columns UI configuration on ``preferences > Columns UI > Main`` and choose the ``.fcl`` file.  

## Troubleshooting

- Portable version of Foobar2000 is recommended.
- May not work well on HiDPI Display scale 125% and 150%, may require changing hidpi setting on foobar executable properties.  
![alt text](../main/etc/hidpi.png "Foobar.exe Properties > Compatibility > Change HiDPI Settings")  

*note : The skin might not fit in 150% display scale for 1080p resolution or lower.*  

- Alternatively you can refer the "minimum" window size here  
![alt text](../main/etc/window.png "Preference > Display > Main Window (UI Hacks)")

*warning : changing the maximum window too low will crash the Spider monkey JS Panel.*

## Changelog

- Atheros `v1.2`
  - Columns UI `v1.?.?`
  - Album List Panel `v1.0.0`
  - Spider Monkey Panel `v.1.6.?`

- Atheros `v 1.1`
  - Columns UI `v 1.7.0`  
  - Spider Monkey Panel `v 1.6.1`  

- Atheros `v 1.0`  
  - Columns UI `v 1.6.0`
  - Spider Monkey Panel `v 1.3.1`
