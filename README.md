# mac-init
A collection of random configuration scripts to help with setting up a new Mac. This is also a list of apps and tools that I like to use.

## _Prerequisites_
[Homebrew](http://brew.sh/)

## App Store

Name|Description
---|---
[Realm Browser](https://itunes.apple.com/us/app/realm-browser/id1007457278?mt=12)|A GUI for interacting with [Realm](https://realm.io) database files.
[Sip](https://itunes.apple.com/us/app/sip/id507257563?mt=12)|A better digital color meter.

## Casks
Run `casks.sh` to install a bunch of useful apps, or pick them one at a time from the below table.

Name|Command|Description
---|---|---
Atom|`brew cask install atom`|Emacs or vim? **Atom.** *(And sometimes vim.)*
Chrome|`brew cask install google-chrome`|Google's web browser.
Dropbox|`brew cask install dropbox`|Sync files across all of your devices.
Evernote|`brew cask install evernote`|Notes 'n' stuff.
Flux|`brew cask install flux`|Automatic color temperature adjustments to make eyeballs happy at night. :eyes: :moon:
Gifrocket|`brew cask install gifrocket`|Fast gif creation. :rocket:
Google Drive|`brew cask install google-drive`|Sync files to and from Google Drive.
Simpholders|`brew cask install simpholders`|Quick access to the filesystem on your iOS simulators.
Skitch|`brew cask install skitch`|Better screengrabs, powered by Evernote.
SourceTree|`brew cask install sourcetree`|My favorite Git GUI.
Spotify|`brew cask install spotify`|:notes::notes::notes:

## Formulae
Run `formulae.sh` to install useful command-line utilities.

Name|Command|Description
---|---|---
rbenv|`brew install rbenv ruby-build`|The best Ruby version manager.
xctool|`brew install xctool`|

## Gems

Name|Command|Description
---|---|---
alcove|`gem install alcove`|Painless code coverage reporting for Objective-C projects.
bundler|`gem install bundler`|Escape from gem dependency hell. I use bundler to groom my iOS project's gem dependencies and ensure consistent versions are used across dev and build environments.
cocoapods|`gem install cocoapods`|Package manager for iOS projects. You should probably specify this in a Gemfile in your project directory so you can enforce a specific version number.
fastlane|`gem install fastlane`|Automate all of the nasties.
xcpretty|`gem install xcpretty`|:sparkles:Prettier xcodebuild output.:sparkles:

## Misc

Name|Command|Description
---|---|---
[alcatraz](http://alcatraz.io)|<code>curl -fsSL https://raw.githubusercontent.com/supermarin/Alcatraz/deploy/Scripts/install.sh &#124; sh</code>|Package manager for Xcode plugins.

## Missing Something?
Feel free to submit a pull request!
