# koala

## Getting Started with Koala
Koala is an open source GUI compiler for pre-processing languages. It currently supports Less, Sass, Compass, and CoffeeScript out of the box. It is cross-platform.

### Features
1. **Multi-language Support :** There is support for Less, Sass, CoffeeScript and the Compass framework.
2. **Real-time Compilation :** Koala listens for file changes, and compiles them automatically when the file changes. Everything is running in the background without user action.
3. **Compile Options Support :** You can set the compiler options for each file.
4. **Compression :** Koala can automatically compress code after the compilation is completed.
5. **Error Notification :** If Koala encountered an error during compilation, it will display the error message.
6. **Cross-platform :** Koala can run on Windows, Mac and Linux.
***
## Installation Guide
Download your system version of the installation package from the official website. Koala's built-in compiler components can be directly used after installation.

The Sass compiler function needs a system with Ruby installed. If you’re using OS X, you’ll already have Ruby installed. Koala has built-in Ruby on the Windows version.
***
## Add Project
Drag and drop a folder into the window to add a project, or click on the plus icon in the top left corner and select your project folder.

***

## How to run koala?
1. Clone Koala to the local
2. Download [node-webkit(0.8.6 version)](https://github.com/nwjs/nw.js) prebuilt binaries for your system environment.
3. For
     - Windows, copy ``nw.exe, nw.pak, icudt.dll`` to ``koala/src`` directory, and install [Ruby](http://www.ruby-lang.org/en/) to ``koala/src/ruby``.
    - For Linux, copy ``nw, nw.pak``, install Ruby: ``sudo apt-get install ruby``
    - For Mac OS X, copy ``node-webkit.app``, OS X already have Ruby installed.
4. Run the ``nw`` executable file.

