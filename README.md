# Android x86 Arm NativeBridge (libhoudini)
从ChromeOS r110提取的libhoudini,适用于Android 11的各种x86系统...

```
waydroid_x86_64 / # houdini --version
[7491] 
[7491] Houdini version: 11.0.1f_y.38795.g
[7491] 
waydroid_x86_64 / # houdini64 --version
[7492] 
[7492] Houdini version: 11.0.1f_z.38795.g
[7492] 
```

话说这东西真的只能从各大公司编译出的成品里扒拉吗？

#### 安装方式
替换入system镜像的各种方法均可，包括但不限于重新打包镜像、Magisk、overlay文件系统（如waydroid的lxc容器）、gearlock等。
