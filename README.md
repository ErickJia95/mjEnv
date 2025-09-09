#第一步
/bin/bash -c "$(curl -fsSL https://mirrors.ustc.edu.cn/misc/brew-install.sh)"
/usr/local/bin/brew update --force --quiet
brew install --cask visual-studio-code
brew install --cask pycharm
brew install --cask jetbrains-toolbox
brew install --cask apifox

source ~/.zshrc

git clone https://codeup.aliyun.com/chuangyuan/android/script/AndroidScript.git
git clone https://codeup.aliyun.com/chuangyuan/android/script/HttpScript.git
git clone https://codeup.aliyun.com/672c8a3c2e4840914701d975/flaskProject.git

#第二部
brew install openjdk@17
brew install python@3.10
brew install mysql
brew tap mongodb/brew && brew install mongodb-community
brew install redis
/usr/local/opt/python@3.10/bin/python3.10 -m pip install --upgrade pip

