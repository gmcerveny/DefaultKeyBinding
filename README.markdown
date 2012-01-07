This is my default keybindings for OS X. 

Info on keybinds at ADC's [Text Defaults Bindings](http://developer.apple.com/library/mac/documentation/cocoa/conceptual/eventoverview/TextDefaultsBindings/TextDefaultsBindings.html#//apple_ref/doc/uid/20000468-CJBDEADF).

> These notes do apply to Cocoa applications such as Xcode, Interface Builder, TextEdit, and others which use the text system.

> The standard key bindings are specified in /System/Library/Frameworks/AppKit.framework/Resources/StandardKeyBinding.dict. These standard bindings include a large number of Emacs-compatible control key bindings, all the various arrow key bindings, bindings for making field editors and some keyboard UI work, and backstop bindings for many function keys.

> With these bindings it would be necessary to type “Control-Q, Option-f” in order to type a florin character instead of moving forward a word.

This maybe interesting to add as well [Emacs Opt Keybindings](http://www.hcs.harvard.edu/~jrus/Site/KeyBindings/Emacs%20Opt%20Bindings.dict ) with writeup at [Cocoa Text System](http://www.hcs.harvard.edu/~jrus/Site/Cocoa%20Text%20System.html).

Key bindings raise events on NSResponder, and most interesting are the [Action Nessages](http://developer.apple.com/library/mac/documentation/Cocoa/Reference/ApplicationKit/Classes/NSResponder_Class/Reference/Reference.html#//apple_ref/doc/uid/20000015-6949). Note: there don't seem to exist messages for things like sentences.  