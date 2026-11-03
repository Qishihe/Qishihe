<div align="center">

<img width="100%" src="assets/banner.svg" alt="banner" />

<a href="https://chd-charge.pages.dev/">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=19&pause=1100&color=6A11CB&center=true&vCenter=true&width=680&lines=chd-charge.pages.dev;ROS2+Humble+%2F+MoveIt2+%2F+Gazebo;Chang%27an+University" alt="typing" />
</a>

<br/>

<img src="https://img.shields.io/badge/CHANG'AN%20UNIVERSITY-%E9%95%BF%E5%AE%89%E5%A4%A7%E5%AD%A6-6A11CB?style=for-the-badge" alt="chd" />
<img src="https://img.shields.io/badge/MPL--2.0-open%20source-2ea44f?style=for-the-badge" alt="license" />
<img src="https://img.shields.io/badge/ROS2-Humble-22314E?style=for-the-badge&logo=ros&logoColor=white" alt="ros2" />

</div>

<br/>

## 关于

- **学校** — 长安大学
- **公开项目** — `longsong-chd-charger`：充电桩空闲查询，部署在 [chd-charge.pages.dev](https://chd-charge.pages.dev/)
- **私有项目** — `S300` 轮式机械臂：RealMan ECO65-B 六轴协作臂 + ROS2 Humble + MoveIt2 + Gazebo
- **其他仓库** — `zaoba`（AI 工具定时签到）、`rea`（agent 逆向分析），均为 fork

<br/>

## 项目

| 项目 | 说明 | 状态 |
| :--- | :--- | :--- |
| **[longsong-chd-charger](https://github.com/Qishihe/longsong-chd-charger)**<br/><sub>长安大学充电桩空闲查询 · [在线试用](https://chd-charge.pages.dev/)</sub> | 查询各充电桩当前空闲状态 | <img src="https://img.shields.io/github/stars/Qishihe/longsong-chd-charger?style=flat-square&color=6A11CB&label=stars" /> <img src="https://img.shields.io/github/last-commit/Qishihe/longsong-chd-charger?style=flat-square&color=2575FC&label=last" /> <img src="https://img.shields.io/github/license/Qishihe/longsong-chd-charger?style=flat-square&label=license" /> |

<br/>

## S300 轮式机械臂

```text
   vi_grab            MoveIt2          ros2_rm_robot         ECO65-B
  (RGB-D pose)  -->  (plan + avoid) -->  (joint traj)   -->  (real arm)
       ^                                                          |
       |                                                          |
       +--------------  Gazebo Classic  <--------------------------+
                        (physics sim, same ROS2 API)
```

仿真与真机共用同一套 ROS2 接口——先在 Gazebo 里验证轨迹，再下发到 ECO65-B。

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
     数据统计区：当前 3 个公开仓库（其中 2 个 fork），卡片出来只有个位数。
     公开仓库和提交量起来后，删掉这层注释即可启用。
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

<a href="https://chd-charge.pages.dev/"><img src="https://img.shields.io/badge/%E4%B8%AA%E4%BA%BA%E7%AB%99-chd--charge.pages.dev-6A11CB?style=flat-square" alt="site" /></a>
<a href="https://github.com/Qishihe"><img src="https://img.shields.io/badge/GitHub-Qishihe-181717?style=flat-square&logo=github" alt="github" /></a>
<a href="https://github.com/Qishihe/Qishihe/issues"><img src="https://img.shields.io/badge/Issues-Qishihe%2FQishihe-2ea44f?style=flat-square&logo=github" alt="issues" /></a>

<br/><br/>

<img width="100%" src="assets/footer.svg" alt="footer" />

</div>
