# 本仓库是我整理收集的一些 **VirtualDJ Device Pack**

## 📦 安装说明

**① 查找设备**

在仓库中找到与你的设备型号对应的文件夹，每个设备文件夹内通常包含 **xxx.xml xxx mapping.xml xxx.png xxx Screen.zip** 等文件。

**② 下载文件**

完整下载所需的设备文件夹，**保留原始文件夹名称及内部文件名称**，请勿重命名或单独提取文件。

**③ 放置文件**

根据你使用的 VirtualDJ 版本，找到对应的数据目录

2023之前的版本，通常在  C:\Users\用户名\Documents\VirtualDJ

2023之后的版本，通常在  C:\Users\用户名\AppData\Local\VirtualDJ

将下载的整个设备文件夹内的文件 **除去xxx Screen.zip** 全选后压缩为zip文件，**压缩后的文件名应为对应文件夹名，打开后根目录就是各xml文件**，随后放入 `Devices` 文件夹中。

如有为屏幕的设备，将文件夹中的 **xxx Screen.zip** 放入 `Skins` 文件夹中。

打开VirtualDJ即可使用。

## 📁 文件夹结构示例

**仓库中的设备文件夹：**

```text
VirtualDJ-Device-Pack/
├── Pioneer-DDJ-XXX/
│   ├── xxx.xml
│   ├── xxx mapping.xml
│   └── xxx.png
│   └── xxx Screen.zip
│
├── Numark-XXX/
│   ├── xxx.xml
│   ├── 文件 2
│   └── 文件 3
│
└── Denon-XXX/
    ├── 文件 1
    ├── 文件 2
    └── 文件 3
```

**安装到 VirtualDJ 后：**

```text
VirtualDJ/
└── Devices/
    └── Pioneer-DDJ-XXX.zip
└── Skins/
    └── Pioneer-DDJ-XXX Screen.zip
```
