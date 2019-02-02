# my_local_env
僕のMac

```shell
# install homebrew
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

```shell
# install chrome
brew cask install google-chrome
```

```shell
# install vs-code
brew cask install visual-studio-code
```

```shell
# install pyenb
brew install pyenv
echo 'eval "$(pyenv init -)"' >> ~/.bash_profile
exec $SHELL -l
```

```shell
# install anaconda
pyenv install -l | grep anaconda

# set version
pyenv install anaconda3-x.x.x
pyenv global anaconda3-x.x.x
```
