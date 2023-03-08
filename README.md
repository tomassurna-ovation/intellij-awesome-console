Install - Tomas
===============
Forked version of this plugin which takes file paths in the console and allows them to be clickable. This is great
because for some reason Rider turned off their stack trace analyze a few years
back (https://youtrack.jetbrains.com/issue/RIDER-5594/Stack-traces-in-Run-or-Debug-windows-arent-clickable).

Making stack traces in the console simple text.

The problem with this plugin is the regex was designed against a different language/logging then we use. Therefore
forking the repo and updating the regex was easier then changing the logging format in our apps (I tried to at first).

To install:
Go to releases of this repo and download the JAR. Then go to Rider > Preferences > Plugins > 3 Vertical Dots In Tabs >
Install Plugin From Disk > Select Jar


Awesome Console
===============

This is a plugin for JetBrains IDEs that finally makes links in your console and terminal at least 200% more awesome!

With this plugin all files and links in the console and terminal will be highlighted and can be clicked. Source code
files will be opened in the IDE, other links with the default viewer/browser for this type.
Now you just need to configure your favorite Logger to include the file name (and optionally a line number) and you can
instantly jump to that file that throws this stupid error.

![](https://github.com/anthraxx/intellij-awesome-console/blob/master/data/screenshot.png)

Links are integrated for the following types:

- source
- file
- url

**(This plugin requires your IDE to run on Java 8 or higher.)**
