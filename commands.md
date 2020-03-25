## Mac show hidden files

```
defaults write com.apple.finder AppleShowAllFiles TRUE
killall Finder
```

# set sublime command as terminal command

```
sudo ln -s "/Applications/Sublime Text.app/Contents/SharedSupport/bin/subl" /usr/local/bin/subl
```

# Install Ohmyzsh

# https://github.com/robbyrussell/oh-my-zsh

```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

## Make sublime text the default text editor

defaults write com.apple.LaunchServices LSHandlers -array-add '{LSHandlerContentType=public.plain-text;LSHandlerRoleAll=com.sublimetext.3;}'
