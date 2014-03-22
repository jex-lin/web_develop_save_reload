# Introduction

Detect directory, reload current page when file changed.

# Install

    go get github.com/jex-lin/web_develop_save_reload

# How to use

### [1] Install chrome extension

### [2] Execute the command

    web_develop_save_reload -p /tmp/test

### [3] Open chrome extension and type IP / domain

# Option

* `-p` : Watching path. Use `-p /tmp/test` to set watching target.
* `-r` : Watch subfolder under path. Default is recursive. Use `-r=false` to disable recursive watching.
* `-ig` : Ignore file extension changing. Default is `swp|swpx`.  Use `-ig swp|git|swpx|conf` to set ignorant list.

# Notice !!

* Port is 9112, not support other port so far. I will add this option as soon as possible.

# Todo list

### Hot fix

* Dynamic add folder, but not monitor.  If folder and not exist then add to monitor.
* Change port
* watch /tmp currently message on server output

### Miscellaneous

* chrome extension  啟動 save reload 按鈕 分開為 連線及監聽按鈕要分開為兩個checkbox, 結束按鈕就不用了
* UI input directory that i want watching
* - extensions: .html .css .js .png .gif .jpg .php .php5 .py .rb .erb
* - excluding changes in: */.git/* */.svn/* */.hg/*
* Strip -c flag


# Install libsass

Linux :

    cd gosass/libsass
    make
    sudo make install

Mac OS :




