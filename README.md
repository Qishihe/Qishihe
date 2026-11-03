<div align="center">

<img width="100%" src="assets/banner.svg" alt="banner" />

<a href="https://chd-charge.pages.dev/">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=19&pause=1100&color=6A11CB&center=true&vCenter=true&width=680&lines=find+a+free+charger+before+class;longsong-chd-charger%2C+in+production;hardware+%C3%97+web+%C3%97+automation;ship+small+things+people+actually+use" alt="typing" />
</a>

<br/>

<img src="https://img.shields.io/badge/CHANG'AN%20UNIVERSITY-%E9%95%BF%E5%AE%89%E5%A4%A7%E5%AD%A6-6A11CB?style=for-the-badge" alt="chd" />
<img src="https://img.shields.io/badge/MPL--2.0-open%20source-2ea44f?style=for-the-badge" alt="license" />
<img src="https://img.shields.io/badge/ROS2-Humble-22314E?style=for-the-badge&logo=ros&logoColor=white" alt="ros2" />

</div>

<br/>

## 关于我

> 先上线，再优雅。跑在别人手机里的丑代码，胜过躺在硬盘里的漂亮架构。

- **作品** — [`longsong-chd-charger`](https://chd-charge.pages.dev/) 长安大学充电桩空闲查询，独立站点在线运行中
- **日常** — 把重复劳动交给脚本：AI 工具自动签到、页面自动化、能省一步就省一步
- **主线（未开源）** — `S300` 轮式机械臂：RealMan ECO65-B 六轴臂 + ROS2 Humble + MoveIt2 + Gazebo，从仿真一路推到真机
- **信条** — 具体到接口名、话题名、能跑的代码；不要架构图，要能 `git clone` 的东西

<br/>

## 置顶项目

| 项目 | 它解决什么 | 状态 |
| :--- | :--- | :--- |
| **[longsong-chd-charger](https://github.com/Qishihe/longsong-chd-charger)**<br/><sub>长安大学充电桩空闲查询 · [在线试用](https://chd-charge.pages.dev/)</sub> | 出门前先看清哪个桩空着，少白跑一趟教学楼 | <img src="https://img.shields.io/github/stars/Qishihe/longsong-chd-charger?style=flat-square&color=6A11CB&label=stars" /> <img src="https://img.shields.io/github/last-commit/Qishihe/longsong-chd-charger?style=flat-square&color=2575FC&label=last" /> <img src="https://img.shields.io/github/license/Qishihe/longsong-chd-charger?style=flat-square&label=license" /> |
| **[zaoba](https://github.com/Qishihe/zaoba)**<br/><sub>早八 · AI 工具每日自动签到（WorkBuddy / 豆包 / 智谱），带本地控制台</sub> | 早上 8:30 之前把该签的到全签完，人还在睡 | <img src="https://img.shields.io/badge/status-running-2ea44f?style=flat-square" /> <img src="https://img.shields.io/github/last-commit/Qishihe/zaoba?style=flat-square&color=2575FC&label=last" /> |
| **[rea](https://github.com/Qishihe/rea)**<br/><sub>用 agent 逆向分析——从应用行为一路挖到原生二进制</sub> | 想搞懂一个东西到底怎么跑的，而不是只会用 | <img src="https://img.shields.io/badge/type-fork-8250df?style=flat-square" /> <img src="https://img.shields.io/github/last-commit/Qishihe/rea?style=flat-square&color=2575FC&label=last" /> |

<br/>

## 没开源的那条线

```text
   vi_grab            MoveIt2          ros2_rm_robot         ECO65-B
  (RGB-D pose)  -->  (plan + avoid) -->  (joint traj)   -->  (real arm)
       ^                                                          |
       |                                                          |
       +--------------  Gazebo Classic  <--------------------------+
                        (physics sim, same ROS2 API)
```

同一套 ROS2 接口，先喂给幽灵臂，再喂给铁疙瘩。仿真里跑不通的轨迹，真机上只会更贵。

<br/>

## 技术栈

**语言 & 环境**

<img src="https://skillicons.dev/icons?i=html,css,js,python,cpp,bash,linux,git" alt="langs" />

**机器人 & 自动化**

<img src="https://img.shields.io/badge/ROS2-Humble-22314E?style=flat-square&logo=ros&logoColor=white" />
<img src="https://img.shields.io/badge/MoveIt2-planning-0A66C2?style=flat-square" />
<img src="https://img.shields.io/badge/Gazebo-Classic-F58113?style=flat-square" />
<img src="https://img.shields.io/badge/Playwright-automation-2EAD33?style=flat-square&logo=playwright&logoColor=white" />
<img src="https://img.shields.io/badge/DDS-FF6F00?style=flat-square" />

<br/>

<!-- ============================================================
     数据统计区：当前 3 个公开仓库（其中 2 个 fork），
     卡片出来只有个位数，视觉上不如不放。
     等公开仓库和提交量起来后，删掉这层注释即可启用。
     注意：github-readme-stats 走 Vercel，部分网络环境需要代理。
     ============================================================

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=Qishihe&show_icons=true&count_private=true&hide_border=true&theme=transparent&title_color=6A11CB&icon_color=2575FC" alt="stats" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Qishihe&layout=compact&hide_border=true&theme=transparent&title_color=6A11CB" alt="langs" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Qishihe&theme=minimal&hide_border=true&color=6A11CB&line=2575FC&point=111111" alt="activity" />

</div>

-->

<br/>

<div align="center">

**找得到我**

<a href="https://chd-charge.pages.dev/"><img src="https://img.shields.io/badge/%E4%B8%AA%E4%BA%BA%E7%AB%99-chd--charge.pages.dev-6A11CB?style=flat-square" alt="site" /></a>
<a href="https://github.com/Qishihe"><img src="https://img.shields.io/badge/GitHub-Qishihe-181717?style=flat-square&logo=github" alt="github" /></a>
<a href="https://github.com/Qishihe/Qishihe/issues"><img src="https://img.shields.io/badge/Discuss-Issues-2ea44f?style=flat-square&logo=github" alt="issues" /></a>

<br/><br/>

<img width="100%" src="assets/footer.svg" alt="footer" />

</div>
