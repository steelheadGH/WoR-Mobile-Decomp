# What is this?
This is a full decompilation of the game Guitar Hero Warriors of Rock Mobile. It includes the source code, images, sound effects and midis, etc. 

# How did you make this?
To decompile the source code, I used Apktool to extrat the game's classes.dex file, giving me the smali source code which I converted to java code using smali2java (this conversion prob has a bunch of bugs and issues, and I don't care enough to fix them). To extract the MIDIs and MP3s, I renamed the apk file to zip, extracted it and took all the mp3s and midis out of the assets folder. For the PNGS, i renamed the apk again, this time to jar, and used j2me-asset-hunter to extract all of the assets from it.

# Tools used:
Apktool: https://github.com/iBotPeaches/Apktool
smali2java: https://github.com/AlexeySoshin/smali2java
j2me-asset-hunter: https://github.com/zzxzzk115/j2me-asset-hunter

# Notes
1. The .java source code provided here is not perfect. It was converted from the .smali files and probably has several issues. What you can do is use the .java files to learn about the smali programming language the game uses in an easier way.

2. I don't know what MobirooLibraries is, if somebody knows what it is, please tell me.

3. If some of the images seem random and unrelated to the game, that's because GLU Mobile left in a tutorial on how to use OpenFeint (the game's online leaderboards service) in the game's files.

4. The decomp is in a zip file on releases because I had trouble adding the files to the GitHub repository.

# Copyright notice
I DO NOT own any code, assets, audio, and more in this project. This project is only a reverse engineering of Guitar Hero Warriors of Rock Mobile, which was made by GLU Mobile. If GLU Mobile wants to take this project down, I will do so.

# Contact info
If you have something you need to tell me, like a bug report, or something else, please let me know on my Discord DMs: @enter_gh
