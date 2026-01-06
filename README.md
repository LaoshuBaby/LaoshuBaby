<!--

GitHub的在线展示环境和VSCode等代码编辑器中使用浏览器作为HTML渲染预览的方式存在不同，需要做出修正和适配以尽可能令不同环境下统一和兼容。

虽然是Markdown魔法但也会和前端项目一样在MDN的底线反复横跳。

1. 例如:file_folder:的emoji在正常浏览器访问GitHub的展示是可以正常显示为📁(U+1F4C1)的。但是在VSCode等编辑器内将不能正常显示，故采用由 https://emojipedia.org/file-folder#designs 提供的静态渲染来代替（且可保证所有平台效果一致）。
如果通过height=0.9em指定高度，则在VSCode中会直接消失并不显示（VSCode中显示需要指定像素，但不推荐硬编码像素高度而是通过em作为可变的1字符高度代替）。
而只采用style="height: 0.9em"指定高度，则在GitHub上会被全局的GitHub CSS覆盖，将显示为一张巨大的图片。
因此，通过硬编码GitHub CSS上的字号16px，和style中使用可变字符高度，来保证文本编辑器与网页都取得良好体验。

2. li的序号即使有display: inline;，在GitHub上也会被覆盖CSS

-->

<h2>
Language
</h2>

<a href="/locale/zh-Hans.md">简体中文</a> | <a href="/locale/en.md">English</a> | <a href="/locale/ja.md">日本語</a>

</hr>

<img
        style="float: right;"
        align="right"
        src="https://laoshubaby.oss-cn-beijing.aliyuncs.com/laoshubaby.jpg"
        width="233"
        height="233"
      />

### 仓库大全

<!--

希望能认真建设和推广的项目：
1. OSMChina三大原：Keqing-Zhongli-Yanfei
2. 知识开放，推动Mozilla和千树学院的建设
3. 所有参与翻译过的项目
4. python-cngal/bangumi 以及其他开放知识站点的数据驱动（甚至可以造一个更底层的swagger的驱动，然后把各个站点的驱动都配置文件化，这是远期目标）

-->

<!-- 玩具项目Repo -->

<details>
  <summary>
    <strong
      ><img
        src="https://em-content.zobj.net/source/mozilla/36/file-folder_1f4c1.png"
        style="height: 0.9em"
        height=16px
        alt=":file_folder:"
      />玩具项目Repo</strong
    >
  </summary>

  <!--
      <img src='https://raw.githubusercontent.com/vorillaz/devicons/ba75593fdf8d66496676a90cbf127d721f73e961/!SVG/python.svg' width='18'/> Python
      <img src='https://raw.github.com/voodootikigod/logo.js/master/js.png' width='18'/> Javascript <although_I_don_t_know_js/>
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" width="18"/> Typescript <although_I_don_t_know_ts/>
      <those_from_docentYT_readme_and_looks_good/>
      -->

