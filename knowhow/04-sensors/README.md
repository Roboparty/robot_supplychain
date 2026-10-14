# 传感器

**大类：** 力、触、惯导、视觉。接口协议和标定流程比「分辨率参数」更容易误事。

关节里的编码器见 [关节模组 / 编码器](../01-joint-modules/encoder/README.md)，不在本大类重复当主文档。

## 小类

| 小类 | 干什么 | 入口 |
|---|---|---|
| 力 / 力矩 | 足底、关节、腕部六维力 | [force-torque.md](./force-torque.md) |
| 触觉 | 指面、接触检测 | [tactile.md](./tactile.md) |
| IMU | 躯干姿态、角速度 | [imu.md](./imu.md) |
| 视觉 | 相机、深度、线激光 | [vision.md](./vision.md) |
