# 📷 TP 02: Basic Image Operations  BY Dr Guessoum

## 🎯 Objectives  
Learn how to manipulate images by applying basic operations such as inversion (negative creation) and image addition.  

## 📝 Instructions  

### 🔹 1. Image Inversion  
- Load the image **`rose_1024.tif`**.  
- Apply a negative transformation to invert the colors of the image.  
- Compare the original and inverted images by displaying them side by side.  

### 🔹 2. Image Addition  
- Load two images (**`toADD`** and **`rose_1024.tif`**) of the same size or resize them if necessary (using `cv2.resize`).  
- Perform pixel-by-pixel addition of the two images.  
- Ensure the addition values remain within the valid range **(0 to 255)**.  
- Display the resulting image to observe the effects of the addition.  

### 🔹 3. Image Rotation  
- Load the image **`rose_1024.tif`**.  
- Perform a **45° rotation** on the image.  
- Display the resulting image.  

## 🔧 Useful Functions  

### 📌 Image Addition  
After implementing manual pixel addition, use the OpenCV function:  
```python
cv2.add(image1, image2)
