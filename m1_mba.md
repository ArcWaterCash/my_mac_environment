# m1 mba setting

1. chrome
    ```
    Apple プロセッサ搭載の Mac
    のインストーラーを選ぶ
    ```
1. vscode
    ```
    insider版をインストールする
    https://code.visualstudio.com/insiders/
    ```
1. homebrew
    ```
    sudo mkdir /opt/homebrew
    sudo chown -R $(whoami) /opt/homebrew
    curl -L https://github.com/Homebrew/brew/tarball/master | tar xz --strip 1 -C /opt/homebrew
    
    touch ~/.zshrc
    echo 'export PATH=$PATH:/opt/homebrew/bin' >> ~/.zshrc
    source ~/.zshrc
    
    brew update
    ```
1. git
    ```
    brew install git
    ```

