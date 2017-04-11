# iphone-5c-4G_crack
+ open mac terminal
  - command:
    * `defaults write com.apple.iTunes carrier-testing -bool YES`
    * OR `defaults write com.apple.iTunes carrier-testing -bool YES`

+ mac下打开iTunes，选择手机，按Option键+Update，就可以跳出选择ipcc文件的界面

+ 打开itunes
  - iphone-5c-4G_crack/yunpan-download/电信4G-9.3.2+
  - 依次刷入
    - `ChinaTelecom_5s_nojb_24.1_iOS9.0-9.3.3_goodbest_1.ipcc`,
    - `ChinaTelecom_5s_nojb_24.1_iOS9.0-9.3.3_goodbest_2.ipcc`,
    - 这两个文件
+ 已经刷入ipcc文件，这个时候你的手机可能会出现“无服务”、“无SIM卡”等提示，不要担心，重启手机
+ 还没结束，在设置－蜂窝移动数据，打开允许“数据漫游”


## details:
```conf
iPhone 5S 不越狱 破解电信4G
支持机型
无锁版5s/5c（A1533/A1453、A1532/A1456）；Mini2 4G版
 
 
特殊情况
2014年9月中旬之后，苹果对电信版国行5s/5c A1533/A1532做了限制，使其无法同时连接到中国电信的3g和4g网络。
翻译过来就是如果你的电信版国行5s/5c A1533/A1532在2014年9月后激活，或DFU刷过机激活，建议你放弃。
A1528/A1530、两网版A1533用户，也不要尝试此教程，不适用。
 
 
教程
 
你需要
 
一台对应型号、对应系统版本的无锁版5s/5c
一台装有最新版iTunes的PC或Mac
两个ipcc运营商文件
（百度网盘下载地址  IPHONE 9.3以下系统用： http://pan.baidu.com/s/1qYiqd2W）
（百度网盘下载地址  IPHONE 9.3以上系统用： http://pan.baidu.com/s/1jIhNjF4）
（百度网盘下载地址  IPAD Mini2 Air1 9系统用： http://pan.baidu.com/s/1eR6H9Iy）
（百度网盘下载地址  IPAD Mini2 Air1 10系统用： http://pan.baidu.com/s/1i5G8mTR）
（百度网盘下载地址  IPHONE5 联通4G专用： http://pan.baidu.com/s/1eSvF9XC）
 
 
 
1 允许iTunes加载ipcc文件
本操作在当前电脑只需执行一次就够了，之后一直有效。重新安装或升级iTunes可能需要再来一遍。
下面的命令执行完毕后，不会有任何提示。反而出错的话会有提示，一般是iTunes路径不对。
 （WIN+R，调出运行，敲入执行命令，回车）
windows32位的用户：
首先请打开命令提示符。然后完整复制下方代码（含引号），回车执行。
"%ProgramFiles%\iTunes\iTunes.exe" /setPrefInt carrier-testing 1
 
如果提示错误，请换下面一种代码执行。之前iTunes安装到非C盘的话，自己改盘符。
"C:\Program Files\iTunes\iTunes.exe" /setPrefInt carrier-testing 1
 
windows 64位的用户：
首先请打开命令提示符。然后完整复制下方代码（含引号），回车执行。如果之前iTunes安装到非C盘的话，自己改盘符
"C:\Program Files\iTunes\iTunes.exe" /setPrefInt carrier-testing 1
 
如果提示错误，请换下面一种代码执行。如果之前iTunes安装到非C盘的话，自己改盘符。
"C:\Program Files (x86)\iTunes\iTunes.exe" /setPrefInt carrier-testing 1

MacOS用户：
请打开Terminal终端。然后完整复制下方代码，回车执行。
defaults write com.apple.itunes carrier-testing -bool true
 
如果不行，请换下面一种代码执行。
defaults write com.apple.iTunes carrier-testing -bool YES
 

 
2 刷入ipcc文件
 
先打开itunes，连上你的iPhone或者iPad。选择好当前已经连接的设备。
然后按住shift键的同时，用鼠标选择“更新”。如图。（Mac用户的话，则需要按住Option键的同时，用鼠标选择“更新”）
然后会出现一个对话框，可以右下角选择文件类型为ipcc，如图。(Mac系统不需要手动选文件类型为ipcc）
如果没有ipcc可以选择，说明刚才第2步操作有误。请重复第2步。之后选好路径和要刷的ipcc，点击确认就行了。
 
 
3 重启iPhone
 
已经刷入ipcc文件，这个时候你的手机可能会出现“无服务”、“无SIM卡”等提示，不要担心，重启手机。
还没结束，在设置－蜂窝移动数据，打开允许“数据漫游”
等待一会，你会发现
然后应该就没有然后了。
 
 
4 不要手贱
 
千万不要点击更新！
千万不要点击更新！
千万不要点击更新！
这是刷ipcc文件破解电信4G的弊端，更新后你的4G就没有了！
需要重新刷入ipcc文件。
```


## resources:
+ http://www.cy2010.com/tips/2942.html
