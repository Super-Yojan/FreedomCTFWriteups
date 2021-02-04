# Android 16

First I started by downloading the file

![](./first.png)

Next I dowloaded the apktool

```
sudo apt install apktool -y
```

![](./second.png)

After Installing that, I used this command to decode the file

```
apktool d app-debug.apk
```

![](./fourth.png)

![](./fifth.png)

Then in 
```
/app-debug/smali/com/example/myapplication/MainActivity.smali
```
We can find the flag

![](./sixth.png)