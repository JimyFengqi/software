# software
添加自己使用的软件，或者工具

新安装一个ubuntu系统用到的工具或者安装包

## 数据库以及常用工具
```shell
sudo apt-get install redis-server
sudo apt-get install mongodb
sudo apt-get install subverion
sudo apt-get install git
sudo apt-get install tree
```
## python工具
```shell
sudo apt-get install ipython
sudo apt-get install ipython3
sudo apt-get install python-dev
sudo apt-get install python3-dev
sudo apt-get install python-pip
sudo apt-get install python3-pip
sudo apt-get install python3-tk
sudo apt-get install libevent-dev
sudo apt-get install libssl-dev


sudo pip3 install wordcloud jieba wheel
sudo pip3 install echarts  echarts-themes-pypkg 
sudo pip3 install  pyecharts==0.1.9.4 pyecharts-snapshot  pyecharts-javascripthon pyecharts-jupyter-installer 
sudo pip3 install wxpy itchat  
sudo pip3 install requests httplib2 html5lib
sudo pip3 install tushare pandas pillow selenium bs4 pyquery xpinyin demjson  
sudo pip3 install scrapy scrapy_djangoitem  
sudo pip3 install numpy pandas Image opencv-python pyecharts   pymongo redis  
sudo pip3 install django django-admin django-simple-captcha django-pure_pagination django-taggit django-xadmin django-formtools django-import-export  
sudo pip3 install xlrd xlwt xlutils   apscheduler  pyinstaller
sudo pip3 install pygame pyqt5   qdarkstyle   
sudo pip3 install celery pywifi
```

## ruby安装
```shell
sudo apt-get install libxslt-dev libxml2-dev
sudo apt-get install zlib1g-dev  #安装第三方包的依赖库
sudo apt-get install libsqlite3-dev
sudo apt-get install ruby
sudo apt-get install ruby-dev
sudo apt install ruby-bundler
sudo gem install nokogiri
sudo gem install rails
sudo gem install bundler
sudo gem install sass-rails bootstrap-sass
```
## 数据库浏览工具 下载解压安装
```shell
wget http://security.ubuntu.com/ubuntu/pool/main/i/icu/libicu52_52.1-3_amd64.deb
sudo dpkg -i libicu52_52.1-3_amd64.deb
sudo apt-get -f install libicu52
sudo apt-get -f install 

sudo apt-get install sqlitebrowser
sudo snap install redis-desktop-manager
wget https://download-test.robomongo.org/linux/robo3t-1.3.1-linux-x86_64-7419c406.tar.gz

wget https://bitbucket.org/ariya/phantomjs/downloads/phantomjs-2.1.1-linux-x86_64.tar.bz2
tar xvjf phantomjs-2.1.1-linux-x86_64.tar.bz2
sudo cp phantomjs-2.1.1-linux-x86_64/bin/phantomjs /usr/bin/
sudo mv phantomjs-2.1.1-linux-x86_64/bin/phantomjs  /usr/local/src/phantomjs
sudo ln -sf  /usr/local/src/phantojs/bin/phantomjs  /usr/local/bin/phantomjs

wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
sudo dpkg -i google-chrome-stable_current_amd64.deb
wget http://cdn.npm.taobao.org/dist/chromedriver/75.0.3770.8/chromedriver_linux64.zip
unzip chromedriver_linux64.zip
sudo mv chromedriver /usr/local/bin/
wget https://github.com/mozilla/geckodriver/releases/download/v0.24.0/geckodriver-v0.24.0-linux64.tar.gz
tar -zxvf geckodriver-v0.24.0-linux64.tar.gz 
sudo mv geckodriver /usr/local/bin/
rm google-chrome-stable_current_amd64.deb chromedriver_linux64.zip geckodriver-v0.24.0-linux64.tar.gz
```


