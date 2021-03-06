picCustom
=========

Python script that allows you to quickly copy and rename a large set of images (e.g. concert or event photos).

#####Settings
- The `typeIn` variable lets you limit the target files to a single filetype
- The remaining variables will determine the new image names of the form `newString + delim + count + typeOut`

#####Example
```
newString = "abcd"          # fixed image base string
delim = "_"                 # delimiter
count = 20                  # starting number for fixed images
pad = 2                     # zero padding for fixed image numbers
typeIn = [".jpg", ".png"]   # filetype of images to fix
typeOut = ".jpg"            # filetype of fixed images
```

The settings above turn ["IMG001.jpg", "IMG002.gif", "IMG003.jpg"] into ["abcd_20.jpg", "abcd_21.jpg"].
- Note that `typeIn = [".jpg", ".png"]` kept the second image, a `.gif` file, from being renamed.
