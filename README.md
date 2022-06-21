# CentiCodes Ultimate NCS Collection Level Files
These are the unencrypted level files for CUNC levels.

To play these levels, I recommend using Rolling Sky Unlocked:
https://drive.google.com/drive/folders/1TOVFp5pwICQG5swru3-kKigRyowmn5fq
- Put each file to the corresponding folder.
  - Level and End files go to Levels
  - Theme files go to Themes
  - geoBuffer files go to GeoBuffers

- "Android, PC" means you can play the level in Rolling Sky Android and Rolling Sky PC.
- "PC" means you can only play the level in Rolling Sky PC.
    - In order to play PC-Exclusive levels, first you have to download dnSpy.
    - dnSpy: https://github.com/dnSpy/dnSpy
  - Go to Rolling Sky_data/Managed and use dnSpy to open Assembly-CSharp.dll.
    - Search for "leveldesigner". On the search results, go to WorldThemes and scroll up until you see these lines.
      ![image](https://user-images.githubusercontent.com/105146816/174720716-a92f270e-fbcb-434b-86b7-3dbe59aa7892.png)
    - Right Click and select "Edit Class".
    - Highlight line 651-703.
      ![image](https://user-images.githubusercontent.com/105146816/174720888-5fdd4ff7-aa63-4247-b6cc-fd75f621b504.png)
    - Copy everything on "Level Attributes.txt" and replace those lines by pasting everything from the .txt.
    - Select Compile.
    - Go to File and choose Save All or Save Module.
  - Open Rolling Sky. If you do everything correctly, you can play the levels.
