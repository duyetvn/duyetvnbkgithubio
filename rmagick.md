Link: https://stackoverflow.com/questions/16774501/rmagick-gem-installation-issue

```
Building native extensions.  This could take a while...
ERROR:  Error installing rmagick:
    ERROR: Failed to build gem native extension.

        /usr/local/bin/ruby extconf.rb
```

### Ubuntu
```
sudo apt-get install libmagickwand-dev imagemagick
```


### Macos
```
brew install imagemagick@6
brew link --force imagemagick@6
gem install rmagick
```
