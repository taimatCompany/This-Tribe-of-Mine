Localizations are not added to the mod
And here we reached the true plague of Storyteller. After all the hard work you've done, all texts you've edited, you pack your mod, launch the game and see how perfectly it works, You push it to Workshop, and after a while, reading comments, you begin to realize that something's off. The players don't see your texts...

I do understand your emotions. I've spent quite some time bashing my head against the wall about this one, and I've thought I'll have to use a separate mod for localizations like it's mostly being done. However, at the very last moment I've stumbled upon a well-hidden piece of advice (unfortunately, I forgot who made a discovery - if it's you, drop a comment, I'll credit you!).

In order to make it work, you'll have to use something I call a localization donor (or a donor mod). Here's what you need to do:
Create a new mod. You won't use it for anything but for being a localization donor, so don't change anything there.
Go to this mod's "Localizations" folder.
Remove every file with ".lang" extension.
Go to your actual mod's "Localizations" folder.
Copy every .lang file that ends with "_%modID%" and paste it to your donor's "Localizations" folder.
Remove your mod's ID and "_" character from these files' titles. So, for example, "ancient_3dde5318ba8641bfbdf863fb23f31480.lang" turns into ""ancient.lang".
Pack your donor mod.
Three "localizations" archives of your donor mod residing in "Mods" folder are the ones you're gonna push into Workshop instead of your actual mod's archives.
Why does it work like that? I don't know and I don't wanna now. All I care about is that this is the only known way to make it work without asking your subscribers to use additional localization mods on top of your actual mod.
Complicated? Indeed; but if you read further, I might be able to help you to make it a bit easier.

Create a folder to which you will put your archives to be sent to Steam Workshop (will be further referred to as "pre-Workshop folder").
Pack your mod via Storyteller.
From mods folder, copy all your mod's archives except for "common" and "localizations" to pre-Workshop folder.
Add your customized scripts into "common" archive, as seen in "Making your own mod: execution, p.1" section, subsection #1: "Find the action of scavenging a heap".
Copy the archives that underwent re-packing from unpacker/out into pre-Workshop folder.
Also copy common.dat_items.dat and common.str archives of your mod from Mods folder and into pre-Workshop folder.
Create localization archives via donor, as explained in "Localizations: problems and workarounds Edit" section, subsection "Localizations are not added to the mod".
Put localization archives created via donor into pre-Workshop folder.
Remove all prefixes from your mod's files. So, for example, "8d3ef3d9599a4935b737a59d813aa553_common.dat" should turn into "common.dat".