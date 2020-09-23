# Label Reference

### 1.	Download and Install Python

##### Download Python 3.8.5

[python-3.8.5.exe](https://www.python.org/ftp/python/3.8.5/python-3.8.5.exe)


##### Install Python (Windows)

Double click python-3.8.5.exe

Check "Add Python 3.8 to PATH"



### 2.	Install Labelme

1. Open CMD command prompt

2. Run 

   ```
   pip install labelme
   ```
   



### 3.	Download images

1. Download sftp https://www.netsarang.com/en/free-for-home-school/
2. Open sftp -> File -> New
   1. Host: forjlive.com
   2. Port Number:28386
   3. check User authentication agent
   4. User Name: imgprocess
   5. Password: "Ask me for that"
3. Download Folder "Images_your name" to your local drive

### 4.	Pre-process images

1. Make sure you finished downloading all picture to your local drive

2. There should be 5-6 images for one event, pick the one have most clearly plate.

3. Rename the image as their PLATE Number.

4. Create a new folder called "DATA" , and put renamed image inside of it.

5. If you found mutiple vehicle plates in one image. Don't pick it. If all 6 images for this event have mutiple vehicle plates, delete all 6 imgs for this event.

### 5.	Start Labelme

  1. Make sure you get all images for labeling
  2. Create a folder called "JSON"
  3. Open a CMD Window
  4. Type "labelme" and press ENTER (should open lableme)
  5. Click button "Open Dir"
  6. Select your image source folder 
  7. Click button "File"->"Save Automatically"
  8. Click button "File"->"Change Output Dir"
  9. Start label; Click button "Create Polygons"
  10. Draw a 4 point Polygons for license plate you get  (Use "ctrl + mouse wheel up" to  make pic lager then make sure the Polygon perfectly fit the license plate )
  11. Click "Edit Polygons " to adjust the polygon (make sure it's perfectly fit!)
  12. Enter Object name exact same as "licenseplate"
  13. Click button "Next Image" 
 14. Loop through 9-13



### 6.	Upload Img

Upload folder JSON_yourname and DATA_yourname and to server at step 3



