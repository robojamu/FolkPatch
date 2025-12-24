<div align="center">
<h1 align="center">FreePatch Manager</h1>

[![GitHub License](https://img.shields.io/github/license/bmax121/APatch?logo=gnu)](/LICENSE)

</div>

**语言 / Language:** [中文](README.md)

**FreePatch(FolkPatch-spoof)** 是基于 [APatch](https://github.com/bmax121/APatch) 和 [FolkPatch](https://github.com/matsuzaka-yuki/FolkPatch) 的自定义包名分支，不对核心内容进行任何修改

## 主要特性

- 基于内核的Android设备Root解决方案
- APM：支持类似Magisk的模块系统.支持批量刷入,更加快捷
- KPM：支持将任何代码注入内核的模块（提供内核函数`inline-hook`和`syscall-table-hook`）
- 移除了自动更新功能，提供更稳定的用户体验
- 更好的自定义系统,支持自定义壁纸
- 全自动的KPM加载机制,无需嵌入到Boot
- 模块全量备份,只管安心的体验Root
- 多种特色语言,随心切换
- 模块全局排除,更加快速
- 在线模块下载功能


## 系统要求

- 支持ARM64架构
- 支持Android内核版本 3.18 - 6.12

## 开源信息

本项目基于以下开源项目：

- [KernelPatch](https://github.com/bmax121/KernelPatch/) - 核心组件
- [Magisk](https://github.com/topjohnwu/Magisk) - magiskboot和magiskpolicy
- [KernelSU](https://github.com/tiann/KernelSU) - 应用UI和类似Magisk的模块支持
- [Sukisu-Ultra](https://github.com/SukiSU-Ultra/SukiSU-Ultra) - 参考一些界面的设计
- [APatch](https://github.com/bmax121/APatch) - 上游分支
- [FolkPatch](https://github.com/matsuzaka-yuki/FolkPatch) - 上游分支

## 许可证

FreePatch 遵循 GNU General Public License v3 [GPL-3](http://www.gnu.org/copyleft/gpl.html) 许可证开源。

## APatch社区

频道地址: [@APatch](https://t.me/apatch_discuss)

FreePatch 的问题和建议请在ISSUE中提出,不要给官方频道造成困扰。