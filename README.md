# IDM激活脚本（汉化版）

这是一个汉化版的IDM激活脚本，用于激活和重置 [Internet Download Manager](https://www.internetdownloadmanager.com/) 的试用版。本脚本参考了 [https://github.com/lstprjct/IDM-Activation-Script](https://github.com/lstprjct/IDM-Activation-Script) 的代码并进行了汉化处理。

## 特性
- **IDM冻结试用和激活**：通过注册表键锁定方法实现。
- **激活和试用持久化**：即使安装IDM更新，激活和试用状态仍然保留。
- **IDM试用重置**：可以随时重置IDM的激活和试用状态。
- **完全开源**：基于透明的批处理脚本。

## 文件格式
- 编码      GB2312
- 行尾      CRLF
- 文件名    IDM激活汉化版.cmd
- **如果下载的cmd文件无法运行，请使用Visual Studio Code 或 Notepad++ 修改文件编码和行尾**

## 详细信息
- 此脚本通过注册表锁定方法激活Internet Download Manager（IDM）。
- 激活时需要联网。
- 可以直接安装IDM更新，无需再次激活。
- 激活后，如果IDM显示激活提示屏幕，只需再次运行激活选项，无需使用重置选项。

### 冻结试用
- IDM提供30天的试用期，你可以使用此选项将试用期永久锁定，无需再次重置试用，试用期也不会过期。
- 应用此选项时需要联网。
- 可以直接安装IDM更新，无需再次冻结试用期。

### 重置IDM激活/试用
- Internet Download Manager提供30天的试用期，你可以使用此脚本来重置激活/试用期限。
- 此选项还可用于恢复IDM报告虚假序列号等类似错误的状态。

## 常见问题解答
### 激活失败怎么办？
如果激活失败或IDM显示虚假序列号提示屏幕，建议使用“冻结试用”选项。

### 遇到其他问题怎么办？
请查看 [帮助页面](https://github.com/lstprjct/IDM-Activation-Script/wiki/IAS-Help#troubleshoot) 以获取更多帮助。

## 屏幕截图
![IDM 激活脚本](https://raw.githubusercontent.com/jarocheng0123/IDM-CN/refs/heads/main/png/1.png)
![激活选项](https://raw.githubusercontent.com/jarocheng0123/IDM-CN/refs/heads/main/png/2.png)
![激活完成](https://raw.githubusercontent.com/jarocheng0123/IDM-CN/refs/heads/main/png/3.png)