# buildQt 从源代码自动构建Qt

## 说明
1. 本项目的主要目的是从源代码构建Qt的二进制版本(使用GithubActions自动构建)
2. 主要针对开源版本的Qt5、Qt6版本
3. 主要构建`Windows版本`(使用`MSVC`)

## 各分支说明
| 分支 | static/shared | debug/release | 备注|
| :----- | :----- | :----- | :-----|
| main | static | debug-and-release | 主要构建64位版本|
| shared-release | shared | release | 主要构建64位版本|
| shared-debug | shared | debug | 主要构建64位版本|
| shared-debug-and-release | shared | debug-and-release | 主要构建64位版本|

## 版本
1. 无"RP"版本：从Qt完整源代码构建，构建绝大部分组件
2. 有"RP"版本：从Qt组件源代码构建，目前只构建qtbase、qttools、qttranslations、qtsvg共4个组件

## 参考仓库
1. Github: https://github.com/yuanpeirong/buildQt
