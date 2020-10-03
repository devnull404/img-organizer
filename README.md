# img-organizer
A repository to organize your photos in a folder with personalized tags, by showing you every photo stored in it.

# ¡ADVICE!
In order to prevent data loss, I strongly recomend to create a new folder and copy the images you want to organize as this repo is being developed yet by me, a noob in python. 

## Dependencies
The only dependencies are matplotlib wich you can install by piping and tkinter:
```bash
pip install matplotlib
sudo apt install python3-tkinter (or which applies to your case)
```

## Usage
The main methods in this repo are the ones to create tags and start organizing photos.
```python3
import imginizer

imginizer.addNewTags()
imginizer.identify()

```

### Adding New Tags (imginizer.identify())
First thing you should do before using imginizer.identify() method, is to create new tags to have options to organize your photos. When using it, you will be asked to enter an alias and a category.

```bash
>> iminizer.identify()
Ingresa un alias: b
Ingresa la categoría: beach
```


And you will be asked to set an category and a alias respectively, for example:

```
name: alias
beach: b
mexico: mx
home: h
```

The result for an input like IMG_n.jpg finally must be something like this:

```
Directory input:

IMG_4324324.jpeg
IMG_4534534.jpg
IMG_6452775.jpg
IMG_4567742.png
IMG_7907655.jpg
IMG_5437235.jpg
IMG_7642454.jpg
IMG_5435587.png
IMG_9564869.jpg
IMG_5547891.jpg
IMG_8568492.jpg
IMG_2430285.jpeg

Output:

beach1.jpg
beach2.jpg
beach3.jpg
beach4.png
home1.png
home2.jpeg
home3.jpg
mexico1.jpg
mexico2.jpg
mexico3.jpg
mexico4.jpg
mexico5.jpg
```

