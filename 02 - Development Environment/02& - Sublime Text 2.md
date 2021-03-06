# Installing Sublime Text 2

## Installing Sublime Text 2

1. Go to [SublimeText.com](http://www.sublimetext.com/) and download the Sublime Text 2 installer.
2. Install it.
3. Input the license.

## Installing subl

This step is optional but very recommended, it installs the subl command to UNIX, so that you can call Sublime Text 2 from anywhere in the Terminal.

`$ sudo ln -s "/Applications/Sublime Text 2.app/Contents/SharedSupport/bin/subl" /usr/local/bin/subl`

# Setting up custom environment (plugins etc.).

## Installing packages

### List of packages

1. Install the Package Control: [WBond.net > Sublime Packages > Package Control](http://wbond.net/sublime_packages/package_control)
2. Install the following packages:

- AdvancedNewFile
- Alignment
- Bracket Highlighter 2 (still in alpha)
- Comments Aware Enter
- DetectSyntax
- DocBlockr
- FuzzyFileNav
- Gist
- Inc-Dec-Value
- INI file Syntax Highlighting
- Markdow Preview
- Nettuts+ Fetch
- PlainTasks
- Prefixr
- RegReplace
- SideBarEnhancements
- Smart Match
- Solarized Color Scheme
- SortTabs
- SublimeLinter
- ThemeChanger (in beta, very recommended)
- Vintage
- VintageEx
- WordCount
- WordHighlight
- ZenCoding or Emmet
- Pretty JSON
- VCS Gutter
- SVN

The "Vintage" and "VintageEx" packages should only be installed if you use Vim, if you like it, or if you're used to it. Also see the the next section if you use Vim.

### Setting up Vintage mode

I suggest that if you're used to Vim, that you install the "Vintage" and "VintageEx" packages. Some extra steps to take to finish installing correctly, add the following to your user preferences file:

`"vintage_start_in_command_mode": true`

Also, make sure to do the following in your Terminal, after which you will need to restart your computer:

`$ defaults write com.sublimetext.2 ApplePressAndHoldEnabled -bool false`

## Installing the theme and the color scheme

### Installing the theme

If you would like to use a good looking theme that's compact and has Retina display support, then you will be very interested in the [Phoenix theme](http://netatoo.github.com/phoenix-theme/), it is beautiful and can be configured to be pretty compact. The instructions are the same as the theme below, or just go to it's GitHub and follow the instructions there.

Alternatively, if you would like to use the Soda theme, which is pretty well known, and has an on-going support, then follow the steps below to install it:<br />
1. Download the Soda theme: [GitHub > buymeasoda > soda-theme](https://github.com/buymeasoda/soda-theme)<br />
OR<br />
Install it with the Package Control package. Shift+Command+p type "install", press enter. Now type "soda theme" and select the right option, it is now installed.
2. Follow these instructions to set it up and use it: [GitHub > buymeasoda > soda-theme > Activating the theme](https://github.com/buymeasoda/soda-theme#activating-the-theme)

Note that I use my own version of this theme, which I have modified to be as compact as possible, but still have it's awesome graphics: [gist: 4002309](https://gist.github.com/4002309)

Check out [this guide](https://github.com/buymeasoda/soda-theme/wiki/Theme-customisation) on having your own customized version of a Sublime Text theme (and using mine if you like it).

### Installing the color scheme

If you use the Solarized (Light, Dark) theme, then I really recommend you check out this GitHub repository: [GitHub > SublimeColors > Solarized](https://github.com/SublimeColors/Solarized)<br />
It is meant to be more true to the original theme, because Sublime Text 2's representation of Solarized is quite wonky.

1. Download the Tomorrow color scheme, the TextMate version: [GitHub > ChrisKempson > Tomorrow-Theme](https://github.com/ChrisKempson/Tomorrow-Theme)
2. To install the Tomorrow color scheme, go to *Sublime Text 2 > Preferences > Browse Packages*, copy the theme to the User directory, now select it on your color schemes.

## Syncing with DropBox

If you want to sync your Sublime Text 2 settings accross all your devices using DropBox, you can follow the instructions in this online article: [Stofke on wheels > Use Dropbox to store your Sublime Text 2 settings, themes and plugins](http://wheels.onebuttonapps.net/2012/04/use-dropbox-to-store-your-sublime-text-2-settings/)

If you don't yet have DropBox, then you really need to get an account, especially if you're constantly on the move. Use the following link to register:<br />
http://db.tt/v3QI85gA<br />
That link will give you an account with an extra amount of space I think, and you will be helping me out by giving me an extra 500MB. If you use it, Thanks!

If you don't want to help me out (you're such a mean person), you can just use the following link:<br />
https://www.dropbox.com

