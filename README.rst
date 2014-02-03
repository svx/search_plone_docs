A Sublime Text 2/3 plugin
-------------------------

A command to search developer.plone.org for the current word.

Supports
~~~~~~~~

* Plone

Submit a patch adding more and I'll include it.

Usage
~~~~~
Open the command palette (cmd-shift-p) and choose "Search PloneDocs" while your cursor is on a word.

Make a keybind by adding the following to your `User/Default (OSX).sublime-keymap`:

  { "keys": ["super+shift+a"], "command": "cakephpapi_search_selection" },
  { "keys": ["ctrl+shift+a"], "command": "cakephpapi_search_from_input" }


Install
-------

Without Git
~~~~~~~~~~~

Download the latest source zip from [github](https://github.com/svx/search_plone_docs/zipball/master) and extract the files to your Sublime Text "Packages" directory, into a new directory named Search PloneDocs.

With Git
~~~~~~~~

OSX
---

  $ cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/
  $ git clone git://github.com/svx/search_plone_docs.git "Search PloneDocs"

Linux (Ubuntu like distros)
---------------------------

  $ cd ~/.config/sublime-text-2/Packages/
  $ git clone git://github.com/svx/search_plone_docs.git "Search PloneDocs"


