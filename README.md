## Mizuki's personal bucket
## Apps included:
- [lolcrab](https://github.com/mazznoer/lolcrab): Like lolcat but with noise and more colorful.
  - `lolcrab`
- [Sizer](https://web.archive.org/web/20231214142633/https://www.brianapps.net/sizer4/) ([Legacy version](https://web.archive.org/web/20231213123421/https://www.brianapps.net/sizer/)): Freeware utility that allows you to resize any window to an exact, predefined size.
  - `sizer4_archived` and `sizer3_archived`
- [oggdec](https://www.rarewares.org/ogg-oggdec.php): RareWare's Ogg Vorbis decoder created by John33. Shim is renamed to oggdec2 to prevent conflict with `vorbis-tools`.
  - `oggdec2`
- [vorbis-tools](https://gitlab.xiph.org/xiph/vorbis-tools): Command-line tools for creating and playing Ogg Vorbis files. Build by [Chocobo1](https://github.com/Chocobo1/vorbis-tools_win32-build).
  - `vorbis-tools-chocobo1`
- [opus-tools](https://gitlab.xiph.org/xiph/opus-tools): Command-line tools for creating and playing Opus files. Build by [Chocobo1](https://github.com/Chocobo1/opus-tools_win32-build).
  - `opus-tools-chocobo1`
- [ldd-win](https://github.com/Ex-Origin/ldd-win): A similar Linux ldd command for EXE files.
  - `ldd-win`
- [pdu](https://github.com/KSXGitHub/parallel-disk-usage): Highly parallelized, blazing fast directory tree analyzer.
  - `pdu`
- [AntiDupl.NET](https://ermig1979.github.io/AntiDupl/english/): A program to search similar and defect pictures on the disk.
  - `antidupl.net-portable`
- [yt-dlg](https://github.com/oleksis/youtube-dl-gui): A cross platform front-end GUI of the popular youtube-dl written in wxPython.
  - `yt-dlg`
- [gImageReader](https://github.com/manisandro/gImageReader): A Gtk/Qt front-end to tesseract-ocr.
  - `gimagereader`
- [Touhou Toolkit](https://github.com/thpatch/thtk): Command-line toolkit for extracting, modifying, and repacking the data of the Team Shanghai Alice games.
  - `thtk-nightly`
- [Don't Sleep](https://www.softwareok.com/?seite=Microsoft/DontSleep): A small program to prevent system Shutdown, Stand By, Turn Off , Restart, Hibernate.
  - `dontsleep`
- [Large Text File Viewer](https://web.archive.org/web/20141121061431/http://www.swiftgear.com/ltfviewer/features.html): Read-only text viewer optimized for very large text files. Support regex-based searching.
  - `ltfviewer`
- [OpenTTD-jgrpp](https://github.com/JGRennison/OpenTTD-patches): JGR's Patchpack applied to OpenTTD.
  - `openttd-jgrpp`
- [ZaDark](https://zadark.com): Open-source dark mode for Zalo.
  - `zadark`
- [7-Benchmark](https://www.7-cpu.com/utils.html): LZMA 7-Zip Benchmark suite.
  - `7-benchmark`
- [dependency_runner](https://github.com/marcoesposito1988/dependency_runner): ldd for Windows - and more!
  - `dependency-runner`
- [pixiv-viewer](https://github.com/asadahimeka/pixiv-viewer): Yet Another Pixiv Illust&Novel Viewer.
  - `pixiv-viewer`
- [pixiv-viewer-electron](https://github.com/asadahimeka/pixiv-viewer): Yet Another Pixiv Illust&Novel Viewer. (Deprecated Electron version)
  - `pixiv-viewer-electron`
- [binocle](https://github.com/sharkdp/binocle): a graphical tool to visualize binary data.
  - `binocle`
- [diskus](https://github.com/sharkdp/diskus): A minimal, fast alternative to 'du -sh'.
  - `diskus`
- [CrystalDiskInfo Aoi Edition](https://crystalmark.info/en/software/crystaldiskinfo/): A HDD/SSD utility software which supports a part of USB, Intel RAID and NVMe.
  - `crystaldiskinfo-aoi`
- [CrystalDiskMark Aoi Edition](https://crystalmark.info/en/software/crystaldiskmark/): A simple disk benchmark software.
  - `crystaldiskmark-aoi`
- [Notepad4](https://github.com/zufuliu/notepad4): Fork of Notepad2, a light-weight Scintilla-based text editor. Featuring syntax highlighting, code folding, auto-completion and API list for about 80 programming languages/documents.
  - `notepad4`
- [Re-version](https://web.archive.org/web/20230609000845/http://lunarcast.net/revers.php): Allows modification of the PE Optional Image Header which contains the Operating System Major & Minor version and the SubSystem Major & Minor version.
  - `reversion`
```
Usage: Revers32/64.exe <InputFile> <OSMajor> <OSMinor> <SubsysMajor> <SubsysMinor>
Despite the name, the OS fields doesn't seem to be regarded by the OS, but rather the Subsys ones.
Setting the OS fields to 10 0 (Win10) and Subsys fields to 5 1 (WinXP) will allow the binary to run on XP.
Conversely, OS 5 1 (WinXP) and Subsys 10 0 (Win10) will not.
Lunarcast recommends setting OSMajor and OSMinor to 1 and 0 respectively and more or less ignore them.
Documentation: https://learn.microsoft.com/en-us/windows/win32/api/winnt/ns-winnt-image_optional_header32
```
