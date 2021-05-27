# Custom-dataset
For creating a custon dataset, the steps are:
1. Google the image you want to search.
2. Keep scrolling down untill you find the images you want.
3. Open Inspect element and go to console and paste the content of browser.js
4. Open treminal and run 
```
python download_images.py --urls urls.txt --output images/class
```
This would create a folder named images with class as a subfolder and downlaod all the images from urls.txt


