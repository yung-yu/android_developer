# 在Mac上安裝adb
## 裝完Android Studio後,sdk預設路徑
```
~/Library/Android/sdk/platform-tools
```
## 使用cammad建立
```
echo 'export PATH=$PATH:~/Library/Android/sdk/platform-tools/' >> ~/.bash_profile
```
## 然後重開terminal或者使用cammad
```
source ~/.bash_profile
```
## 如果有使用on-my-zsh會有重開後,出現問題
```
zsh: command not found adb:adb
``` 
> 1. 打開.zshrc文件檔
> 
> ```
> open .zshrc
> ```
> 2.找到  # User configuration,貼上下面內容
> 
> ```
> source ~/.bash_profile
> ```

## 依照步驟完成後重開就正常了

# 環境 windows 7
## 設定環境變數

## .android 
```
加入環境變數
ANDROID_SDK_HOME : sdk path
```
## .gradle
```
加入環境變數
GRADLE_USER_HOME = gradle  cache path
```
## .AndroidStudio
```
安裝路徑\Android stuido\bin\idea.properties
idea.config.path=D:/.AndroidStudio/config
idea.system.path=D:/.AndroidStudio/system
```

## .MAC投影

https://github.com/Genymobile/scrcpy

