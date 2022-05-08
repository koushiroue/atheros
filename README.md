# Atheros  

<p align="center">
<img src="https://user-images.githubusercontent.com/29189359/165435326-c5e0e74a-44c3-48e4-8cd0-73a0dfd7fc01.png" width="480">

<img src="https://user-images.githubusercontent.com/29189359/165435377-28df718a-4731-4cde-81e6-4a9bbb8b4f7b.png" width="480">
</p>

Homemade Foobar Skin  

## Prerequisite

### Foobar Component  

- [Columns UI >= (1.6.0)](https://github.com/reupen/columns_ui "foo_ui_columns")
- [Spider Monkey Panel >= (1.3.0)](https://github.com/TheQwertiest/foo_spider_monkey_panel "foo_spider_monkey_panel")
- [Waveform Minibar](https://wiki.hydrogenaud.io/index.php?title=Foobar2000:Components/Waveform_Minibar_(mod)_(foo_wave_minibar_mod) "foo_wave_minibar_mod")
- ~~[EsPlaylist (v0.1.3.9(2011/05/28))](http://foo2k.chottu.net/ "outdated")~~
- [OpenLyrics](https://github.com/jacquesh/foo_openlyrics)
- [Musical Spectrum](https://wiki.hydrogenaud.io/index.php?title=Foobar2000:Components/Musical_Spectrum_(foo_musical_spectrum))
- UI Hacks
- ~~Panel Stack Splitter~~
- Youtube Component (Optional) - [Website](http://fy.3dyd.com/ "Proprietary")

### Library Component  

- `ffmpeg`  
- `youtube-dl`  
- `madvr` Can installed by `scoop install madvr`  

## Scripts

List of Included Spider Monkey Panel Scripts :

- [JS Smooth Playlist Manager](https://www.deviantart.com/br3tt/art/JS-Smooth-Playlist-Manager-571376332)
- [Library Tree](https://hydrogenaud.io/index.php?topic=110938.100000)

## Installation  

- Extract ``release.7z`` and copy ``Atheros`` folder inside ``\foobar2000\themes``.
- Install Required Component from Prerequisite or Drag all files from ``components`` folder into foobar component preferences setting.
- Restart, Choose Column UI and enable theming.  
- Install `.zip` Script by using Spider Monkey Package Manager (TBA)
- Import Columns UI configuration on ``preferences > Columns UI > Main`` and choose the ``.fcl`` file.  

## Troubleshooting  

- Prefer Portable version of Foobar2000
- Does not works  well on HiDPI Display scale 125% and 150%, may require changing hidpi setting on foobar executable properties.  
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
