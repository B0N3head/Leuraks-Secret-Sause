# Bonzify
A trojan created for Vinesauce Joel's Windows Vista Destruction.  
**This is destructive malware, don't compile and run it if you don't know the risks!**

## About this release
The is not the original Bonzify Joel used, but rather an unfinished version of the improvements I wanted to do before 
releasing the source code.

Some parts are still rushed and badly implemented, like the timing and killing of Bonzi, the EXE finder implementation 
and a lot of dumb batch files because they made it easier to work on the other parts. Don't take this code as a "good example".

There are no plans fix or document anything, so don't submit issues (which are disabled anyway).
Just use what's there and maybe improve it for yourself. **NEVER SHARE BINARIES!**

## Videos
* **Original Bonzify used by Joel:** <https://youtu.be/9VgIOeuMj7I?t=6611>  
...including Twitch chat: <https://youtu.be/MaGPJP6Lyk0>

* **Showcase of the changes in the Source Code release:** (coming soon, which probably means never)

## Compatibility
Bonzify should launch on XP and later, but is optimized for Windows Vista.
There could be issues with more recent versions of Windows.

The DLL injection is only compatible with x86 executables, 
which means the Bonzification only works properly on 32-bit operating systems.

## Compilation Instructions
### Prerequisites
* Visual Studio 2015 (you might be able to use a newer version if you change the project settings)
* Some extra "resource" files, listed [here](Bonzify/Resources/README.md)

### Important
* Only use the Release/Win32 configuration
* Due to the shitty way the resources got implemented, always build the solution twice
* Don't accidentally run this on your production machine (which should be obvious)a