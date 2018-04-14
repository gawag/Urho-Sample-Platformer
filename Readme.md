# Urho Sample Platformer


--
14.4.2018 updated to trunk ( at this point: 218e4d7592cf8681001e795cac6672fb29fb156a ).
Fixed few things in source code, updated CMake files, CoreData, some Data files.

Visual Studio 2017 info (should work other cmake_* too):

Create solution like this

 cmake_vs2017.bat Build -DURHO3D_HOME=your_urho3d_build_directory
 
ie if you have F:/CPP/Urho3D/  (from trunk), and you created (cmake created) F:/CPP/Urho3D/Build/  dir where  lib/, include/ etc are, then use

 cmake_vs2017.bat Build -DURHO3D_HOME=F:/CPP/Urho3D/Build

Then open Build/Urho-Sample-Platformer.sln

 
-m
--

This is the first Urho3D sample project developed for the Unofficial Urho wiki: http://urho3d.wikia.com/  
The USP page there with Urho related details is at: http://urho3d.wikia.com/wiki/USP_-_Urho_Sample_Platformer  
See the wiki here https://github.com/gawag/Urho-Sample-Platformer/wiki for more game related informations.

## Build Instructions

Like Urho USP  uses CMake for building. I'm using Codeblocks on Windows but I also heard USP being build on GNU/Linux and Mac OS X.  
See http://urho3d.wikia.com/wiki/Creating_a_new_Urho3D_Project for details.

## Copyright Notes for Third-Party Assets in /Build/bin/Data/

File: Models/robot.mdl and /blends/Robot.blend (the player model)  
Based on http://www.blendswap.com/blends/view/77792 and heavily modified by gawag.  
Original licence: Creative Commons Attribution 3.0 Unported (CC BY 3.0)

File: Music/Drums of the Deep.ogg (the music in level_1, I made it ~76% faster)  
Artist: Kevin MacLeod  
Licence: Creative Commons: By Attribution 3.0  
Found at: http://incompetech.com/music/royalty-free/index.html?isrc=USUAN1400021

File: Music/Lord of the Land.ogg (the music in level_2)  
Artist: Kevin MacLeod  
Licence: Creative Commons: By Attribution 3.0  
Found at: http://incompetech.com/music/royalty-free/index.html?isrc=USUAN1400022

File: Music/271866__mrpork__era-of-space.ogg (the music in level_3)  
Artist: MrPork  
Licence: Creative Commons: 0 License  
Found at: https://www.freesound.org/people/MrPork/sounds/271866/  
Comment: Slowed down by 50% and added flanger effect.

File: Sounds/littlerobotsoundfactory__jingle-win-synth-04.ogg (the flag collect sound)  
Artist: LittleRobotSoundFactory  
Licence: Creative Commons Attribution 3.0 Unported (CC BY 3.0)  
Found at: https://www.freesound.org/people/LittleRobotSoundFactory/sounds/274183/

File: Sounds/torch.ogg (torch/fire sound)  
Artist: leosalom  
Licence: Creative Commons Attribution 3.0 Unported (CC BY 3.0)  
Found at: https://www.freesound.org/people/leosalom/sounds/234288/

Files: Sounds/step1.ogg, step2.ogg and steam.ogg are recorded by me  
Artist: gawag  
Licence: MIT or CC BY 3.0

All other files are either from Urho3D or made by me and under the general license (MIT) described in the LICENSE file.
