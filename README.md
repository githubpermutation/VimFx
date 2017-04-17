# VimFx – Vim keyboard shortcuts for Firefox

<img src="extension/skin/icon128.png" alt="" align="right">

[VimFx] is a Firefox extension which adds short, Vim-style keyboard shortcuts
for browsing and navigation, for a near mouseless experience.

- Doesn’t change your browser in any way. Everything can be disabled.
- Easy for beginners, powerful for advanced users. Not just for Vim fanatics.
- Modeled after [Vimium] for Chrome.

**New to VimFx?** Check out [Questions & Answers]!  
Power user? Make a [config file]!  
In either case, have look at the the [documentation] and the [wiki].  
Also check out **[the future of VimFx].**

VimFx is made by [these awesome people][people].

[VimFx]: https://addons.mozilla.org/firefox/addon/vimfx
[Vimium]: http://vimium.github.io/
[Vimperator]: http://www.vimperator.org/vimperator
[config file]: https://github.com/akhodakivskiy/VimFx/blob/master/documentation/config-file.md
[documentation]: https://github.com/akhodakivskiy/VimFx/tree/master/documentation#contents
[wiki]: https://github.com/akhodakivskiy/VimFx/wiki
[Questions & Answers]: https://github.com/akhodakivskiy/VimFx/tree/master/documentation/questions-and-answers.md
[the future of VimFx]: https://github.com/akhodakivskiy/VimFx/issues/860
[people]: https://github.com/akhodakivskiy/VimFx/blob/master/PEOPLE.md

## Why VimFx was created

> Even before [Vimium] there was [Vimperator] for Firefox. In my opinion,
> Vimperator has too many features and aggressively changes the default Firefox
> appearance and behavior. Vimium is exactly what I need in terms of added
> functionality, but for Chrome. That’s why I decided to develop a similar
> extension for Firefox.
>
> &nbsp;**VimFx will be nice to your browser and to your habits. Promise.**
>
> – _Anton Khodakivskiy,_ VimFx’s original author.

## Key Features

VimFx has concise shortcuts for most commonly performed actions. Many simply
invoke standard Firefox features. That is preferred over re-implementing similar
functionality.

Press <kbd>f</kbd> to mark links, text inputs and buttons on the page. Then
either type the [_hint_ or the _text_][hint-chars] of a marked element to click
it. This command has many variations, for example to copy links or open them in
new tabs.

Search with <kbd>/</kbd> and cycle between matches with <kbd>n</kbd> and
<kbd>N</kbd>.

Open a new tab with <kbd>t</kbd>, close it with <kbd>x</kbd>. Reopen it again
with <kbd>X</kbd>. Switch between tabs with <kbd>J</kbd> and <kbd>K</kbd>, or
some of the several other tab commands.

Scrolling left/down/up/right: <kbd>h</kbd>, <kbd>j</kbd>, <kbd>k</kbd>, <kbd>l</kbd>.  
Top/Bottom: <kbd>gg</kbd>, <kbd>G</kbd>.  
Page up/down: <kbd>space</kbd>, <kbd>shift-space</kbd>.  
Half a page: <kbd>d</kbd>, <kbd>u</kbd>.

Use [Caret mode] to copy text without using the mouse.

There are of course many more shortcuts! Press <kbd>?</kbd> to see them all, and
then <kbd>/</kbd> to search among them. Click on a command or open VimFx’s
[options] page in the Add-ons Manager to customize the [default shortcuts].

You can temporarily disable VimFx by using Ignore mode. Press <kbd>i</kbd> to
enter it, and <kbd>shift-escape</kbd> to exit. Use the [blacklist] to
automatically enter Ignore mode on specific sites.

There’s also an [article on ghacks.net][ghacks] which is a good introduction.

[hint-chars]: https://github.com/akhodakivskiy/VimFx/blob/master/documentation/options.md#hint-characters
[Caret mode]: https://github.com/akhodakivskiy/VimFx/blob/master/documentation/commands.md#the-v-commands--caret-mode
[options]: https://github.com/akhodakivskiy/VimFx/blob/master/documentation/options.md
[default shortcuts]: https://github.com/akhodakivskiy/VimFx/blob/master/extension/lib/defaults.coffee
[blacklist]: https://github.com/akhodakivskiy/VimFx/blob/master/documentation/options.md#blacklist
[ghacks]: http://www.ghacks.net/2016/07/01/vimfx-improve-firefox-keyboard-use/

## Feedback

Enjoying VimFx? [Write a review][review]!

Having a problem? Report it in the [issue tracker]!

[review]: https://addons.mozilla.org/firefox/addon/vimfx/reviews/add
[issue tracker]: https://github.com/akhodakivskiy/VimFx/issues
