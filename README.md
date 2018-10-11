# mac-init
A collection of random configuration scripts to help with setting up a new Mac. This is also a list of apps and tools that I like to use.

## _Prerequisites_
[Homebrew](http://brew.sh/)

## Casks
Run `casks.sh` to install a bunch of useful apps, or pick them one at a time from the below table.

Name|Command|Description
---|---|---
[Android Studio](https://developer.android.com/studio/)|`brew cask install android-studio`|Sometimes you've gotta do Android stuff, and this is the best way to get the emulators running.
[Charles](https://www.charlesproxy.com)|`brew cask install charles`|The world's okayest proxy tool for debugging network traffic.
[Chrome](https://www.google.com/chrome/)|`brew cask install google-chrome`|Google's web browser. A nice quarantine for Google's products.
[Dropbox](https://www.google.com/chrome/)|`brew cask install dropbox`|Sync files across all of your devices.
[Flycut](https://github.com/TermiT/Flycut)|`brew cask install flycut`|An amazing little clipboard manager.
[Gifrocket](http://www.gifrocket.com)|`brew cask install gifrocket`|Fast gif creation. :rocket:
[GitKraken](https://www.gitkraken.com)|`brew cask install gitkraken`|A delightful GUI for git.
[Karabiner Elements](https://pqrs.org/osx/karabiner/)|`brew cask install karabiner-elements`|Remap keys and stuff. [Great for external keyboards](https://twitter.com/ioveracker/status/1050051898428948480).
[Ring](https://ring.com)|`brew cask install ring`|The Ring video doorbell Mac app.
[Spotify](http://spotify.com)|`brew cask install spotify`|:notes::notes::notes:
[Steam](https://store.steampowered.com)|`brew cask install steam`|The Steam client for Mac. You can't code _all_ the time.
[Toggl](https://toggl.com)|`brew cask install toggl`|A fantastic way to quantify the time you send on things. The app leaves much to be desired, but is good for small start/stop interactions. The website is much more powerful.
[VSCode](https://code.visualstudio.com)|`brew cask install visual-studio-code`|Quickly becoming the best code editor around. My go-to when I'm not required to use Xcode.

## Formulae
Run `formulae.sh` to install useful command-line utilities.

Name|Command|Description
---|---|---
cloc|`brew install cloc`|A useful command-line utility for **c**ounting the **l**ines **o**f **c**ode in a directory.
heroku|`brew install heroku`|[Heroku](https://heroku.com) CLI toolbelt.
imagemagick|`brew install imagemagick`|Like the name says, this does magical stuff with images. Great for generating diff gifs, etc.
postgresql|`brew install postgresql`|Command-line tools for interacting with postgresql databases.
rbenv|`brew install rbenv ruby-build`|The best Ruby version manager.
redis|`brew install redis`|https://redis.io
telnet|`brew install telnet`|Can you believe macOS doesn't come with telnet? What year is it?!

## Gems
Run `gems.sh` to install all of these gems at once.

Name|Command|Description
---|---|---
bundler|`gem install bundler`|Escape from gem dependency hell. I use bundler to groom my iOS project's gem dependencies and ensure consistent versions are used across dev and build environments.
cocoapods|`gem install cocoapods`|Package manager for iOS projects. You should probably specify this in a Gemfile in your project directory so you can enforce a specific version number.
fastlane|`gem install fastlane`|Automate all of the things. This too should be specified in a Gemfile in your project to keep this in sync across workstations.
xcpretty|`gem install xcpretty`|:sparkles:Prettier xcodebuild output.:sparkles:

## Misc
Miscellaneous things that need to be installed manually.

Name|Command|Description
---|---|---
[Prezto](https://github.com/sorin-ionescu/prezto)|Multiple steps--go [here](https://github.com/sorin-ionescu/prezto).|Instantly awesome zsh. ([Why use zsh?](http://www.slideshare.net/jaguardesignstudio/why-zsh-is-cooler-than-your-shell-16194692))
[Realm Studio](https://realm.io/products/realm-studio/)|A GUI for interacting with [Realm](https://realm.io) database files.
[SimPholders](https://simpholders.com/3/)|Quick access to the apps installed in your iOS simulators. This used to be available on homebrew, but the latest version (v3) does not appear to be there, so it's best to get this from their website.
[Sip](https://sipapp.io)|A better digital color meter.
[zenburn-terminal](https://github.com/bdesham/zenburn-terminal)|N/A|Zenburn theme for Terminal.
[Zenburn for Xcode](https://github.com/ioveracker/Zenburn-for-Xcode)|N/A|Zenburn theme for Xcode

## Missing Something?
Feel free to submit a pull request!
