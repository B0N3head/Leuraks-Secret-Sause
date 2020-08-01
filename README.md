# Leurak's Malware (source code)
Found most on an old usb, got others via other means.
Please [create an issue](https://github.com/B0N3head/Leuraks-Secret-Sause/issues) if any of the samples are corrupted, protected or you think I am missing something, have fun.
Don't come here expecting to just download memz and give it to a friend this is ment for preservation and exploration, not skids.

|Name            |Full source there       |Buildable?                 |Working Win Versions |Non Win Versions |
|----------------|------------------------|---------------------------|--------------------|--------------------|
|Bonzify         | Yes | [How to build Bonzify](#files-required-to-build-bonzify) | xp, vista, win7| Not tested |
|Illuminati      | Yes | Not tested, requires OpenCV2 | Not tested | Not tested |
|MEMZ (Master)   | Yes | Not tested | Not tested | Not tested |
|REGFuck         | Yes | Easy | Not tested | Not tested |
|TrollRAT        | Yes | Not tested | Not tested | Not tested |
|VineMEMZ        | Yes | Not tested |Not tested | Not tested |
>If it does not show your windows version that does not mean that it wont work, just not tested.

## FILES REQUIRED TO BUILD BONZIFY
These files are not made by me and could be copyrighted.
Most of them are contained in BonziBuddy432.exe, which is commonly [available](https://archive.org/download/BonziBuddy432.7z/BonziBuddy432.7z) on the internet.
You will need Visual Studio 2015 with the Windows XP Support for C++ package to be able to build. (Works on xp, vista and win7)

|    Filename     |                 Usage                 |   CRC32    | Source |
| --------------- | ------------------------------------- | ---------- | ------ |
| **Bonzi.acs**   | MS Agent character file of Bonzi      | `021C47FF` | BonziBUDDY (installs to `%WINDIR%\msagent\chars`) |
| **Bonzi.ico**   | BonziBUDDY Icon                       | `AC81A034` | BonziBUDDY (extracted using a resource editor) |
| **MSAGENT.EXE** | Microsoft Agent 2.0 Installer         | `E6DB4931` | [Available Here](https://web.archive.org/web/2006id_/http://activex.microsoft.com/activex/controls/agent2/MSagent.exe), MSagent.exe is contained in BonziBuddy432 |
| **tv_enua.exe** | Bonzi's Text-To-Speech Engine         | `AF0365F7` | [Available Here](https://web.archive.org/web/2006id_/http://activex.microsoft.com/activex/controls/agent2/tv_enua.exe), Tv_enua iscontained in BonziBuddy432 |
> **Plz GitHub don't take it down it's preservation**
