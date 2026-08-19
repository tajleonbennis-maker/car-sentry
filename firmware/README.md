# firmware

ESP32 固件（Arduino / PlatformIO 工程），开发中。

计划功能：
- deep sleep + GPIO 外部唤醒（雷达 OUT → GPIO13）
- 唤醒后初始化摄像头，连拍 2-3 张存 SD
- 可选：4G Cat.1 上传 + 微信推送
- 冷却时间、触发延时、光敏联动

参考接线见 ../docs/wiring.md
