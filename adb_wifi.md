# Adb WIFI Connect

## 先將Android device連上usb,找到裝置
```
adb devices
```
看到下面內容

```
List of devices attached
BH9029XC8Z	device
```
## Android device和電腦在同一個wifi下

```
adb -s 裝置名稱 tcpip 5555
```
## 然後看到
```
restarting in TCP mode port: 5555
```
## 就完成了,最後下連線指令
```
adb connect [device private ip]

```
## 完成可以拔usb線Debug了

