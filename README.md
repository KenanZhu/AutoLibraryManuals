# AutoLibrary 用户手册

AutoLibrary 北京建筑大学图书馆自动化工具的 Mintlify 文档站点。

## 开发

安装 [Mintlify CLI](https://www.npmjs.com/package/mint) 以在本地预览文档更改：

```
npm i -g mint
```

在 `docs.json` 所在目录运行：

```
mint dev
```

在 `http://localhost:3000` 查看本地预览。

## 发布

更改推送到默认分支后将自动部署到生产环境。

## 文档结构

```
├── docs.json          # Mintlify 配置与导航
├── index.mdx          # 首页
├── versions/          # 版本手册
│   ├── v1.3.0.mdx
│   ├── v1.2.1.mdx
│   ├── ...
│   └── v0.0.3-alpha.mdx
├── autoscript.mdx     # AutoScript 语法参考
├── logo/              # Logo 资源
└── images/            # 图片资源
```
