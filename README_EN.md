# [EN] Ciao Prolog installation for MacOS

[![English](http://upload.wikimedia.org/wikipedia/commons/e/e1/Union_Jack_22x16.png "English")](README_EN.md)
[![Español](http://upload.wikimedia.org/wikipedia/commons/3/30/Flag_of_spain.png "Español")](README_ES.md)

**Authors:** [Daniel Melero Chaves] (https://github.com/DanielMChaves) y [Carlos Saito Murata] (https://github.com/exacs)

1. Download emacs app

  Download emacs app for macOS from the official web page: https://emacsformacosx.com

2. Install terminal interpreter

  Download the interpreter from the official web page and download Mac OS X (Leopard, Snow Leopard, Lion) http://ciao-lang.org/download_stable.html. If you have another version of macOS, don't worry, it will work the same.

  To check if this installation is working correcly, execute the interpreter in terminal "ciao".

  ![alt text](screenshots/screen_shot_interpreter.png "Interprete Ciao Prolog en terminal")

3. Emacs configuration

  Finally, write this code in the emacs configuration file (.emacs, .emacs.d/init.el, .emacs.el or similar). This loads the file ciao-mode-init.el so that Ciao prolog works on emacs.

```bash
(if (file-exists-p "/usr/local/lib/ciao/ciao-mode-init.el")
    (load-file "/usr/local/lib/ciao/ciao-mode-init.el"))
```

* This installation has been done in a mac with macOS Sierra.

* Example apperience of Ciao prolog in emacs

![alt text](screenshots/example_interface.jpg "Interprete Ciao Prolog en terminal")
