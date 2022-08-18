简体中文 | [English](./README_EN.md)

<p>
<strong><h2>松子分享の主页</h2></strong>
简单的小主页，原来的看够了，重新弄了一个
</p>

![松子分享の主页](https://s1.ax1x.com/2022/08/18/vrlM2d.jpg)

### Demo

>由于 CDN 缓存原因，查看最新效果可能需要 `Ctrl` + `F5` 强制刷新浏览器缓存

- [松子分享の主页](https://szfx.top/home/)

### 功能

- [x] 载入动画
- [x] 站点简介
- [x] Hitokoto 一言
- [x] 日期及时间
- [x] 实时天气
- [x] 时光进度条
- [x] 音乐播放器
- [x] 移动端适配

* [ ] 去除 jQuery 依赖
* [ ] VUE 重构

### 天气

由于原天气 API 不稳定，已更换天气 API，现需要前往以下网站获取 key

- 前往 [ROLL](https://www.mxnzp.com/doc/list) 获取 app_id 和 app_secret，用于获取城市信息

也可自行更换其他方式

<!-- ### 配置

本项目采用 `json` 文件来配置站点内容，该配置不受版本更新影响，可将自定义配置写入 `setting.json` 以更改页面内容

<details>
<summary>配置说明</summary>

```json
{
    "title": "网页标题",
    "description": "网页简短介绍",
    "keywords": "网页关键词",
    "author": "网页作者",
    "logo_img": "Logo图片路径",
    "logo_text_1": "域名前缀",
    "logo_text_2": "域名后缀",
    "des_title": [
        "Hello World !", //站点介绍标题
        "一个建立于 21 世纪的小站，存活于互联网的边缘" //站点介绍内容
    ],
    "des_title_change": [
        "Oops !", //站点介绍标题点击后文字
        "哎呀，这都被你发现了 ( 再点击一次可关闭 )" //站点介绍内容点击后文字
    ],
    "github": "", //Github 用户名
    "qq": "", //QQ
    "email": "p", //Email电子邮件
    "bilibili": "", //bilibili 用户名
    "link_1": [
        "https://blog.szfx.top/", //链接地址
        "fa-solid fa-blog", //图标类名
        "博客" //链接文字
    ],
    "link_2": [
        "https://cloud.jishusongshu.com/",
        "fa-solid fa-cloud",
        "网盘"
    ],
    "wallpaper_api": [
        [
            "每日一图", //壁纸设置项名称
            "https://api.szfx.top/bing/api" //壁纸图片链接
        ]
    ],
    "Copyright_year": "2020", //站点起始年份
    "Copyright_text": "松子分享" //版权
}
```

</details> -->

### 音乐

>本项目采用了基于 `MetingJS` 的 `Aplayer` 音乐播放器，可实现快速自定义歌单  
>*仅支持 **中国大陆地区**，其他区域请将 [以下内容](https://cdn.jsdelivr.net/gh/imsyy/file/js/music/music-other.js) 替换 `music.js` 以实现音乐播放器的正常使用

更改 `music.js` 的参数即可实现自定义歌单列表

```js
let server = "netease"; //netease: 网易云音乐; tencent: QQ音乐; kugou: 酷狗音乐; xiami: 虾米; kuwo: 酷我
let type = "playlist"; //song: 单曲; playlist: 歌单; album: 唱片
let id = "7452421335"; //封面 ID / 单曲 ID / 歌单 ID
```

### 插件

* [Bootstrap](https://getbootstrap.com/)
* [iziToast](https://izitoast.marcelodolza.com/)
* [Font Awesome](https://fontawesome.com/)
* [jQuery](https://jquery.com/)
* [Aplayer](https://aplayer.js.org/)

### API

* [MetingAPI By 武恩赐](https://api.wuenci.com/meting/api/)
* [小歪 API](https://api.ixiaowai.cn/)
* [和风天气](https://dev.qweather.com/)
* [ROLL](https://www.mxnzp.com/doc/list)
* [Hitokoto 一言](https://hitokoto.cn/)

<a title="SSL" target="_blank" href="https://myssl.com/seal/detail?domain=blog.imsyy.top"><img src="https://img.shields.io/badge/MySSL-安全认证-brightgreen"></a>&nbsp;<a title="CDN" target="_blank" href="https://cdnjs.com/"><img src="https://img.shields.io/badge/CDN-Cloudflare-blue"></a>&nbsp;<a title="Copyright" target="_blank" href="https://imsyy.top/"><img src="https://img.shields.io/badge/Copyright%20%C2%A9%202020--2022-%E7%84%A1%E5%90%8D-red"></a>
