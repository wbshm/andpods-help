---
title: 耳机-说明
date: 2022-05-12 17:55:20
tags:
---

## 耳机 - 界面
{% asset_img erji.jpg 240 503.72 image %}


### 切换耳机
> 绑定多个耳机的，可以手动切换当前耳机

### 更多功能
* 添加耳机：配对新的耳机型号
* 修改名称：通过系统的蓝牙设置重命名耳机名称
* 移除耳机：可以移除已经配对的耳机，移除后需要重新配对才能继续使用软件的功能

### 耳机型号
* 智能识别型号
    * 推荐使用自动识别耳机型号
    * 不同耳机型号支持的功能不一样，耳机型号选错可能会无法显示电量

* 手动更换型号
    * 如果确定当前的耳机型号。可以手动选择

{% asset_img xinghao.jpg 240 503.72 image %}


### 自动弹窗
{% asset_img tc.jpg 240 503.72 image %}
* 连接自动弹窗
    > 开启该功能后，每当耳机与手机自动连接成功时会弹窗提示
* 弹窗停留时长
    > 设置弹出的窗口停留的时间
* 锁屏状态下弹窗
    > 可以开关，在锁屏状态下，是否进行弹窗显示
* 横屏状态下弹窗
    > 可以开关，在横屏状态下，是否进行弹窗显示
    > 建议玩游戏的用户可以关闭横屏弹窗，避免影响游戏体验

### 入耳检测
* 戴上和摘下耳机都会自动触发对应的功能（播放/暂停）
* 由于硬件不兼容的问题，入耳检查会有2~5s左右的延迟，目前还没有很好的解决方案
* 常见问题：[无法入耳检查](/2020/07/09/normal/#入耳检测失效)

### 音频控制
* 通过有规律触摸耳机触发对应的功能。
* 触摸位置
{% asset_img chumoweizhi.jpg 240 279.57 image %}
* 轻点两下: 连续触摸指定的位置两下触发功能（播放/暂停，上一首，下一首，语音助手）
* 轻点四下: 连续触摸指定的位置四下触发功能（播放/暂停，上一首，下一首，语音助手）


### 按键替换
* 设置压感控制，可以将默认功能替换为语音唤醒

### 左右电量互换（限华强北）
* 华强北的蓝牙协议和正版的有区别，有可能会出现左右耳电量互换的情况
* 如果左右耳互换，可以通过开启设置，调整组成正常显示

### 查找定位
* 应用会记录最近一次使用耳机的地理位置，以协助您寻找耳机
* 如果耳机就在附近，可以尝试连接耳机并播放声音来协助定位耳机
* 如果值丢失一直耳机，可以尝试关闭左声道/右声道来辅助确认
{% asset_img chazhaoerji.jpg 240 503.72 image %}

#### 附近耳机
> 该功能使用蓝牙信号测距实现
    
* 在使用中需要注意一下几点：
    * 由于蓝牙信号的强度和穿透能力的限制，距离可能限制在10米范围内，并且容易受到环境干扰
    * 耳机需要处于使用中：取出耳机，并且耳机有电量的情况下才会有蓝牙信号发出
* 怎么使用：
    * 列表中显示附近符合条件的耳机，您可以选择追踪您的耳机
    * 在耳机距离远的情况下可以通过走动来靠近耳机
    * 如果耳机有配对过了，可以再靠近耳机的时候尝试连接耳机播放声音，来帮助您确定耳机位置
{% asset_img fujinerji.jpg 240 503.72 image %}
#### 特别说明：
* 播放声音会将声音调整到最大，并进行播放，请勿在佩戴时进行播放操作
* 因为涉及到用户的敏感的隐私信息（地理位置），所以我们没有将数据上传到云端。数据只存在本地。（重装应用、更换设备等操作，都会导致数据遗失）

### 后台常驻设置
> 这个是应用稳定运行的必要设置
* 系统可能会清理掉应用后台，导致弹窗、电量显示等应用功能失效，可以进行相应设置避免系统杀后台
* [后台常驻方案](/2020/12/22/normal-permanent/#后台常驻设置)