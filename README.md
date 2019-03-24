# macOS Setup

#### System Preferences changes

1. Use tab key to shift focus between input elements in dialog boxes and other similar kind of forms.  
_System Preferences > Keyboard > Shortcuts > (Full Keyboard Access: In win...)_

2. Disable auto adjustment of keyboard brightness.  
_System Preferences > Keyboard > Keyboard > __Uncheck__ (Adjust keyboard bright...)_

3. Do not dim the display when battery powered.  
_System Preferences > Energy Saver > Battery > __Uncheck__ (Slightly dim the display...)_

4. Position of the dock.  
_System Preferences > Dock > Position on screen: Left_

5. Hide the dock by default.  
_System Preferences > Dock > __Check__ (Automatically hide...)_

6. Tap to click.  
_System Preferences > Trackpad > Point & Click > __Check__ Tap to click_

7. Invert scroll direction.  
_System Preferences > Trackpad > Scroll & Zoom > __Uncheck__ Scroll direction: Natural_

8. Do not rearrange workspaces.  
_System Preferences > Mission Control > __Uncheck__ (Automatically rearrange...)_

9. Disable auto adjustment of screen brightness.  
_System Preferences > Displays > __Uncheck__ Automatically adjust brightness_

#### Finder Preferences changes

1. Show home directory when opening in new Finder window.  
_Finder Preferences > General > New Finder windows shows: __username___

2. Show folders on top.  
_Finder Preferences > Advanced > __Check__ (Keep folders...)_

3. Search in current folder only.  
_Finder Preferences > Advanced > (When perf...): Search the Current Folder_

#### Misc

* Change location where screenshots get saved.
```sh
defaults write com.apple.screencapture location [location]
killall SystemUIServer
```

#### The Apps

1. Homebrew
2. Use ZSH shell with Oh My Zsh framework
* Explore theme for ZSH
3. iTerm2
* Disable close confirmation prompts  
_Preferences > General > Closing > __Uncheck__ Confirm closing... and Confirm "Quit..._
* Open new tab in the current directory  
_Preferences > Profiles > General > Working Directory > __Select__ Reuse previous..._
* Always open in fullscreen mode  
_Preferences > Profiles > Window > Style > __Select__ Fullscreen_
* Enable word jumping  
_Preferences > Profiles > Keys > Load Preset... > __Select__ Natural Text..._
4. mpv
```sh
brew cask install mpv
```
