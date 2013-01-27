Plugin for PunBB BBCode buttons
===============================

Enables a toolbar for text formatting in PunBB when creating new forum posts.


Description
-----------

This plugin is forked from version 1.2.2 of the 
[official PunBB BBCode plugin](http://punbb.informer.com/svn/additions/punbb-1.3/extensions/pun_bbcode/). 
(It's therefore distributed under a GPL v2 license).

The code is almost identical, we have just extended the toolbar to include images for
3 extra custom bbcode tags, used by the 
[PunBB Card Tooltips](https://github.com/SebastianZaha/punbb_card_tooltips) plugin.


Usage
-----

To install download and extract 
[this repository's zipfile](https://github.com/SebastianZaha/punbb_bbcode/archive/master.zip) 
in your forums' extension folder. Then enable the plugin through the forums'
administration / extensions interface.

Please uninstall the official punbb_bbcode plugin if you are already using it.

After installing, 3 extra buttons will exist when posting, one each for Magic the Gathering, 
World of Warcraft Trading Card Game and Warhammer Invasion respectively. The extra bbcode tags
are `[mtg]`, `[wow]`, `[whi]`. For details, please see the documentation for the plugin provinding 
these tags: [PunBB Card Tooltips](https://github.com/SebastianZaha/punbb_card_tooltips).


Examples
--------

If you have an account on deckbox.org trying to *post reply* anywhere will display the formatting
buttons.


Support and development
-----------------------

If you run into problems installing or using the plugin, please contact 
[support@deckbox.org](mailto:support@deckbox.org).

If you would like to contribute, I will gladly accept pull requests.
