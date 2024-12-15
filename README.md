<h1 align='center'>OneLight Theme For Typora</h1>

  <p align="center">
    <a>简体中文</a>
    |
    <a href="./README_en.md">English</a>
  </p>

---

<details>
  <summary>各版本下载量</summary>
  <img src="https://img.shields.io/github/downloads/caolib/typora-onelight-theme/v0.2.4/total"></br>
  <img src="https://img.shields.io/github/downloads/caolib/typora-onelight-theme/v0.2.3/total"></br>
  <img src="https://img.shields.io/github/downloads/caolib/typora-onelight-theme/v0.2.2/total"/></br>
  <img src="https://img.shields.io/github/downloads/caolib/typora-onelight-theme/v0.2.1/total"/></br>
  <img src="https://img.shields.io/github/downloads/caolib/typora-onelight-theme/v0.1.0/total"/></br>
  <img src="https://img.shields.io/github/downloads/caolib/typora-onelight-theme/v0.0.6/total"/></br>
  <img src="https://img.shields.io/github/downloads/caolib/typora-onelight-theme/v0.0.5/total"/></br>
</details>

> [!tip]
> **这里有两篇文章使用one-light主题，可点击查看主题详细效果展示**
>
> - **[markdown使用](https://bin-sites.pages.dev/markdown-doc/markdown-learn)**
> - **[计算机网络](https://bin-sites.pages.dev/net/计算机网络)**
> - **[mybatis-plus](https://bin-sites.pages.dev/mp)**

---

![](https://s2.loli.net/2024/12/15/8owUutvPmiQxCWI.png)

![image](https://s2.loli.net/2024/12/15/8yOnx3Kkj2htecp.png)

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
> - 如果想获取最新可以clone本仓库使用git更新或者从网络导入，主题的css文件都在右侧[Release](https://github.com/caolib/theme.typora.io/releases)中，如果喜欢onelight的话不妨点颗⭐获取后续更新，欢迎[提问](https://github.com/caolib/typora-onelight-theme/issues)和PR👏

---

**2.关于字体**

在`onelight.user.css`和`onelight.css`2个文件开头设置了默认字体，可以自行修改
![](https://github.com/user-attachments/assets/ab75260f-cff0-43b7-b8e5-dfea38e8525c)

**因为从网络导入字体文件太慢了，有时候甚至会失败(国内网络)，如果要使用主题中的字体，建议下载字体安装**

[⬇️![](https://img.shields.io/badge/下载CascadiaCode字体-white)](https://clb-cdn.pages.dev/fonts/CascadiaCode.ttf)
[⬇️![](https://img.shields.io/badge/下载喵字果汁体-white)](https://clb-cdn.pages.dev/fonts/MiaoZi-GuoZhiTi.ttf)
---

**3.关于背景图片**

> [!tip]
>
> 只要将背景图片放在css文件同一个文件夹就可以显示了，文件名为`bg.gif`,你可以在`onelight.user.css`中搜索这个文件名并替换成任何你想显示的其他图片



---



<div align=center>
  <img src="https://counter.seku.su/cmoe?name=caolib&theme=r34"/>
</div>
