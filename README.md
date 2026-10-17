# PmRange Windows 发行下载

本仓库只保存发行说明与 **Cython + Nuitka 编译保护后的 Windows x64 ZIP**，不包含私有源码、算法源码或签发密钥。

进入 [正式发行页面](https://github.com/JoeyDL001/PmRange-Releases/releases/latest)，下载 `PmRange-Windows-x64-vX.Y.Z.zip`，完整解压后打开 `PmRange/PmRange.exe`。无需安装 Python，请保留全部随包文件。

企业永久使用版免激活、无用户账户，业务功能可离线使用。自动检查更新默认关闭，可在“应用设置 → 软件更新”明确启用；也可从“帮助 → 检查更新”主动检查。

更新检查仅查询本仓库公开发行信息，不上传图件、坐标、项目路径、设备码或身份信息。更新提示只提供系统浏览器入口，不自动覆盖 EXE/DLL，也不执行下载的文件。

每个正式版本附带 ZIP、`.zip.sha256` 与发行清单。可在 PowerShell 中运行 `Get-FileHash -Algorithm SHA256 文件名.zip`，与校验文件核对。

DWG 支持使用用户本机配置的 ODA 转换器，ODA 是独立第三方软件。

PmRange 为闭源软件；本发行仓库公开不代表软件源码或算法获得开源许可。
