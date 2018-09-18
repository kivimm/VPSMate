VPSMate
=========
This is special edition (fork) of VPSMate with many features not existing on VPSMate official release (v1.0 b10).


#### Install
    curl -O https://raw.githubusercontent.com/zjhch123/VPSMate/master/install.py
    python install.py
    

#### UnInstall
    service vpsmate stop
    rm -rf /usr/local/vpsmate
    rm -f /etc/init.d/vpsmate

#### Forget Username & Password
    /usr/local/vpsmate/config.py username '用户名'
    /usr/local/vpsmate/config.py password '密码'

#### Change Log
1. v1.0b10 - 只是fork代码
2. v1.0b11 - 修复获取版本号错误的问题
3. v1.0b12 - 完善自动更新功能