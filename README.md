# Apex_Legends-Logit-G-series-Lua-script 
一个Apex Legends压枪罗技宏
## 安装
### 自动识别武器版

* 下载Ultimate.lua后从GHUB为Apex Legends新建指令码后导入脚本。
* 从[Apex_Legends-auto_recgonize_weapons](https://github.com/zz824865454/Apex_Legends-auto_recgonize_weapons/releases)下载并解压。

### 手动设置武器版

* 下载Ultimate.lua后从GHUB为Apex Legends新建指令码后导入脚本。

## 使用

### 自动识别武器版

* 编辑GHUB内Apex Legends导入后的指令码，将

```
    version = x
```
* 改为

```
    version = 2
```

* 若Windows显示缩放为100%游戏分辨率与桌面相同，且分辨率为1280\*1080或2560\*1080则可直接打开AutoRecoginze.exe，任务管理器出现进程后进入游戏即可。
* 游戏内灵敏度设置2.5。

### 手动设置武器版

* 编辑GHUB内Apex Legends导入后的指令码，将

```
    version = x
```

* 改为

```
    version = 1
```

* 设置

```
------------------------------------------------------------------------------------
------------------------------------SetGunKey---------------------------------------
Target=1 --Target Key 1:light 2:right 3:middle

SetGunKey_User1=4 --mouse key
R99_Key="lalt"
R301_Key="lshift"
PX_Key="lctrl"
DN_Key="ralt"
M600_Key="rshift"
RE45_Key="rctrl"

SetGunKey_User2=5
ZHZ_Key="lalt"
ZZ_Key="lshift"
LS_Key="lctrl"
LSTAR_Key="ralt"
HWK_Key="rshift"
HWK_WL_Key="rctrl"
```
* 操作为按住鼠标4号键或者5号键并按下键盘左右alt，shift，ctrl键盘即可设置对应枪械。
* 游戏内灵敏度设置2.5。

## 说明
* 下为设置宏开启模式，1为按下一次开关键后左键开火即有压枪，2为按住右键左键开火即有压枪，3为按下开关键且按住右键，4为按下开关键或者按住右键。

```
    KaiGuan="capslock" --KaiGuanJian
    offset_pattern = 3     --1.KaiGuan    2.YouJian   3.KaiGuan AND YouJian   4.KaiGuan OR YouJian
```

* 下为设置自动模式下的键盘停止压枪按键，LSKG=1为使能按下lalt可以在错误时停止压枪，比如2，4模式下往往舔包点击左键也有压枪效果。

```
    keybb="lalt"		
    LSKG = 1
```


