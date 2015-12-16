Server Data
===========

# Information:

These files contain the master mod list for any type of modpack. Feel free to add new modpacks which are not yet supported, make fixes, add mods and remove as needed.

This will change the contents of the downloads here: http://soartex.net/downloads/modpacks/

## How to add a pack


1. Get the complete mod listing

    This means all the mods in the pack, which use textures you can check this by opening the mod with wither WinRar or 7Zip or another other application. Once you can see inside the mod file, browse into the "assets/modname" directory and look to see if there is a folder called "textures" and if it has any. For the benefit of the server we'd prefer if mods which have no textures are not included on the modpack file.

2. Create the modpack file

    This file has to be named and stored in the correct folders on this repository. So for instance if your modpack is called "SoarCraft" and your pack is on the "Feed The Beast Launcher" you would name your file "FTB-SoarCraft.txt", then you put this file in the corresponding directory in the repository. So for this pack it is "1.6.x" so you would put the file in this location "modpacks/providers/1.6.x/ftb".

    Now it comes to adding the mods to the file, you need to add each mod to the text file using strict naming guide lines found here (coming soon), the naming is key as if your naming a mod in-correct our server script won't add the mod as the name would be wrong of the folder on our repositories. 

    So for an example "BuildCraft" would be called "Buildcraft" or "CompactSolars" would be called "Compact_Solars" as these are the naming styles we are using on the Soartex repositories. Once you have added all the mods you need to ensure you leave an "return" (empty line) at the bottom of the file as this is used on the server to start the next build. Without this white-line your pack could miss a few mods being added to the download.
    
3. Submit a pull request

    Once you have created your file, then all you have to do is submit a pull-request to here and a member of staff will check the file out on a development server before merging to check for bugs or mistakes made on the file. Once the testing is completed your modpack will be added the repository! Mopacks added here won't always make it to the site as a download from there, but can be packages and have hidden links. Please take a quick look at the notes to find more information about the downloads system.

### Note:

Not all packs added on here will be automatically added to the website this can be due to various reasons. Sometimes packs will be added as a "hidden" download and you need to request to have a link for the download. But if you would like your pack added to the site as a download, or if you have a question regarding hidden downloads please contact us by:
- Posting an issue on this repo.
- Using our contact form https://soartex.net/contact/
- Emailing us at support@soartex.net



