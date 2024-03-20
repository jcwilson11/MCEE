# How to import and export templates
```https://www.youtube.com/watch?v=WgzzS95RwKU``` - This video shows how to import and export templates in the game. It is recorded on a mac, but the steps are the same for windows. I am not sure if this can be done on mobile. It may require additional apps, and will not be covered in this video.

Since I have already prepared the **.mctemplate file**, you should be able to import it directly into your game without having to import the individual files. 

If that does not work, **generate two unique UUIDs** (Use the following website: https://www.uuidgenerator.net/), open the **maniffest.json** file, and **replace the UUIDs with the new ones.** Then, zip the **ALL** files and **change the extension to .mctemplate.** You can then **import the .mctemplate file into your game.**

If you need to create a new .json file, open your text editor (TextEdit on Mac, Notepad on windows). Copy and paste the ffollowing template into the new file:
```
{
   "format_version" : 1,
   "header" : {
      "description" : "DESCRIPTION HERE",
      "name" : "NAME HERE",
      "uuid" : "b8cea4a2-f311-459e-a0bd-692c8602956e",
      "version" : [ 1, 0, 0 ]
   },
   "metadata" : {
      "authors" : [ "YOU DID THIS" ],
      "url" : "YOUR WEBSITE HERE"
   },
   "modules" : [
      {
         "description" : "Not Needed",
         "type" : "world_template",
         "uuid" : "23168ea1-9707-4a8c-88e5-08ae93ec083f",
         "version" : [ 1, 0, 0 ]
      }
   ]
}
```
Replace the text in caps with your own information, and take two new UUIDs and replace the ones in the file. Save the text file as maniffest.json, so it is ready to be copied into the unzipped folder. 

# Credit
-  Class Build a simple house by JWil
- Remix of Class Build Blocks of Concrete by Nathan Richards. Can be found in the Minecraft Education Edition Library.
```
