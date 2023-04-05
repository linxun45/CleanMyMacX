中文使用说明（只支持 Intel，不支持 M1/M2）

1、卸载旧版
2、从系统自带的 App Store 下载正版的CleanMyMac X
3、在桌面新建一个文件夹，比如我新建了一个叫“Test”的文件夹
4、打开“终端”App，然后输入以下内容，并回车：
cd ~/Desktop/Test
5、接着输入以下内容，并回车：
git clone https://github.com/davidepedrazzi/CleanMyMacX.git
6、接着输入以下内容，并回车：
cd CleanMyMacX
7、接着输入以下内容，并回车：
chmod u+x patch.py
8、最后输入以下内容，并回车（这一步才是优雅的关键）：
sudo ./patch.py
或者
sudo python3 ./patch.py 

输入以上内容后，终端显示的结果应该是这样：

$ sudo ./patch.py
Patching /Applications/CleanMyMac-MAS.app/Contents/MacOS/CleanMyMac-MAS...
Patching /Applications/CleanMyMac-MAS.app/Contents/Library/LoginItems/CleanMyMac-MAS Menu.app/Contents/MacOS/CleanMyMac-MAS Menu...
Re-signing /Applications/CleanMyMac-MAS.app...
/Applications/CleanMyMac-MAS.app: replacing existing signature
/Applications/CleanMyMac-MAS.app: valid on disk
/Applications/CleanMyMac-MAS.app: satisfies its Designated Requirement
Enjoy!