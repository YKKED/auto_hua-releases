# auto_hua · 小花仙安卓脚本

适用于 MuMu 安卓 12 的 Windows 便携应用。

## 下载与运行

1. 下载 [最新便携版](https://github.com/YKKED/auto_hua-releases/releases/latest/download/auto_hua-portable.zip)。
2. 完整解压，运行 `auto_hua.exe`。
3. 更新已有程序时，保留原来的 `data` 文件夹，其中保存配置和历史记录。

## 运行要求

- Windows 10/11，64 位系统。
- MuMu 安卓 12，安装安卓《小花仙》。
- 模拟器分辨率设置为 **1280×720**。

便携版已包含 Python、识别模型、ADB 和所需运行库，无需单独安装这些依赖。

## 自动更新

程序会自动检查并下载更新。下载内容通过数字签名和 SHA256 校验，等待当前任务结束后安装并重启，保留配置与历史记录。安装验证失败时恢复旧版本；更新后需手动启动任务。

## 发布文件

| 文件 | 用途 |
| --- | --- |
| `auto_hua-portable.zip` | 便携应用 |
| `latest.json` | 版本、下载地址和更新说明 |
| `latest.sig` | 更新清单的数字签名 |

此仓库用于发布程序与更新资料，不包含用户数据或签名私钥。
