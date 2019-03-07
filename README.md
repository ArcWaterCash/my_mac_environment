# 僕のMac

```shell
# clone
cd ~/gitrepos
git clone https://github.com/ArcWaterCash/my_mac_environment.git
cd my_mac_environment
```

```shell
# install homebrew
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

```shell
# brew update/upgrade
brew upgrade
brew update
brew cask update
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
# git-lfs(for largefile) install
brew install git-lfs
# cd {repos_dir}
# git lfs install
```

```shell
brew install octave
```
