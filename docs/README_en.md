<h1 align='center'>OneLight Theme For Typora</h1>

<div align="center">
    <a href='https://github.com/caolib/typora-onelight-theme'>简体中文</a>
    |
    English
</div>



![](https://img.shields.io/github/downloads/caolib/typora-onelight-theme/total?labelColor=black&color=blue)
[![](https://img.shields.io/github/v/release/caolib/typora-onelight-theme?labelColor=black&color=red)](https://github.com/caolib/typora-onelight-theme/releases)
[![](https://img.shields.io/github/last-commit/caolib/typora-onelight-theme?labelColor=black&color=blue)](https://github.com/caolib/typora-onelight-theme/activity)
[![](https://api.netlify.com/api/v1/badges/6ca72e1b-7dc6-4d51-8542-e07bf9ad0a88/deploy-status)](https://typora-theme.netlify.app)
[![压缩打包](https://github.com/caolib/typora-onelight-theme/actions/workflows/css-compress.yml/badge.svg)](https://github.com/caolib/typora-onelight-theme/actions/workflows/css-compress.yml)

<details><summary><kbd>version history</summary></kbd>
  <img src="https://img.shields.io/github/downloads/caolib/typora-onelight-theme/v1.4.0/total"></br>
  <img src="https://img.shields.io/github/downloads/caolib/typora-onelight-theme/v1.3.0/total"></br>
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
---

## **1.Overview**


> [!tip]  
> **Here are two articles using the one-light theme. You can click to see detailed theme effect demonstrations.**  
>  
> - **[onelight](https://bin-sites.pages.dev/onelight)**  
> - **[Computer Networks](https://bin-sites.pages.dev/net/计算机网络)**  

---

![image-20250108140354139](https://s2.loli.net/2025/01/08/fNQF1ZCOgGydEUL.png)

![image-20250108140529374](https://s2.loli.net/2025/01/08/aMkKwdmVuTCtW4G.png)

![image-20250108140656725](https://s2.loli.net/2025/01/08/TyJutRejBLX3xGW.png)

<details><summary><kbd>Click to view more screenshots</summary></kbd>  
  <img src="https://s2.loli.net/2025/01/08/Ir1mgZCto4YS6lj.png"></br>  
  <img src="https://s2.loli.net/2025/01/08/ugxkC5UyvqGw6iP.png"></br>  
  <img src="https://s2.loli.net/2025/01/08/cAgBOqFoCMYE8S6.png"></br>  
	Integrated mode menu interface  
  <img src="https://s2.loli.net/2025/01/08/QF2UA9zPOW5X6ji.png"></br>  
</details>  

---

## **2. How to Use**  

> [!important]  
>  
> **Recommended**  
>  
> - Download the [theme file zip package](https://github.com/caolib/typora-onelight-theme/releases)  
> - In Typora, go to **File → Preferences → Appearance → Open Theme Folder**  
> - Extract the downloaded zip package, then paste the **CSS files** and **folder** into Typora's theme folder  
> - Restart Typora, then switch the theme from the menu bar, and you're all set!  


> [!caution]  
>  
> - **If you want to clone this repository and avoid cloning other branches, use the following command. This will only clone the main branch:**  
>  
>   ```shell  
>   git clone --single-branch https://github.com/caolib/typora-onelight-theme.git  
>   ```
>  
> - If you want to import from the web:  
>  
>   ```css  
>   @import url("https://cdn.jsdelivr.net/gh/caolib/typora-onelight-theme@onelight/dist/onelight.min.css");  
>   ```

---

## **3. About Fonts**  

The default font is set at the beginning of the `onelight.css` file, and you can modify it as needed.  
![](https://github.com/user-attachments/assets/ab75260f-cff0-43b7-b8e5-dfea38e8525c)  

> [!tip]  
>  
> **If you want to use the fonts in the theme, it’s recommended to download and install them.**  
> The Chinese font is [MiaoZi-GuoZhiTi](https://cdn.jsdelivr.net/gh/caolib/cdn@main/fonts/MiaoZi-GuoZhiTi.ttf), and the English font is [Cascadia Code](https://cdn.jsdelivr.net/gh/caolib/cdn@main/fonts/CascadiaCode.ttf).  

---

## **4. About Background Images**  

> [!important]  
>  
> Background images are located in the `onelight/img` folder. By default, the file is `bg.gif`. You can replace it as needed. Alternatively, you can search for the keyword `gif` in the CSS file to find the corresponding code and replace it. It is recommended to use images with transparent backgrounds.  
>  
> ```css  
> content {  
>      background-color: transparent;  
>      /* You can replace the image here. If you don't want it to appear, you can comment out this section.*/
>      background-image: url('./onelight/img/bg.gif');  
>      background-position: 100% 100%;  
>      background-repeat: no-repeat;  
>      background-size: 100px auto; /* Adjust the display size of the image */ 
>      transition: background-image .5s ease-in-out, background-size .5s ease-in-out;  
> }  
> ```
>  
> <img src="https://s2.loli.net/2024/12/15/Fn6LcrKWC2dlp1J.gif" alt="recording" style="zoom: 50%;" />  

---

## **5. Others**  

<img align='right' src="https://s2.loli.net/2025/01/04/zt7O3daMLDC5EHW.png" alt="Like" />✅ The theme looks better in integrated mode.  

❓ If you have any questions, feel free to ask in [Issues](https://github.com/caolib/typora-onelight-theme/issues).  

⭐ If you like this theme, please give it a star. Thank you!  

📄 The [docs](https://github.com/caolib/typora-onelight-theme/tree/onelight/docs) folder contains markdown files of example articles.  

🖼️ The [img](https://github.com/caolib/typora-onelight-theme/tree/onelight/onelight/img) folder contains background images for the theme. You can replace them with any image you like, or delete them if not needed.  



