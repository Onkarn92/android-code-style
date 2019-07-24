# Android Code Styles
Android studio code style settings for Effective Digital's android projects.

# Installation

 * On Unix, run the `install.sh` script. Windows users should use `install.bat` instead.
 * Restart IntelliJ and/or AndroidStudio if it's running.
 * Open IntelliJ and/or AndroidStudio, go to Settings -> Editor -> Code Styles and make sure 'EffectiveDigital' is selected as a code style scheme.

 
# Copyright Config

 * Copyright script requires logged in user to fetch a username. Make sure you are logged in to IntelliJ and/or AndroidStudio.
 * Open IntelliJ and/or AndroidStudio, go to Settings -> Editor -> Copyright -> Copyright Profiles and Import {PATH_TO_THIS_DIR}\EffectiveDigitalCodeStyle\copyright\EffectiveDigital.xml, Click apply to save the changes.
 * Go to Settings -> Editor -> Copyright and select 'EffectiveDigital' as default project copyright.
 * Click plus icon (+) to add the scope.
 * Select 'All' as a scope, Click apply and ok to save the changes.
 * After creating new file, You can see copyright block above the package name.
 * To apply copyright block for existing files, go to Code -> Update Copyright, Select scope and hit apply. You should see copyright blocks for selected scope.
 * If username is incorrect, go to Help -> Edit Custom VM Options and add this line '-Duser.name={YOUR_USERNAME}'.
 
# Resetting File Header

 * Go to Settings -> Editor -> File and Code Templates, Select 'Includes' tab and select 'File Header'.
 * Click icon 'Reset To Default' which will clear out everything in the file header template, Save the changes.