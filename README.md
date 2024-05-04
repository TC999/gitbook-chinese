# [GitBook 汉化插件][project-url]
 本项目修改自 [maboloshi/github-chinese](https://github.com/maboloshi/github-chinese)

## 🚩 功能

- 汉化 GitBook 菜单栏，标题，按钮等公共组件
- 保留、完善正则功能

## 🌐 浏览器与脚本管理器

浏览器                              | 脚本管理器
:---------------------------------: | :---------: 
Chrome 或 基于 Chromium 内核的浏览器| [Tampermonkey](Tampermonkey.net),[Violentmonkey](https://violentmonkey.github.io/)
Safari 浏览器                       | 未测试
Firefox 或基于 Gecko 的浏览器                      | [Tampermonkey](Tampermonkey.net)

## 💽 安装
1. 请先安装用户脚本管理器。
1. 然后再点击链接之一，安装脚本即可。
1. 刷新下页面，即可发现网站已中文化。

## 词库本地调试方法
1. 需要安装插件管理器[Tampermonkey][Tampermonkey]，其他可能不支持。
1. 在浏览器插件管理中，开启[Tampermonkey][Tampermonkey]的 “允许访问文件网址” 如图：

    <picture>
      <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/maboloshi/github-chinese/gh-pages/preview/允许访问文件网址-light.png"/>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/maboloshi/github-chinese/gh-pages/preview/允许访问文件网址-dark.png"/>
      <img src="https://raw.githubusercontent.com/maboloshi/github-chinese/gh-pages/preview/允许访问文件网址-light.png" width="75%" />
    </picture>

1. 将修改的词库文件放到方便访问的本地位置。
1. 安装[GitHub 中文化插件 - GitHub 托管【开发版】（相对及时更新）][main.user.js]，实际[GitHub 中文化插件 - GreasyFork 托管【发布版】（仅大版本更新）][main(greasyfork).user.js]也可。
1. 回到插件管理器，修改词库文件路径，即类似`// @require      https://raw.githubusercontent.com/maboloshi/github-chinese/gh-pages/locals.js?v1.9.0`
   中网址改成本地路径格式如`file:///D:/APP/github%E9%A1%B9%E7%9B%AE/github-chinese/locals.js`。

  > [!TIP]
  > 直接将词库文件拖到浏览器的地址栏，再复制地址栏的中地址即可。

## ✔ 待办 (TODO)
**本人英文渣渣，翻译非常困难，急需大家 PR 共同翻译**