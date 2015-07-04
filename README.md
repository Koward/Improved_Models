# The Improved Models Patch

![Logo](http://b.thumbs.redditmedia.com/aetMRPVEDnE3u3qmEA3_n1pp9RsZJ84-u_C9uWBaW6E.png)
Hi !

I had a while ago the idea of porting some Cataclysm m2s in WoW Classic. I first converted the models with tools found on Modcraft and fixed little things like textures to fit the 1.12 lighting system. 
Then I started my own tool, a[LKBC Converter](http://github.com/Koward/LKBC_Converter) in C, allowing me to go further in the process.
Now the models come from all extensions, from Burning Crusade to Warlords of Draenor.
I hope you'll enjoy it ;)

**WARNING : THIS MOD IS ONLY COMPATIBLE WITH WORLD OF WARCRAFT 1.12.1. ANY ATTEMPT TO USE IT ON AN OTHER VERSION WILL RESULT IN CRASHES AND IS A BLATANT PROOF OF YOUR STUPIDITY**

## CHANGES :
* Elwynn trees (4.0)
* Teldrassil, Ashenvale & Winterspring trees (4.0)
* Stormwind Cathedral Square ground textures (4.0)
* New Carrion bird model (3.0)
* New texture for the Night elf cat form (3.1)
* Molten giants (4.0)
* Various Stormwind City textures (4.0)
* Improved Night elf character screen
* Stranglethorn trees (4.0)
* Stormwind fountains (4.0)
* Improved waterfalls everywhere (3.0)
* Stormwind Signs (4.0)
* Human crates, barrels and postboxes (6.0)

## POSSIBLES BUGS (Please, report them):
* Scale issue : a model is bigger or smaller than it should (I think I fixed them all but you can never be sure)
* Really bright texture : this happens when a _s is not transparent enough to fit the classic lighting system.
* Funky moving model : a bug with my creature converter, resulting in parts of the body moving randomly.
* Various crashs

## TO DO :
* Stormwind Streetlamps (I've some problems with this one.. strange bugs..)
* Westfall, Duskwood and Redridge Mountains trees (based on the Elwynn model)
* Find the Stormwind crate model (Not StormwindCrate01.m2, I already replaced that one)
* Update mobs : Crab/DeepSeaCrab, Crocodile/CataclysmCrocodile, Tiger/PandarenTiger, Wendigo/Wendigo2, Frog/Toad, Owl/Edited Kaliri?, Shark/ToothedShark and all demons updated with 6.2
* Create new tree models to replace old ones
Tools used :
* CataToLK by Mjollna (CT=>LK)
* Previously LK2BC by Stan84 and now my own LKBC converter (LK=>BC)
* M2TBC posted by Soluhe (BC=>Classic)
* Previously Glitchy's Model Editing Suite
* Previously Vim xxd and now also 010 Editor with M2&Skin templates
* Ladik's MPQ Editor
* GIMP&Blender

## Installation :
### Standard 1.12.1 server
1. Download the Standard version
2. Rename in patch-X.MPQ (X have to be a number)
3. Place it in your Data folder

### Nostalrius 1.12.1 server
1. **BACKUP YOUR PATCH-2.MPQ FILE OF YOUR WOW INSTALLATION**
2. **BACKUP YOUR PATCH-2.MPQ FILE OF YOUR WOW INSTALLATION**
3. Download the Nostalrius version
4. Make sure the file is named patch-2.MPQ.
5. Place it in your Data folder. Override the existing patch-2.MPQ

##Download :
https://github.com/Koward/Improved_Models/releases
