# Achari
![Achari help](https://raw.githubusercontent.com/xtiankisutsa/achari/master/images/help.png)

## What is achari?
Achari is a nifty tool that you can use to convert KeepNotes in a specified folder into the PDF format.The tool is mostly in the PoC stage and hence cannot yet convert all notes in the main KeepNote folder into PDF. Achari is also capable of converting Keep Notes into a single image in PNG format. 

### Installing dependencies
    sudo apt-get install openssl libssl-dev figlet

### Configure permissions
    chmod u+x achari/achari.sh
    chmod u+x achari/tools/wkhtml*

### Folder structure
In order to make use of Achari, your Keep Notes have to adhere to a strict folder structure. This is where all folder and subfolder names **MUST** be preceded with a numerical value in ascending order.The images below, illustrate the supported folder structure. 

![Folder structure 1 image](https://raw.githubusercontent.com/xtiankisutsa/achari/master/images/folders_1.png)

![Folder structure 2 image](https://raw.githubusercontent.com/xtiankisutsa/achari/master/images/folders_2.png)

If you would like to read about my blog post on this tool, you can find it [here](http://www.shadowinfosec.io/2017/02/achari-converting-keepnotes-to-pdf-and.html)

## To do list
Achari is more of a PoC tool. I intend to work on the following features in due time: 
* Ability to customize PDF headers, font, etc. 
* Ability to create a cover page on the PDF
* Ability to create a table of contents for the PDF document
* Ability to convert multiple Keep Notes at a time
* Add native support for OS X and Windows 
* Develop achari into a KeepNote extension

## Credits
These are the people who came up with the idea and assisted beta test the tool. 
* Jade - [@0x7678](https://twitter.com/0x7678) - http://blog.0x7678.com/
* Gabby - [@_V1VI](https://twitter.com/_V1VI) - https://thevivi.net
* Trune - [@truneski](https://twitter.com/truneski)
* Ruby - [@doobie](https://twitter.com/___doobie___)
