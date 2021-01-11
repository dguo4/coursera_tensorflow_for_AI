This folder contains all material for week 2 for Convolutional Neural Networks in TensorFolw. 

Some key features/ideas/notes:

ImageDataGenerator function: 

  1. rotation_rage(0~180): 40 -> the image will randomly rotate xx amount (0~40 degrees)
  2. width_shift_range/height_shift_range (): 0.2 -> the image will randomly be offset by 20% vertically or horizontally. 
  3. shear_range: 0.2 -> the image will be randomly sheared up to the specified portion of the image 
  4. zoom_range: 0.2 -> 0.2 is the upper relatively portion of the image you will zoom in on. 
  5. horizontal_flip (True/False)
  6. fill_mode ('nearest'): with above operation, which action we should use for lost pixels. 
   
