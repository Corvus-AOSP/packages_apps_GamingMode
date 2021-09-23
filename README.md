# GamingMode

exTHmUI 游戏模式 (Game mode)

## 性能调节器说明 (Performance Tuner Description)
当进入游戏模式或者用户调节 (When entering game mode or user adjustment) SeekBar 时 (Time), 游戏模式会设置 (Game mode will be set with) `sys.performance.level` This attribute.\
设备维护者需要在代码中添加对这个属性变化的监听 (The device maintainer needs to add monitoring for this attribute change in the code).
可以参考 (Can refer to) [这个(this) commit](https://github.com/exthmui-devices/android_device_xiaomi_raphael/commit/78ecd4bde0ee80e35cbfa21262e3399b59d44899)

### 属性值说明 (Property value description)
- 0-6 : 数值越大性能越高 (The higher the value, the higher the performance)
-  -1 : 恢复默认性能 (Restore default performance)

## 使用的第三方组件 (Third-party components used)
- [EasyDanmaku](https://github.com/LittleFogCat/EasyDanmaku)
