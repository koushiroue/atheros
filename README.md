# Atheros  
<p align="center">
<img src="https://user-images.githubusercontent.com/29189359/173229414-33e5bf10-d047-43c5-afa6-99d2b681f0b5.png" width="480">
<img src="https://user-images.githubusercontent.com/29189359/173229700-826c8d8a-9f00-4e71-9963-e3f7c064e9a3.png" width="480">
</p>

<p align=center> Foobar Compact ColumnUI Theme </p>

## Prerequisite

### Foobar Component  

- [Columns UI >= (1.6.0)](https://github.com/reupen/columns_ui "foo_ui_columns")
- [Spider Monkey Panel >= (1.3.0)](https://github.com/TheQwertiest/foo_spider_monkey_panel "foo_spider_monkey_panel")
  - [Library Tree](https://github.com/Wil-B/Library-Tree)
- [Waveform Minibar](https://wiki.hydrogenaud.io/index.php?title=Foobar2000:Components/Waveform_Minibar_(mod)_(foo_wave_minibar_mod) "foo_wave_minibar_mod")
- [OpenLyrics](https://github.com/jacquesh/foo_openlyrics)
- [Musical Spectrum](https://wiki.hydrogenaud.io/index.php?title=Foobar2000:Components/Musical_Spectrum_(foo_musical_spectrum))
- UI Hacks
- ~~[EsPlaylist (v0.1.3.9(2011/05/28))](http://foo2k.chottu.net/ "outdated")~~
- ~~Panel Stack Splitter~~

## Installation  

- Extract ``release.7z`` and copy ``Atheros`` folder inside ``\foobar2000\themes``.
- Install Required Component from Prerequisite or Drag all files from ``components`` folder into foobar component preferences setting.
- Restart, Choose Column UI and enable theming.  
- Install `.zip` Script by using Spider Monkey Package Manager (TBA)
  - Right Click into Blank Spider Monkey Panel and select Configure Panel or;
    <img src="../main/etc/script.png">
  - Preferences > Layout > Spider Monkey Panel > Configure Panel  

    <img src="../main/etc/SMP.png" width="320">  
  - Select Package > Package Manager > Import > Select `.zip` script.
    <img src="../main/etc/SMP-packman.png" width="240">
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

- Atheros `v 1.1`
  - Columns UI `v 1.7.0`  
  - Spider Monkey Panel `v 1.6.1`  

- Atheros `v 1.0`  
  - Columns UI `v 1.6.0`
  - Spider Monkey Panel `v 1.3.1`
