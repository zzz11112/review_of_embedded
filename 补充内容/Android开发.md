# Android/鸿蒙开发

### 1. Android应用程序构成

1. 活动(Activity)
2. 意图(Intent)
3. 服务(Service)
4. 内容提供器(Content Provider)

### 2. 生命周期

* 指一个 Android 组件（如 Activity、Fragment、Service 等）从创建到销毁的整个过程
* 六个核心回调
  * onCreate()
  * onStart()
  * onResume()
  * onPause()
  * onStop()
  * onDestroy()

### 3. 开发坏境

1. Eclipse开发坏境+ADT插件
   * Java+AndroidSDK
2. Android Studio

### 4. 鸿蒙应用开发

1. 基本开发流程
   * 准备开发环境->ABILITY开发->UI开发->业务功能开发->应用调试及发布
2. Ability
   * 应用所具备的能力的抽象，也应用程序重要组成部分
   * 一个应用可包含多个Ability
   * 分类
     * FA:Feature Ability,UI界面
     * PA:Particle Ability，其他Ability调用自定义服务，如视频采集等功能
3. 技术特性
   * 硬件互助，资源共享
     * 分布式设备虚拟化
     * 分布式数据管理
     * 分布式任务调度
   * 一次开发，多端部署
   * 统一OS，弹性部署
