Vimkeys - Firefox Extension
===========================
*(originally developed/maintained by __hut__, but it seems like it's been abandoned for 2 years)*

This small extension gives you the most useful
keybindings from the text-editor vim.

I want to keep this as small as possible, so there is no
settings window. If you want to add/change keys, please
edit the source and send a pull request.

Installation
------------
You can find and install the latest release directly at [addons.mozilla.org](https://addons.mozilla.org/en-US/firefox/addon/vimkeys/).

If you want the bleeding-edge development edition, then clone this repo into the extensions-folder of your firefox profile-folder and restart firefox
```shell
$ cd ~/Library/Application Support/Firefox/Profiles/fr4vxxec.default/extensions
$ git clone git@github.com:engeld/vimkeys.git vimkeys@engeld.cc
```

Supported keybindings
---------------------
```
Key | Action
----+-------------------------
 k  | scroll up by 1 line
 j  | scroll down by 1 line
 K  | scroll up by 1 page
 J  | scroll down by 1 page
 g  | scroll to top
 G  | scroll to bottom
----+-------------------------
 H  | back in history
 L  | forward in history
 r  | reload
 R  | reload, ignoring cache
 s  | stop loading
----+-------------------------
 h  | previous tab
 l  | next tab
 d  | close tab
 u  | undo closing tab
 t  | new tab
----+-------------------------
 :  | focus address bar
```



[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/engeld/vimkeys/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

