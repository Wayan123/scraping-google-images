# Scraping Google Images

This method is suitable for downloading images from Google Images to be used in deep learning datasets, such as for YOLO or Transfer Learning.

## How to use:

0. Clone this repo with 'git clone https://github.com/Wayan123/scraping-gambar-google.git'.
1. Install requirements with 'pip install -r requirements.txt'.
2. Open Google Images, then search for the images you want to download, for example, apples, and then scroll down until all the images cannot be displayed anymore.
3. On the same page where we searched for the images, find Developer Tools or you can also use CTRL+SHIFT+I.
4. Click on the console and then paste the code from js_code.js, then press enter and wait a moment until urls.txt is downloaded with the image URLs.
5. Once urls.txt is downloaded, move it to the directory/folder of the git clone result, and also create a new directory to store the images that will be downloaded later.
6. Run the Python code to start downloading images by typing "python image-downloader2.py -u urls.txt -o directory-name".
7. Wait until the download process is complete, and you can view the contents of the image directory where the images will be downloaded one by one.

Happy Deep Learning!
