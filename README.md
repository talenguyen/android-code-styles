Java Code Styles
================

IntelliJ IDEA code style settings for Tiki’s Java and Android projects.

Installation
------------

 * Run the `install.sh` script.
 * Restart IntelliJ if it's running.
 * Open IntelliJ Project Settings -> Code Styles, change the code style for the
   project to the one you want.

Tips: re-format on save
----

With 3 simple steps you can reorder and reformat your code automatically with `⌘ + S`

 1. Make sure a Java source file has focus (or you can’t record all steps)
 2. Record a macro

    * Select `Edit > Macros > Start Macro Recording`
    * Select `Code > Optimize Imports`
    * Select `Code > Reformat Code`
    * Select `Code > Rearrange Code`
    * Select `File > Save All`
    * Select `Edit > Macros > Stop Macro Recording` and give it a name (mine is OptimizeImportsReformatRearrangeSave)
 3. Assign a shortcut

    * Go to `Preferences > Keymap`
    * Find the Macro section
    * Add `⌘ + S` shortcut for the new macro

thanks @passsy @grandcentrix for the [tips][1]

License
-------

    Copyright (C) 2017 Tiki Corp

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

[1]: https://android.jlelse.eu/7-reasons-this-android-code-style-improves-your-productivity-65d196fa55f