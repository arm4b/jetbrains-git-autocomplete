# Jetbrains IDE git autocomplete
Provides git autocompletion support for command line console in Jetbrains IDEs: PyCharm, PhpStorm


##### 1.) Install plugin: `Command Line Tool Support`
Settings -> Plugins -> Install JetBrains plugin...

##### 2.) Configure it for `git`
* Add new configuration: Settings -> Tools -> Command Line Tool Support -> +
* After adding, edit the configuration (click ![Edit definition in editor](http://i.imgur.com/ANqYO2a.gif))
* Paste the contents of [`git.xml`](./git.xml) in opened file. Optionally enhance it for your needs.

##### 3.) Run the console: `Ctl+Shift+X`
![Git Autocompletion in PyCharm IDE](http://i.imgur.com/BSBxAV2.gif)
