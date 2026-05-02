<div align="center">

# OPCameraPro 相机功能补全

<a href="https://github.com/Xposed-Modules-Repo/com.tlsu.opluscamerapro/releases/"><img alt="Github Releases" src="https://img.shields.io/github/v/release/Xposed-Modules-Repo/com.tlsu.opluscamerapro"><a href="https://github.com/Xposed-Modules-Repo/com.tlsu.opluscamerapro/releases"><img alt="GitHub all releases" src="https://img.shields.io/github/downloads/Xposed-Modules-Repo/com.tlsu.opluscamerapro/total?label=Downloads"></a> <a href="https://github.com/Xposed-Modules-Repo/com.tlsu.opluscamerapro/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/Xposed-Modules-Repo/com.tlsu.opluscamerapro"></a>
<a href="http://t.me/+awg-7X5Ggrs5NzZl"><img alt="Telegram" src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white"></a>
</div>

### 简要介绍：
- 这是一个适用于 ColorOS 的相机/相册增强型 Xposed 模块，推荐 ColorOS 16 / realmeUI 7.0，C15仅做简单兼容，未来版本将彻底舍弃。
- App是一个第三方的功能模块，使用该模块App造成的任何后果作者均不会负责。

### 必要说明
- **需要 Root 权限以及 LSPosed v2.0+ 激活方可使用**，老版本 LSPosed 不再兼容
- 建议使用 KernelSU LKM + Mountify / Hybrid Mount 元模块进行挂载
（由于 Mountify / Hybrid Mount 元模块的模块目录要求不同，切换元模块后需要重新安装附属模块）
- **Root 管理器-超级用户-相机、相册的 App Profile 请务必取消掉「默认卸载模块」**
- Bug Report 请通过模块内的**日志中心**导出日志包，如遇闪退可使用「复现闪退并收集日志」功能一键采集
- 模块App请时刻保持在最新版，旧版本不会受到任何的支持
- 推荐相机版本：[6.0.31.72（新UI版本）](https://gitee.com/bugme7/OPCameraPro/releases/download/CameraApp/%E7%9B%B8%E6%9C%BA_6.031.72.zip)，安装新UI相机后需安装附属模块，并且严格按照上面的环境要求操作，否则无法正常拍照


### 开放源代码
- https://github.com/Weverses/OPCameraPro
### 下载与支持
- Github Releases: https://github.com/Xposed-Modules-Repo/com.tlsu.opluscamerapro/releases/
- Xposed Modules Repo: https://modules.lsposed.org/module/com.tlsu.opluscamerapro
- Telegram (Recommend): http://t.me/+awg-7X5Ggrs5NzZl



### 功能介绍
- 注意：以下的功能为总览，不代表你的机型一定可以开启、使用以下功能
- 模块会自动根据机型、版本、底层能力、环境状态来大致判断功能是否可用并显示开关（不一定准确）
#### 相机功能

**直出照片与画质**
- 直出 25MP 照片
- 10bit 照片
- HEIF模式编辑背景虚化
- 全链路 ProXDR
- 大师/专业/高像素模式 ProXDR（UltraHDR）
- HEIF Ultra HDR 重封装（通用 Android Gainmap 格式，可跨设备分享 HDR 效果）
- 哈苏超清及 4K 超清实况照片
- 自定义机型水印名称
- 扩展 ISO 上下限
- AI 构图大师
- 点击变焦切换焦距

**大师模式**
- 新版大师模式
- 大师模式放大对焦
- 大师模式滤镜与参数预设
- 大师模式预设
- 大师模式导入、编辑预设
- 大师模式滤镜角标
- 大师模式预设信息水印

**人像与变焦**
- 人像模式变焦
- 前置拍照变焦
- 人像模式后置闪光灯
- 人像镜头包
- AI 超清望远算法
- 超清长焦算法

**视频与音频**
- 前置4K视频
- 720P 60FPS视频
- 4K 120FPS 视频
- 1080P 120FPS 视频
- 视频自动帧率
- 视频录制锁定镜头
- 视频录制锁定白平衡
- 视频录制检测麦克风状态
- 录制结束立即播放提示音
- 声音聚焦
- 去除只能在 1080P 30FPS 下使用滤镜限制

**实况照片**
- 实况照片
- 大师模式实况
- 实况视频高码率
- 实况照片时长

**微距**
- 新版微距模式
- 微距模式调用长焦
- 微距景深融合

**滤镜**
- LUT 导入为相机滤镜
  - 支持 33 位 LUT 导入后转换为相机滤镜，自由排序应用到不同模式
  - 支持复制滤镜，使用原图和套滤镜后的图分析出滤镜，可用于导入其他系统、摄影软件的滤镜
  - 支持滤镜仓库，用户可自由上传和下载滤镜并导入
- 自定义滤镜排序，自由组合70+个滤镜
- 大师滤镜
- GR 滤镜
- 光影有声滤镜
- 旅行系列滤镜
- 沙漠系列滤镜
- Vignette Grain滤镜
- 姜文滤镜
- 贾樟柯滤镜
- Meishe系列滤镜
- Claudio Miranda 系列滤镜
- 权力的游戏系列滤镜
- 800T 胶片霓虹滤镜
- CCD 闪光滤镜
- 和光 / 浓郁 / 反差黑白滤镜
- 柔光滤镜
- 80s美式复古、街拍、光影、新潮复古、北欧冷调、小城大事、银白极境、戏剧、黑金、黄蓝、粉青、夜之城、柔和

**水印**
- 哈苏界面与水印
- 哈苏水印默认开启
- GR 水印
- LUMO
- 新版 XPAN

**其他**
- 新版美颜菜单
- 超级文本扫描
- 双击音量键快捷启动相机
- 运动模式
- 无影抓拍
- EV 调节功能
- 光场设计 UI
- 支持磁吸闪光灯
- 水下相机模式
- 相机 Debug 模式

#### 相册功能
- AI 灵感成片
- AI 消除
- AI 实况消除
- AI 去拖影
- AI 画质增强
- AI 去反光
- AI 最佳表情
- AI 人像补光
- 实况照片更换封面 ProXDR
- LUMO 凝光水印
- 自定义水印样式编辑器（支持自由编辑水印中的图片、文字等元素）


### 模块功能介绍

- App的附属模块功能：对于部分功能，需要安装附属模块才能正常启用，安装附属模块的方法是打开模块设置->安装附属模块

- App的安全模式功能：如果遇到了开启某个开关但是记不起来了，相机、相册App又不断闪退，或安装附属模块后遇到了问题，请使用安全模式来一键停用所有Hook并清理数据缓存，回归未修改状态。
