# my_local_env
僕のMac

```shell
# clone
cd ~/gitrepos
git clone https://github.com/ArcWaterCash/my_local_env.git
cd my_local_env
```

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
# install list
pyenv install -l

# set version
pyenv install 3.7.2
pyenv global 3.7.2
pyenv rehash
```

```shell
# install python library
pip install -r requirements.txt
```

```shell
# brew update/upgrade
brew upgrade
brew update
brew cask update
```
