#在Mac上安裝adb
##裝完Android Studio後,sdk預設路徑
```
~/Library/Android/sdk/platform-tools
```
##使用cammad建立
```
echo 'export PATH=$PATH:~/Library/Android/sdk/platform-tools/' >> ~/.bash_profile
```
##然後重開terminal或者使用cammad
```
source ~/.bash_profile
```