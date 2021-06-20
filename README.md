# Daily-Words

Daily Words Project 秉持自由软件和开源的价值观

## 项目的组成

- 服务端
    服务端可选择本项目的官方服务，或自行编译运行在自己的服务器上。
    - 【未实现】[ASP.NET core 服务端](https://github.com/Daily-Words/Daily-Words-.NET)
    - 【未实现】[PHP 服务端](https://github.com/Daily-Words/Server-php)
- 客户端
    客户端可选择官方提供的编译版本，或自行编译。依赖于服务端的客户端版本的编译，不依赖于服务端的实现，在客户端内支持动态配置运行选项。
    - 【未实现】[WPF Windows 客户端源代码](https://github.com/Daily-Words/Daily-Words-.NET)
        - 支持依赖服务器或本地运行
    - 【未实现】[Xamarin Windows 客户端源代码](https://github.com/Daily-Words/Daily-Words-.NET)
        - 支持依赖服务器或本地运行
    - 【未实现】[HTML 客户端源代码](https://github.com/Daily-Words/Client-Web)
        - 仅支持依赖服务器运行
- 项目的标准
    - [开发标准](Dev-Docs.md)
    - [UI 标准](UI-Docs.md)
    - [API 标准](API-Docs.md)
    - [Data 标准](Data-Docs.md)

## 服务端可选

在以下描述中，“本项目”代表我们提供的服务，包括服务器 API 和客户端的编译版本；“本项目实现”代表我们开放的源代码和您自己编译架设的版本。

根据情况，您可以选择以下组合：

- 使用官方服务
    - 服务端：本项目的服务器
    - 客户端
        - 本项目或本项目实现的 Web 页面
        - 本项目或本项目实现的 Windows 客户端
        - 本项目或本项目实现的 Xamarin 客户端
        - 依据本项目规范的第三方代码客户端
- 自建服务端
    - 服务端
        - 本项目实现的 ASP.NET core 服务端
        - 本项目实现的 PHP 服务端
        - 依据本项目规范的第三方代码服务端
    - 客户端
        - 本项目实现的 Web 页面
        - 本项目或本项目实现的 Windows 客户端
        - 本项目或本项目实现的 Xamarin 客户端
        - 依据本项目规范的第三方代码客户端
- 本地版本
    - 本项目或本项目实现的 Windows 客户端
    - 本项目或本项目实现的 Xamarin 客户端

## 智能算法

- 添加词库
- 新词
- 复习词