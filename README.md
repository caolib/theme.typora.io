<h1 align='center'>OneLight Theme For Typora</h1>

![](https://img.shields.io/github/downloads/caolib/typora-onelight-theme/total?labelColor=white&color=blue)
[![](https://img.shields.io/github/v/release/caolib/one-light-theme?labelColor=blue&color=red)](https://github.com/caolib/typora-onelight-theme/releases)
[![](https://img.shields.io/github/last-commit/caolib/one-light-theme?labelColor=white&color=blue)](https://github.com/caolib/typora-onelight-theme/activity)
[![](https://api.netlify.com/api/v1/badges/6ca72e1b-7dc6-4d51-8542-e07bf9ad0a88/deploy-status)](https://typora-theme.netlify.app)

[![压缩打包](https://github.com/caolib/typora-onelight-theme/actions/workflows/css-compress.yml/badge.svg)](https://github.com/caolib/typora-onelight-theme/actions/workflows/css-compress.yml)
---

<details><summary><kbd>各版本下载量</summary></kbd>
      <img src="https://img.shields.io/github/downloads/caolib/typora-onelight-theme/v1.2.4/total"></br>
  <img src="https://img.shields.io/github/downloads/caolib/typora-onelight-theme/v1.2.3/total"></br>
  <img src="https://img.shields.io/github/downloads/caolib/typora-onelight-theme/v1.2.0/total"></br>
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
> - **[onelight](https://bin-sites.pages.dev/onelight)**
> - **[计算机网络](https://bin-sites.pages.dev/net/计算机网络)**

---

![](https://s2.loli.net/2024/12/29/4zq9VbuAKvkFhYo.png)

![image-20241229005801957](https://s2.loli.net/2024/12/29/mHh5nuwyVWvpoGI.png)

## **1.如何使用**

- 下载[主题文件](https://github.com/caolib/typora-onelight-theme/releases)
- 在typora中选择 文件 → 偏好设置 → 外观 → 打开主题文件夹
- 将下载的zip解压，将**css文件**和**文件夹**粘贴到typora的主题文件夹中

> [!caution]
>
> - **如果你想克隆本仓库，为了避免克隆到其他分支，请使用下面这条命令,这样只会克隆主分支**
>
>   ```shell
>   git clone --single-branch https://github.com/caolib/typora-onelight-theme.git
>   ```
>
> - 如果你想从网络导入
>
>   ```css
>   @import url("https://cdn.jsdelivr.net/gh/caolib/typora-onelight-theme@onelight/dist/onelight.min.css");
>   ```

---

## **2.关于字体**

在`onelight.css`文件开头设置了默认字体，可以自行修改
![](https://github.com/user-attachments/assets/ab75260f-cff0-43b7-b8e5-dfea38e8525c)

> **如果要使用主题中的字体，建议下载字体安装**,中文字体是[喵字果汁体](https://clb-cdn.pages.dev/fonts/MiaoZi-GuoZhiTi.ttf)，英文字体是Cascadia Code

## **3.关于背景图片**

> [!tip]
>
> 背景图片在`onelight/img`文件夹下，默认是bg.gif，可以自行替换,你也可以在css文件中搜索并替换文件
>
> ```css
> content {
>     background-color: transparent;
>     //可以替换此处的图片，不想显示可以将这段整个注释掉
>     background-image: url('./onelight/img/bg.gif');
>     background-position: 100% 100%;
>     background-repeat: no-repeat;
>     background-size: 100px auto; // 调整大小
>     transition: background-image .5s ease-in-out, background-size .5s ease-in-out
> }
> ```
>
> <img src="https://s2.loli.net/2024/12/15/Fn6LcrKWC2dlp1J.gif" alt="recording" style="zoom: 50%;" />
