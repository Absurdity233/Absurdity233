<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=190&text=Absurdity&fontAlign=50&section=header&color=0:8EC5FC,100:E0C3FC&fontColor=ffffff&animation=twinkling" alt="header"/>

<p>
  <a href="https://github.com/Absurdity233?tab=followers">
    <img src="https://img.shields.io/github/followers/Absurdity233?style=for-the-badge" alt="followers"/>
  </a>
  <a href="https://github.com/Absurdity233">
    <img src="https://img.shields.io/github/stars/Absurdity233?affiliations=OWNER%2CCOLLABORATOR&style=for-the-badge" alt="stars"/>
  </a>
  <a href="https://komarev.com/ghpvc/?username=Absurdity233&color=blueviolet&style=for-the-badge">
    <img src="https://komarev.com/ghpvc/?username=Absurdity233&color=blueviolet&style=for-the-badge" alt="views"/>
  </a>
</p>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=17&pause=1400&color=7AA2FF&center=true&vCenter=true&width=660&lines=Java+%7C+Rust+%7C+Go+%7C+C%2B%2B;mostly+backend%2C+sometimes+low-level;building+AI+agent+harnesses;reading+memory+over+DMA;Minecraft+and+some+open+source" alt="typing"/>

<p>主要写后端，偶尔往下钻一点。最近在折腾 AI agent 和 DMA，喜欢 Minecraft，攒了不少没看完的书，也开源过几样东西。</p>

<img src="https://img.shields.io/badge/Mizore%20Mode-ice%20blue%20%7C%20lavender-7AA2FF?style=for-the-badge" alt="mizore"/>

</div>

---

## 平时用的东西

<p align="center">
  <img src="https://skillicons.dev/icons?i=java,rust,go,cpp,spring,react,mysql,git,linux,idea,vscode,docker&perline=12" alt="skills"/>
</p>

工作里主要是 Java 后端：写业务、设计接口、把 CI/CD 和容器化那套搭起来。真正让我上心的还是性能、内存和并发——代码写得越久，越觉得这几块绕不开，也最容易写错。

## 在啃的

**AI Agent。** 不是调 API 写个对话框那种。真正有意思的是让模型自己去调工具、看结果、改下一步——怎么切上下文、怎么让它别在同一个坑里反复撞、怎么在它把事办完之前判断它是不是已经跑偏了。我现在写的东西里有很大一块是这类 harness：给 agent 一套能用的工具，然后看它怎么用坏。工具设计得好不好，跑几轮就露底了。这块还很糙，结论也经常被推翻，但每次多跑一遍都能捞到点东西。

**DMA。** 就是绕过操作系统直接读物理内存那套东西——FPGA 板子从 PCIe 那头看目标机的内存，目标机自己完全不知道。起因是想搞清楚一个进程的内存到底长什么样，后来发现拿到手只是第一步：页表得自己走，结构体得自己从汇编里反推，虚拟地址和物理地址之间那层翻译才是真正花时间的地方。现在手上是一块 PCILeech 的板子，配合 MemProcFS 取证和静态分析来回倒。离"想读哪就读哪"还差得远，但每次能把一个指针链走通，都挺爽的。

这两件事其实是一路的：都是在别人的抽象层底下找真实数据。只不过一个往下挖硬件，一个往上管模型。

## 一些数字

<p align="center">
  <a href="https://github.com/Absurdity233">
    <img src="https://github-readme-stats-fast.vercel.app/api?username=Absurdity233&show_icons=true&theme=radical&rank_icon=github&hide_border=true&hide=contribs" height="165" alt="stats"/>
  </a>
  <a href="https://github.com/Absurdity233">
    <img src="https://github-readme-stats-fast.vercel.app/api/top-langs?username=Absurdity233&layout=compact&theme=radical&hide_border=true&langs_count=8" height="165" alt="top languages"/>
  </a>
</p>

<p align="center">
  <a href="https://streak-stats.demolab.com/?user=Absurdity233&theme=radical&hide_border=true">
    <img src="https://streak-stats.demolab.com?user=Absurdity233&theme=radical&hide_border=true" height="165" alt="streak"/>
  </a>
</p>

<p align="center">
  <a href="https://github-trophy.vercel.app/?username=Absurdity233&theme=dracula&column=6&margin-w=8&no-frame=true&no-bg=true">
    <img src="https://github-trophy.vercel.app/?username=Absurdity233&theme=dracula&column=6&margin-w=8&no-frame=true&no-bg=true" alt="trophy"/>
  </a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Absurdity233/Absurdity233/output/github-contribution-grid-snake.svg" alt="snake"/>
</p>

---

## 找我

<p align="center">
  <a href="mailto:absurdity1337@gmail.com">
    <img src="https://img.shields.io/badge/Email-absurdity1337%40gmail.com-7AA2FF?logo=gmail&logoColor=fff&style=for-the-badge" alt="email"/>
  </a>
  <a href="https://wpa.qq.com/msgrd?v=3&uin=457676887&site=qq&menu=yes">
    <img src="https://img.shields.io/badge/QQ-457676887-EB1923?logo=tencentqq&logoColor=fff&style=for-the-badge" alt="qq"/>
  </a>
</p>

邮件或者 QQ 都行，聊代码、聊 Minecraft，或者只是随便说几句，都可以。

---

<div align="center">

<i>先让它跑起来，再让它跑快点。</i>

<img src="https://capsule-render.vercel.app/api?type=waving&height=130&section=footer&color=0:8EC5FC,100:E0C3FC" alt="footer"/>

</div>