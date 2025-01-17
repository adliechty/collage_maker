This is a clone from: [collage_maker](https://github.com/delimitry/collage_maker)

Collage maker
=============

Picture collage maker in Python

Usage:
------
The usage of `collage_maker.py` is very simple:
```
  -h, --help            show this help message and exit
  -f FOLDER, --folder FOLDER
                        folder with images (*.jpg, *.jpeg, *.png)
  -o OUTPUT, --output OUTPUT
                        output collage image filename
  -w WIDTH, --width WIDTH
                        resulting collage image width
  -i INIT_HEIGHT, --init_height INIT_HEIGHT
                        initial height for resize the images
  -s, --shuffle         enable images shuffle
  -n NUM_CALLAGES, --num_callages NUM_CALLAGES
                        How many calages to make total
```

Example:
```
collage_maker.py -o my_collage.png -w 800 -i 250 -s
```

Description:
------------

Description of algorithm is available in my blog:
http://delimitry.blogspot.com/2014/07/picture-collage-maker-using-python.html

License:
--------
Released under [The MIT License](https://github.com/delimitry/collage_maker/blob/master/LICENSE).
