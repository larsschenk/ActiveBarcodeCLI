# ActiveBarcodeCLI

###  A non-interactive barcode image creator

ActiveBarcodeCLI is open source. You can redistribute and/or modify it under the terms of the GNU GPL.

ActiveBarcodeCLI is a bash file as a wrapper tool for the  ActiveBarcode REST API to easily create highly accurate barcode images at the command line. It can be used to create png and jpg bitmaps. It helps to automate your barcode needs, is versatile in use and platform independent. The only requirement is access to the ActiveBarcode REST API and wget.

### Usage: ActiveBarcodeCLI [OPTION]... [FILENAME]...

[FILENAME] must use .png or .jpg to determine the image file format.

  --help  
  display detailed help  

### Examples of usage:

ActiveBarcodeCLI barcode.jpg  
ActiveBarcodeCLI --text=192837465012 --code=ean13 --width=400 --height=200 ean.png  
ActiveBarcodeCLI --text='Hello World!' --type=14 --width=500 --height=100 code128.jpg  


For a faster, enhanced, universal powerful but windows only alternative use  
[ActiveBarcodeCLI.exe](https://www.activebarcode.com/commandline/) &#128640;


----
ActiveBarcodeCLI is free software; you can redistribute it and/or
modify it under the terms of the GNU General Public License
as published by the Free Software Foundation; either version 2
of the License, or any later version.

ActiveBarcodeCLI is published on github WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
See the GNU General Public License for more details.

ActiveBarcode &copy; by the ActiveBarcode developers, [www.activebarcode.com](www.activebarcode.com).