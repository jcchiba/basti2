## basti2

Test Project to learn how to produce fonts using current ai tools and resources.
This is a mix of pix2pix and reinforced learning.

## Current Instructions

1. Install python requirements (python3):

$ sudo pip3 install -r requirements.txt

2. Select a main font for training  and rename it as 1.ttf

3. Put the rest of the fonts in the fonts folder (ttf files)

4. Run font2img.py

$ python3 font2img.py

5. Copy the generated images from the data folder and divide them into 3 folders (50% to train and 25% to the rest of the folders):

+ train
+ test
+ val

6. Use renamer.py to rename files by modifying the path location

7. Once files are renamed copy train test and val folders to the images font folder (replace if needed)  

8. Run basti.py for training

$ python3 basti.py

9. Save or move the generated model h5 and json files to a safe location for further use later


## Good Luck
