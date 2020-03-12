# Labeling tutorial.

You have the opportunity to be a teacher for our artificial intelligence, that tries to approximate roof contours.

### Requirements 

 1. Adobe Photoshop
 2. Adobe Illustrator (Optional)

### Tutorial
 1. Find the location of tiles obtained from Google maps to label on Machine Learning workstation.
    Folder: **"D:\Machine Learning\projects\Dmitrii\roofs_segmentation\data\datasets\tiles\Google\tolabel"**
 2. Select any you want to label.
 3. Be sure that imagery is not yet labeled in:
    Folder: **"D:\Machine Learning\projects\Dmitrii\roofs_segmentation\data\datasets\tiles\Google\psd"**
 4. Open the imagery in any application either Photoshop or Illustrator.
 #### Photoshop guide:
  1. Create separate transparent layer using combination Ctrl + Shift + N, that layer should be active all the time you fill contours with a mask:</br>
    <img src="https://raw.githubusercontent.com/dmitriidatsenko/labeling_tutorial/master/src/transparent_layer.PNG" width="300"/>

  2. Choose **pen** tool:
  <img src="https://raw.githubusercontent.com/dmitriidatsenko/labeling_tutorial/master/src/pen_icon.PNG"/></br>
  3. Start with one of the existing roof on the imagery: </br>
    <img src="https://raw.githubusercontent.com/dmitriidatsenko/labeling_tutorial/master/src/contour.PNG" width="200"/></br>
     **hints:** </br>
     you can zoom in and out with the left Alt key pressed and mouse scroll;</br>
     to change the position of a point on a figure press left Ctrl.
 
  4. Fulfill a figure (roof contour) with white color:</br>
     Right click on the image > select Fill Path > select Contents: White.</br>
     <img src="https://raw.githubusercontent.com/dmitriidatsenko/labeling_tutorial/master/src/filled_contour.PNG" width="200"/>

     Right click on the image > Delete Path.</br>
     <img src="https://raw.githubusercontent.com/dmitriidatsenko/labeling_tutorial/master/src/ready_mask.PNG" width="200"/>

  5. Repeat for any existing roof on the imagery, please label carefully, more accurate data means more accurate segmentation in the future, and please do not skip any roof, even on the edge of the screen.
  6. Save labelled file as .psd format with the same name as input file to 
      Folder: **"D:\Machine Learning\projects\Dmitrii\roofs_segmentation\data\datasets\tiles\Google\psd"**
 
  
 #### Illustrator guide:
  TODO
  
  
Feel free to contact me if you have any questions:
 1. Email: **dmitriidatsenko@gmail.com**
 2. Skype: **winddim**
 
  
  
  
 
 

