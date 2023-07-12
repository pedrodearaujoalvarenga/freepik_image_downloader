# freepik_image_downloader

This notebook installs required python libraries, opens the Freepik website, searches for images with a desired search tag and download 
multiple images from the search results.

It can be used when it is necessary to download a large number of images, for example, for creating a Machine Learning dataset.
It has 3 parameters on the very beggining of the notebook:

```
image_number = 350 #number of images to download
search_key = 'dessert with solid color background' #search key
folder_path = 'solid-color/desert' #folder will be created if does not exist
```

sometimes the results aren't great and you'll have to manually delete the ones that aren't useful, but it is still better than getting all
images manually one by one.
