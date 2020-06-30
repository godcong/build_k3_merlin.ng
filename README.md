# build_k3_merlin.ng

TOP NEW: 新更新添加了编译版本号


采用ghost1988102源码,并合并了上游(asus-merlin.ng)的最新代码.  

https://github.com/ghostnup/asuswrt-merlin.ng  
+  
https://github.com/RMerl/asuswrt-merlin.ng  
=>  
https://github.com/godcong/asuswrt-merlin.ng  


## 附加说明 ##
fork 并修改下列文件的ENV配置可实现MAC地址替换，然后点击右上角的Star开始编译。
1.5小时左右以后，查看自己fork的项目的release接收成果。

文件（.github/workflows/build-rt-k3.yml）请改成自己的MAC地址。

```
  env:
      ET0MACADDR: "00:11:22:33:44:55"    
      MACADDR1_24G: "00:11:22:33:44:66"
      MACADDR2_5G: "00:11:22:33:44:77"
```
对应=>  

(LAN MAC) et0macaddr=00:11:22:33:44:55 -> et0macaddr=XX:XX:XX:XX:XX:XX

(2.4G MAC) 1:macaddr=00:11:22:33:44:66 -> 1:macaddr=XX:XX:XX:XX:XX:XX

(5G MAC) 2:macaddr=00:11:22:33:44:77 -> 2:macaddr=XX:XX:XX:XX:XX:XX


作者原贴请看:


https://www.right.com.cn/forum/forum.php?mod=viewthread&tid=4031512&extra=page%3D1%26filter%3Dtypeid%26typeid%3D15

固件编译时未包含cfe(新版已包含cfe),理论上不会变砖.
万一你刷成砖了,那就是ghost1988102锅,本人啥都没改＾ｖ＾！


### 固件下载地址: ###

https://github.com/godcong/build_k3_merlin.ng/releases

### 你们也可以fork然后star自己编译. ###


砖不砖的我不知道,我只负责编译!　　

砖不砖的我不知道,我只负责编译!　　

砖不砖的我不知道,我只负责编译!　　

重要的事情说三遍.　　


