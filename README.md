<h1 align='center'>OneLight Theme For Typora</h1>

  <p align="center">
    <a>简体中文</a>
    |
    <a href="./README_en.md">English</a>
  </p>


![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/caolib/typora-onelight-theme/total?labelColor=white&color=blue)
[![GitHub Release](https://img.shields.io/github/v/release/caolib/one-light-theme?labelColor=blue&color=red)](https://github.com/caolib/typora-onelight-theme/releases)
[![GitHub last commit](https://img.shields.io/github/last-commit/caolib/one-light-theme?labelColor=white&color=blue)](https://github.com/caolib/one-light-theme/activity)
[![Netlify Status](https://api.netlify.com/api/v1/badges/6ca72e1b-7dc6-4d51-8542-e07bf9ad0a88/deploy-status)](https://typora-theme.netlify.app)
[⬇️![](https://img.shields.io/badge/点击下载最新-white)](https://github.com/caolib/typora-onelight-theme/releases/latest/download/onelight.zip)
---

<details>
  <summary>各版本下载量</summary>
  <img src="https://img.shields.io/github/downloads/caolib/typora-onelight-theme/v0.2.3/total"></br> 
  <img src="https://img.shields.io/github/downloads/caolib/typora-onelight-theme/v0.2.2/total"/></br>
  <img src="https://img.shields.io/github/downloads/caolib/typora-onelight-theme/v0.2.1/total"/></br>
  <img src="https://img.shields.io/github/downloads/caolib/typora-onelight-theme/v0.1.0/total"/></br>
  <img src="https://img.shields.io/github/downloads/caolib/typora-onelight-theme/v0.0.6/total"/></br>
  <img src="https://img.shields.io/github/downloads/caolib/typora-onelight-theme/v0.0.5/total"/></br>
</details>

> [!tip]
> **这里有两篇文章使用one-light主题，可点击查看主题详细效果展示**
> - **[markdown使用](https://bin-sites.pages.dev/markdown-doc/markdown-learn)**
> - **[计算机网络](https://bin-sites.pages.dev/net/计算机网络)**
> - **[mybatis-plus](https://bin-sites.pages.dev/mp)**

---

![image](https://github.com/user-attachments/assets/d56a5c27-7b81-45f9-84cb-8b91df92eba9)

**1.如何使用**
- 下载css文件到本地（推荐）
  - 下载css文件
  - 在typora中选择 文件 → 偏好设置 → 外观 → 打开主题文件夹
  - 将下载的2个css文件都粘贴到这个目录然后重新启动typora，点击主题就能切换了

- 你也可以选择从网络导入

  - 在typora主题文件夹下创建一个css文件（名字随意，比如onelight.css）

  - 加入这两行

    ```css
    @import url('https://cdn.jsdelivr.net/gh/caolib/one-light-theme@main/onelight.css');
    @import url('https://cdn.jsdelivr.net/gh/caolib/one-light-theme@main/onelight.user.css');
    ```

  - 重启typora切换主题

> [!caution]
>
> - 从网络导入可以实时获取主题的最新更改，缺点是每次打开都需要加载一会才行
> - 如果要自行修改，建议修改`onelight.user.css`文件，将你自己的样式放在这个文件中
> - 无需克隆本仓库,（这个仓库是部署官方主题网站的，没有主题的css）,如果想更快地获取更新可以克隆这个[**one-light-theme**](https://github.com/caolib/one-light-theme)仓库然后用git更新或者从网络导入， css文件都在右侧[Release](https://github.com/caolib/theme.typora.io/releases)中，如果喜欢onelight的话不妨点颗⭐获取后续更新，欢迎[提问](https://github.com/caolib/typora-onelight-theme/issues)和PR👏

---

**2.关于字体**

在`onelight.user.css`和`onelight.css`2个文件开头设置了默认字体，可以自行修改
![](https://github.com/user-attachments/assets/ab75260f-cff0-43b7-b8e5-dfea38e8525c)

**因为从网络导入字体文件太慢了，有时候甚至会失败(国内网络)，如果要使用主题中的字体，建议下载字体安装**

[⬇️![](https://img.shields.io/badge/下载CascadiaCode字体-white)](https://clb-cdn.pages.dev/fonts/CascadiaCode.ttf)
[⬇️![](https://img.shields.io/badge/下载喵字果汁体-white)](https://clb-cdn.pages.dev/fonts/MiaoZi-GuoZhiTi.ttf)
---
<div align=center>
  <img src="https://counter.seku.su/cmoe?name=caolib&theme=r34"/>
</div>
