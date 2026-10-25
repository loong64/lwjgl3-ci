# LWJGL Linux dependency CI

以 [LWJGL 发布目录](https://www.lwjgl.org/browse/stable/linux/x64) 中实际使用的外部依赖为范围，
保留各项目上游 Linux 构建命令，通过统一入口按指定 LWJGL 发行快照选择依赖，并使用各源码仓库的默认分支构建。
编译命令直接位于各项目 YAML 中，没有独立编译 shell 脚本。
