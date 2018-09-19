# Learn F#

- F# 指南：https://docs.microsoft.com/zh-cn/dotnet/fsharp/


## F#入门

#### Step.1 安装F#环境
F# + Visual Studio Code + Git + GitHub
- Visual Studio Community
    - 单个组件
        - F# 桌面语言支持
- Visual Studio Code
    - Ionide-fsharp
- .NET Core SDK
- Git

都官网下载，都装好记得重启

#### Step.2 创建F#示例
View - Command Palette（Ctrl+Shift+P）
- >F# new project
- >classlib
- >C:\Users\饼干\OneDrive\饼干的代码\LearnF#\HelloWorld
- >ClassLibraryDemo

#### Step.3 文件结构
- .paket：目录结构
    - paket.bootstrapper.exe
    - paket.exe：可提取包
    - Paket.Restore.targets
    - Paket.targets
- 01-ClassLibraryDemo
    - obj
    - 01-ClassLibraryDemo.fs：实现文件和定义的类
    - 01-ClassLibraryDemo.fsproj：用于生成项目的文件
    - paket.references：特定项目的依赖文件
    - Script.fsx：加载资源文件的脚本
- packages
- paket-files
- .gitignore：Git的源代码管理
- build.cmd
- build.fsx
- build.sh
- paket.dependencies
- paket.lock
