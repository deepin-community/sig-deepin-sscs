---
title: "deepin通用软件包标识化工具发布"
date: 2024-09-09T16:33:20+08:00
draft: false
authors: ["gglinxiao"]
tags: ["成果公示"]
---
deepin universal package identification tool

package-sbom-tool用于针对通用软件包生成符合SPDX标准的SBOM信息。 它是一个命令行工具，工具所采集的软件包信息包括了文件组成、依赖信息、版权、许可证。 工具产生的SBOM信息符合SPDX v2.3规范。

<!--more-->
项目的主要功能或特性：

支持DEB包元信息解析、文件指纹生成、版权、许可证提取
支持包信息SPDX json格式输出
支持对软件包生成唯一标识。
支持对sbom文件进行签名，生成签名文件。
支持对sbom文件签名信息进行验证，保证真实性和完整性。
......
支持的通用软件包格式
DEB
RPM (todo)
Snap (todo)
Flatpak (todo)
Appimage (todo)


仓库地址： https://github.com/linuxdeepin/deepin-sbom-tools