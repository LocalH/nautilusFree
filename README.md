This is the .NET library that Nautilus / Magma / cPlayer and all my tools rely on to decrypt Harmonix MOGG audio files as well as YARG .yargsong audio files.

No support is provided along with it but some people have asked to see the code, so here it is.

Enjoy

Nemo

December 13, 2025

LocalH addendum: I've added preliminary v17 support to this DLL without breaking v11-v16 decryption. Release builds of Nautilus work with this version of the DLL, but they will still send v17 through themethod3 path. But, it *should* work. I have issues trying to build Nautilus (probably just VS shenanigans, I think related to BASS) so I can't really update Nautilus to pass v17 through the DLL as well.