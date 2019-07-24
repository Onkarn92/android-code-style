# Android Code Styles

[![Platform](https://img.shields.io/badge/platform-android-orange.svg)]()
[![license](https://img.shields.io/github/license/mashape/apistatus.svg?maxAge=2592000)](/LICENSE.md)

IntelliJ IDEA/Android Studio code style settings for Effective Digital's android projects.

### Installation

* On Unix, run the `install.sh` script. Windows users should use `install.bat` instead.
* Restart IntelliJ and/or AndroidStudio if it's running.
* Open IntelliJ and/or AndroidStudio, go to Settings -> Editor -> Code Styles and make sure 'EffectiveDigital' is selected as a code style scheme.

### Copyright Config

* Copyright script requires logged in user to fetch a username. Make sure you are logged in to IntelliJ and/or AndroidStudio.
* Open IntelliJ and/or AndroidStudio, go to Settings -> Editor -> Copyright -> Copyright Profiles and Import {PATH_TO_THIS_DIR}\EffectiveDigitalCodeStyle\copyright\EffectiveDigital.xml, Click apply to save the changes.
* Go to Settings -> Editor -> Copyright and select 'EffectiveDigital' as default project copyright.
* Click plus icon (+) to add the scope.
* Select 'All' as a scope, Click apply and ok to save the changes.
* After creating new file, You can see copyright block above the package name.
* To apply copyright block for existing files, go to Code -> Update Copyright, Select scope and hit apply. You should see copyright blocks for selected scope.
* If username is incorrect, go to Help -> Edit Custom VM Options and add this line '-Duser.name={YOUR_USERNAME}'.

### Resetting File Header

* Go to Settings -> Editor -> File and Code Templates, Select 'Includes' tab and select 'File Header'.
* Click icon 'Reset To Default' which will clear out everything in the file header template, Save the changes.

### Contributors
- [Onkar Nene](https://github.com/Onkarn92)
- [Edward Abergas](https://github.com/Bry1337)

### License

```
MIT License

Copyright (c) 2019 Effective Digital

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