- [参与贡献][Unigal-Script](https://github.com/Uni-Gal/UniGal-Script)
  [![](https://img.shields.io/github/stars/Uni-Gal/UniGal-Script.svg?style=flat-square&logo=github&logoWidth=20&label=Stars&labelColor=ce1126&color=fcd116&message=LAOSHUBABYMOE)](https://github.com/Uni-Gal/UniGal-Script/stargazers)
  [![](https://img.shields.io/github/forks/Uni-Gal/UniGal-Script.svg?style=flat-square&logo=github&logoWidth=20&label=Forks&labelColor=ce1126&color=fcd116&message=LAOSHUBABYMOE)](https://github.com/Uni-Gal/UniGal-Script/network/members)
- [独立开发][VisualMoe 视频隐藏帧检测](https://github.com/BUCTSNC/VisualMoe)
  [![](https://img.shields.io/github/stars/BUCTSNC/VisualMoe.svg?style=flat-square&logo=github&logoWidth=20&label=Stars&labelColor=ce1126&color=fcd116&message=LAOSHUBABYMOE)](https://github.com/BUCTSNC/VisualMoe/stargazers)
- [主导开发][Schedule_Intersector 学生组织课表求交器](https://github.com/BUCTSNC/Schudule_Intersector)
  [![](https://img.shields.io/github/stars/BUCTSNC/Schudule_Intersector.svg?style=flat-square&logo=github&logoWidth=20&label=Stars&labelColor=ce1126&color=fcd116&message=LAOSHUBABYMOE)](https://github.com/BUCTSNC/Schudule_Intersector/stargazers)
- [独立开发][OpenPlaids 生成这世界上所有的格纹](https://github.com/OpenPlaids/OpenPlaids)
  [![](https://img.shields.io/github/stars/OpenPlaids/OpenPlaids.svg?style=flat-square&logo=github&logoWidth=20&label=Stars&labelColor=ce1126&color=fcd116&message=LAOSHUBABYMOE)](https://github.com/OpenPlaids/OpenPlaids/stargazers)
- [社区索引][CUTI 中国高校TeX论文模板索引](https://github.com/LaoshuBaby/china-university-thesis-index)
[![](https://img.shields.io/github/stars/LaoshuBaby/china-university-thesis-index.svg?style=flat-square&logo=github&logoWidth=20&label=Stars&labelColor=ce1126&color=fcd116&message=LAOSHUBABYMOE)](https://github.com/LaoshuBaby/china-university-thesis-index/stargazers)
</details>

<!-- 娱乐性Repo -->

<details>
  <summary>
    <strong
      ><img
        src="https://em-content.zobj.net/source/mozilla/36/file-folder_1f4c1.png"
        style="height: 0.9em"
        height=16px
        alt=":file_folder:"
      />娱乐性Repo</strong
    >
  </summary>

- [【催更请Push】VampireValue(VV)](https://github.com/LaoshuBaby/VampireValue)
[![](https://img.shields.io/github/stars/LaoshuBaby/VampireValue.svg?style=flat-square&logo=github&logoWidth=20&label=Stars&labelColor=ce1126&color=fcd116&message=LAOSHUBABYMOE)](https://github.com/LaoshuBaby/VampireValue/stargazers)
</details>

### 集卡大全

<details>
  <summary>
    <strong
      ><img
        src="https://em-content.zobj.net/source/mozilla/36/file-folder_1f4c1.png"
        style="height: 0.9em"
        height=16px
        alt=":file_folder:"
      />Panel</strong
    >
  </summary>
  <b>
    <image
      src="https://github-readme-stats.vercel.app/api?username=LaoshuBaby&theme=tokyonight&show_icons=true&count_private=true"
      height="141"
    ></image>
  </b>
  <b>
    <image
      src="https://github-readme-stats.vercel.app/api/top-langs/?username=LaoshuBaby&theme=tokyonight&layout=compact&count_private=true"
      height="141"
    ></image>
  </b>
  <b>
    <image
      src="https://github-readme-stats.vercel.app/api/wakatime?username=LaoshuBaby&theme=tokyonight&layout=compact&count_private=true"
      height="141"
    ></image>
  </b>

  <!-- <image src='https://github-profile-trophy.vercel.app/?username=LaoshuBaby&theme=nord'></image> -->
</details>

### Social Media

<details>
  <summary>想🍑吃呢！鼠宝宝不会给你看的哦！</summary>
  <ul style="display:inline">
    <li>
      <a rel="me" href="https://wxw.moe/@laoshubaby"
        >(Mastodon)wxw.moe@laoshubaby</a
      >
    </li>
    <li>
      <a rel="me" href="https://en.osm.town/@laoshubaby"
        >(Mastodon)en.osm.town@laoshubaby</a
      >
    </li>
    <li>
      <a rel="me" href="https://misskey.io/@laoshubaby"
        >(Misskey)misskey.io@laoshubaby</a
      >
    </li>
  </ul>
</details>

<!--

### 参与的项目

<div>
  <img src="https://avatars.githubusercontent.com/u/3856374?s=200&v=4" height=50 ></img>
  <br>
  [@osmlab/NSI](https://github.com/osmlab/name-suggestion-index)
</div>
<div>
  <img src="https://avatars.githubusercontent.com/u/90183505?s=200&v=4" height=50 ></img>
  <br>
  @OSMChina
</div>
<div>
  <img src="https://avatars.githubusercontent.com/u/69070757?s=200&v=4" height=50 ></img>
  <br>
  @Uni-Gal
</div>

-->

<!--
https://github.com/ktKongTong/ktKongTong/blob/main/.github/workflows/action.yml
-->

剩下的……实在抱歉，因为感觉没什么技术含量，也算不上有多好玩，就不在这里展示和推荐了

I WANNA BE A NEKO GIRL！

---

~~_前面的区域以后再来探索吧。_~~
