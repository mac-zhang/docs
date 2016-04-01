# Prometheus Documentation

这个库包含prometheus站点的内容和静态站点生成器代码.

## Prerequisites

You need to have a working Ruby environment set up and then install the
necessary gems:
你需要有一个ruby的工作环境，并且安装网站运行必须的gems包。

```首先进入代码目录（命令行）
cd docs
bundle
```

## 编译

生成静态站资源, 执行:

```bash
bundle exec nanoc
```

生成的静态文件资源会被存储在 `output` 这个目录下.

## Development Server

在本地运行生成的网站，执行:

```bash
# Rebuild the site whenever relevant files change:
bundle exec guard
# Start the local development server:
bundle exec nanoc view
```

现在，你可以通过[http://localhost:3000/](http://localhost:3000)访问你生成的网站了.

## License

Apache License 2.0, see [LICENSE](LICENSE).
