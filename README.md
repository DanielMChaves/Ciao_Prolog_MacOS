# [EN] Ciao Prolog installation for MacOS

**Authors:** [Daniel Melero Chaves] (https://github.com/DanielMChaves) y [Carlos Saito Murata] (https://github.com/exacs)

1. Download emacs app

  Download emacs app for macOS from the official web page: https://emacsformacosx.com

2. Install terminal interpreter

  Download the interpreter from the official web page and download Mac OS X (Leopard, Snow Leopard, Lion) http://ciao-lang.org/download_stable.html. If you have another version of macOS, don't worry, it will work the same.

  To check if this installation is working correcly, execute the interpreter in terminal "ciao".

  ![alt text](screenshots/screen_shot_interpreter.png "Interprete Ciao Prolog en terminal")

3. Emacs configuration

  Finally, write this code in the emacs configuration file (.emacs.d/init.el, .emacs.el or similar). This loads the file ciao-mode-init.el so that Ciao prolog works on emacs.

```bash
(if (file-exists-p "/usr/local/lib/ciao/ciao-mode-init.el")
    (load-file "/usr/local/lib/ciao/ciao-mode-init.el"))
```

* This installation has been done in a mac with macOS Sierra.

* Example apperience of Ciao prolog in emacs

![alt text](screenshots/example_interface.jpg "Interprete Ciao Prolog en terminal")

# [ES] Instalación de Ciao Prolog para MacOS

**Autores:** [Daniel Melero Chaves] (https://github.com/DanielMChaves) y [Carlos Saito Murata] (https://github.com/exacs)

1. Descargar la app de emacs

  Descargamos la app de emacs para macOS desde la página web oficial: https://emacsformacosx.com

2. Instalador del interprete en terminal

  Descargamos el interprete desde la página web oficial del desarrollador y nos descargamos la versión para Mac OS X (Leopard, Snow Leopard, Lion) http://ciao-lang.org/download_stable.html. Aunque tengamos otra versión de macOS no pasa nada, nos descargamos esa.

  Una vez instalado, abrimos la terminal para comprobar que tenemos el interprete correctamente instalado. Ejecutamos el interprete escribiendo en terminal "ciao".

  ![alt text](screenshots/screen_shot_interpreter.png "Interprete Ciao Prolog en terminal")

3. Configuración de emacs

  Para finalizar, ponemos el siguiente código en el fichero de configuración de emacs (.emacs.d/init.el, .emacs.el o similar). Esto carga el fichero ciao-mode-init.el para que funcione Ciao prolog en emacs.

```bash
(if (file-exists-p "/usr/local/lib/ciao/ciao-mode-init.el")
    (load-file "/usr/local/lib/ciao/ciao-mode-init.el"))
```

* Esta instalación ha sido realizada en un mac con macOS Sierra.

* Ejemplo del aspecto de Ciao prolog en emacs

![alt text](screenshots/example_interface.jpg "Interprete Ciao Prolog en terminal")
