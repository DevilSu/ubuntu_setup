# SublimeText3

- [SublimeText3](#sublimetext3)
  * [Shortcuts](#shortcuts)
  * [Install "Package Control" package](#install--package-control--package)
    + [1. From terminal](#1-from-terminal)
    + [2. Manually](#2-manually)
  * [Install packages](#install-packages)
  * [Remove packages](#remove-packages)
  * [Some settings](#some-settings)
  * [Some useful packages](#some-useful-packages)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>

## Shortcuts
``crtl+` `` : open terminal(sublime terminal, not ubuntu terminal)

## Install "Package Control" package
Reference: https://packagecontrol.io/installation#st3.

### 1. From terminal
- Hit ``crtl+` `` to open terminal, or click "**View->Show Console**".
- Copy paste these into terminal and press ``Enter``.
```
import urllib.request,os; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); open(os.path.join(ipp, pf), 'wb').write(urllib.request.urlopen( 'http://sublime.wbond.net/' + pf.replace(' ','%20')).read())
```

- Or for SublimeText2
```
import urllib2,os; pf='Package Control.sublime-package'; ipp = sublime.installed_packages_path(); os.makedirs( ipp ) if not os.path.exists(ipp) else None; urllib2.install_opener( urllib2.build_opener( urllib2.ProxyHandler( ))); open( os.path.join( ipp, pf), 'wb' ).write( urllib2.urlopen( 'http://sublime.wbond.net/' +pf.replace( ' ','%20' )).read()); print( 'Please restart Sublime Text to finish installation')
```

### 2. Manually
- Click "**Preference->Browse Packages...**", this will open a folder.
- Goto the parent folder, then goto "**Installed Packages**" folder.
- Download [Package Control.sublime-package](https://packagecontrol.io/Package%20Control.sublime-package) and save it in "**Installed Packages**" folder.
- Restart SublimeText.

## Install packages
- Hit ``crtl+shift+p``, or click "**Preferences->Package Control**".
- Search for "**Package Control: Isntall Package**".
- Then type the package name.

## Remove packages
- Hit ``crtl+shift+p``, or click "**Preferences->Package Control**".
- Search for "**Package Control: Remove Package**".
- Then type the package name.

## Some settings
- Click "**Preferences->Settings**".
- Edit the file on the right.
	* "font_face": "ubuntu mono"
    * "font_size": 14
    * "margin": 0
    * "line_padding_top": 1
    * "line_padding_bottom": 1

## Some useful packages
Reference https://www.youtube.com/watch?v=oHmPrjSzmwU&t=1031s.

- [Emmet](https://packagecontrol.io/packages/Emmet), sense what you are typing and auto-complete for you.
- [CodeIntel](https://packagecontrol.io/packages/SublimeCodeIntel), jump to function definition.
- [Material Theme](https://packagecontrol.io/packages/Material%20Theme), fine-tuning the theme.
- [Sidebar Enhancements](https://packagecontrol.io/packages/SideBarEnhancements), more options while right-click on files in sidbar.
- [Advanced New File](https://packagecontrol.io/packages/AdvancedNewFile), create file quickly. (Can done with Sidebar Enhancements)
- [Git Gutter](https://packagecontrol.io/packages/GitGutter), show * in front of the line for git difference.
- [DocBlockr](https://packagecontrol.io/packages/DocBlockr), comment extension tool.
- [SublimeLinter](https://packagecontrol.io/packages/SublimeLinter), point out error before compile.
- [Colorsublime](https://packagecontrol.io/packages/Colorsublime), change color of code instantly. (Use "**Monokai**"!)
- [MarkdownPreview](https://packagecontrol.io/packages/MarkdownPreview), preview .md on browser.

<meta http-equiv="refresh" content="1">