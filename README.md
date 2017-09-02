# cpu12

CPU12 assembly language support for Sublime Text 3

## Features

![Syntax example](https://raw.githubusercontent.com/heztet/cpu12-sublime/master/example.png)

This package includes the grammar for the Motorola CPU12 core instruction set, defined in the [CPU12/CPU12RM manual](http://www.nxp.com/docs/en/reference-manual/CPU12RM.pdf).

Modified from my [VSCode CPU12 extetnsion][1].

## Install CPU12

- Go to *Preferences* > *Browse Packages...*, then go to the User folder
- Put the file `CPU12.tmLanguage` in the User folder
- Restart Sublime Text 3
- Open any file that ends with `.asm` to test the syntax highlighting

## Modify CPU12

*(These steps largely come from the [sublime unofficial docs](http://docs.sublimetext.info/en/latest/extensibility/syntaxdefs.html))*
- (Optional) Get the latest updated version of [cpu12.tmLanguage.json][2] from the VSCode extension. From here you can either convert the JSON into YAML ([old way](http://sublimetext.info/docs/en/extensibility/syntaxdefs.html)) or convert it into YAML first and work there
- Modify the `CPU12.YAML-tmLanguage` to fit your needs
- Using PackageDev, convert the YAML version into the plist/.tmLanguage version (it should be an XML format when you open it)
- Restart Sublime Text to see if your changes worked