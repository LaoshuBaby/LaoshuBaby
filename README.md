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

### 代表仓库

WIP

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

<hr/>

I WANNA BE A NEKO GIRL！

~~_前面的区域以后再来探索吧。_~~
