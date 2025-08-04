<p align="center">
  <img src="./assets/logo.svg" alt="Logo">
</p>

一个在线的微信公众号文章批量下载工具，支持下载阅读量与评论数据，无需搭建任何环境，HTML 格式可100%还原文章样式，支持私有化部署，可在 Windows/macOS/Linux 系统上使用。


## 文档

[文档站点](https://docs.wxdown.online) 上线啦 🎉🎉🎉，后续使用教程会在此站点统一进行维护。


## :dart: 特性

- [x] 搜索公众号，支持关键字和biz搜索
- [x] 搜索公众号内文章(根据文章标题搜索)
- [x] 支持导出 html/json/excel/txt 格式(html 格式打包了图片和样式文件，能够保证100%还原文章样式)
- [x] 缓存文章列表数据，减少接口请求次数 (关键字搜索的文章不会进入缓存)
- [x] 支持文章过滤，包括作者、标题、发布时间、原创标识、所属合集等
- [x] 支持合集下载
- [x] 支持图片分享消息
- [x] 支持视频分享消息

## :heart: 感谢

- 感谢 [Deno Deploy]、[Cloudflare Workers] 提供免费托管服务
- 感谢 [WeChat_Article] 项目提供原理思路


## :bulb: 原理

在公众号后台写文章时支持搜索其他公众号的文章功能，以此来实现抓取指定公众号所有文章的目的。


## :memo: 许可

MIT


## :star: Star 历史

[![Star History Chart]][Star History Chart Link]



<!-- Definitions -->

[deploy-badge]: https://img.shields.io/github/actions/workflow/status/jooooock/wechat-article-exporter/.github%2Fworkflows%2Fdeno_deploy.yml?label=Deploy

[deploy]: https://github.com/jooooock/wechat-article-exporter/actions

[Github stars]: https://img.shields.io/github/stars/jooooock/wechat-article-exporter?style=social&label=Star&style=plastic

[Github forks]: https://img.shields.io/github/forks/jooooock/wechat-article-exporter?style=social&label=Fork&style=plastic

[Github License]: https://img.shields.io/github/license/jooooock/wechat-article-exporter?label=License

[微信公众平台]: https://mp.weixin.qq.com/cgi-bin/registermidpage?action=index&lang=zh_CN

[登录页面]: https://wechat-article-exporter.deno.dev/login

[切换账号]: assets/switch-account.png

[Deno Deploy]: https://deno.com/deploy

[Cloudflare Workers]: https://workers.cloudflare.com

[Wechat_Article]: https://github.com/1061700625/WeChat_Article

[Star History Chart]: https://api.star-history.com/svg?repos=jooooock/wechat-article-exporter&type=Timeline

[Star History Chart Link]: https://star-history.com/#jooooock/wechat-article-exporter&Timeline
