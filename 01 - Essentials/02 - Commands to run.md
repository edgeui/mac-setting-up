## The commands

The following are must-do commands in order to configure Mac OS X Mountain Lion to our liking.

To show hidden files (.fileName):<br />
`$ defaults write com.apple.Finder AppleShowAllFiles YES`<br />
`$ killall Finder`

To disable .DS_Store files:<br />
`$ defaults write com.apple.desktopservices DSDontWriteNetworkStores true`

To have the 2D dock:<br />
`$ defaults write com.apple.dock no-glass -boolean YES`<br />
`$ killall Dock`

To disable Spotlight:<br />
`$ sudo mdutil -a -i off`<br />
`$ sudo chmod 600 /System/Library/CoreServices/Search.bundle/Contents/MacOS/Search`<br />
`$ killall -HUP SystemUIServer`
