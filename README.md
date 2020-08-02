# Leurak's Malware (source code)
Found most on an old usb, got others via other means.

Please [create an issue](https://github.com/B0N3head/Leuraks-Secret-Sause/issues) if any of the samples are corrupted, protected or you think I am missing something, have fun.

`Don't come here expecting to just download memz and mess with someone, this is ment for preservation and exploration, not skids.`

|Name            |Full source  |Buildable                 |Working Win Versions |Not Working Win Versions |
|----------------|-------------|---------------------------|---------------------|-------------------------|
|Bonzify         | Yes | [How to build Bonzify](#files-required-to-build-bonzify) | xp, vista, win7| Not tested |
|Illuminati      | Yes | Not tested, requires OpenCV2      | Not tested          | Not tested |
|MEMZ (Master)   | Yes | Not tested                        | Not tested          | Not tested |
|REGFuck         | Yes | Yes                               | Not tested          | Not tested |
|TrollRAT        | Yes | Not tested                        | Not tested          | Not tested |
|VineMEMZ        | Yes | Not tested                        | Not tested          | Not tested |
> If your desired windows version is not labled that does not mean that it wont work, just not tested.

## Readme Files
- [Bonzify](https://github.com/B0N3head/Leuraks-Secret-Sause/blob/master/ReadmeFiles/README-Bonzify.md) 
- [Illuminati](https://github.com/B0N3head/Leuraks-Secret-Sause/blob/master/ReadmeFiles/README-Illuminati.md)
- [MEMZ](https://github.com/B0N3head/Leuraks-Secret-Sause/blob/master/ReadmeFiles/README-MEMZ.md)
- [REGFuck](https://github.com/B0N3head/Leuraks-Secret-Sause/blob/master/ReadmeFiles/README-RegFuck.md)
- [TrollRAT](https://github.com/B0N3head/Leuraks-Secret-Sause/blob/master/ReadmeFiles/README-TrollRAT.md)
- [TrollRAT Roadmap](https://github.com/B0N3head/Leuraks-Secret-Sause/blob/master/ReadmeFiles/Roadmap-TrollRAT.md)
- [VineMEMZ](https://github.com/B0N3head/Leuraks-Secret-Sause/blob/master/ReadmeFiles/README-VineMEMZ.md)

## FILES REQUIRED TO BUILD BONZIFY
These files are not made by me and could be copyrighted.
Most of them are contained in BonziBuddy432.exe, which is commonly [available](https://archive.org/download/BonziBuddy432.7z/BonziBuddy432.7z) on the internet.
You will need Visual Studio 2015 with the Windows XP Support for C++ package to be able to build.

|    Filename     |                 Usage                 |   CRC32    | Source |
| --------------- | ------------------------------------- | ---------- | ------ |
| **Bonzi.acs**   | MS Agent character file of Bonzi      | `021C47FF` | BonziBUDDY (installs to `%WINDIR%\msagent\chars`) |
| **Bonzi.ico**   | BonziBUDDY Icon                       | `AC81A034` | BonziBUDDY (extracted using a resource editor) |
| **MSAGENT.EXE** | Microsoft Agent 2.0 Installer         | `E6DB4931` | [Available Here](https://web.archive.org/web/2006id_/http://activex.microsoft.com/activex/controls/agent2/MSagent.exe), MSagent.exe is contained in BonziBuddy432 |
| **tv_enua.exe** | Bonzi's Text-To-Speech Engine         | `AF0365F7` | [Available Here](https://web.archive.org/web/2006id_/http://activex.microsoft.com/activex/controls/agent2/tv_enua.exe), Tv_enua iscontained in BonziBuddy432 |
> **Plz GitHub don't take it down it's preservation**
