<!-- header wave -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:1F6FEB,100:58A6FF&height=200&section=header&text=Cheng-Yu%20Pu&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=%E9%83%A8%E6%94%BF%E4%BD%91%20%C2%B7%20systems%20%C2%B7%20robotics%20%C2%B7%20world%20models&descAlignY=58&descSize=18" />

<div align="center">

<a href="https://github.com/pukyle">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=900&color=58A6FF&center=true&vCenter=true&width=560&lines=%24+insmod+pukyle.ko;CSIE+%40+NCKU+%C2%B7+rank+5%2F165;RA+%40+Academia+Sinica+IIS;teaching+drones+not+to+hit+walls;segfault+%3F+gdb+it." alt="typing" />
</a>

<a href="mailto:pukyle2129266@gmail.com"><img src="https://img.shields.io/badge/-pukyle2129266%40gmail.com-0A84FF?style=flat-square&logo=gmail&logoColor=white" /></a>
<img src="https://img.shields.io/badge/NCKU_CSIE-Top_3%25-2EA043?style=flat-square" />
<img src="https://komarev.com/ghpvc/?username=pukyle&style=flat-square&color=58A6FF&label=views" />

</div>

```console
pukyle@ncku:~$ whoami
Cheng-Yu Pu · CSIE senior @ National Cheng Kung University (2023–2027)
pukyle@ncku:~$ cat interests.txt
os internals · low-level systems · autonomous UAVs · video world models
pukyle@ncku:~$ uptime
RA @ Academia Sinica IIS since Jul 2026, load average: coffee, coffee, coffee
```

成大資工大四，系排 5/165（GPA 4.17/4.3）。

喜歡往底層鑽：寫過 Linux kernel module，用 `lock cmpxchg` 手刻 spinlock。也做無人機避障，單眼深度估計接 informed-RRT\*，在 AirSim 裡飛。

現在在中研院資訊所當兼任研究助理（陳駿丞老師），研究 video world model 生出來的影片，物理狀態能不能跨片段接得上。

## 🔬 Research

**Academia Sinica, IIS**：Summer Intern `Jul–Aug 2026` → Part-time RA `Sep 2026–now`

看 Diffusion、Flow Matching、Autoregressive 三種生成方式，在時間和幾何上各自能維持多少一致性。還在做，結果之後補。

## 🛠️ Projects

<details open>
<summary><b>🛰️ 無人機 3D 自主導航</b>　·　畢業專題，系展第 4 名</summary>
<br/>

```mermaid
flowchart LR
    A[📷 單眼影像] --> B[Depth Anything V2]
    B --> C[3D 障礙物重建]
    C --> D[informed-RRT*]
    D --> E[🚁 AirSim 四旋翼]
    E -. 新的一幀 .-> A
```

只靠一顆鏡頭估深度，再用 informed-RRT\* 算出不撞牆的 3D 航線。

`Python` `PyTorch` `AirSim`
</details>

<details>
<summary><b>🐧 Linux Kernel Modules</b>　·　進階作業系統</summary>
<br/>

- 記憶體內的檔案系統，自己寫 VFS 的 inode 和 dentry 操作
- 用 x86 inline assembly（`lock cmpxchg`）刻 spinlock，量多核搶鎖的成本
- 輕量 IPC，順便摸清楚 kernel/user space 的 memory mapping

`C` `x86 Assembly` `LKM`
</details>

<details>
<summary><b>👁️ 即時影像分類 GUI</b>　·　電腦視覺課</summary>
<br/>

PyQt5 介面接攝影機即時推論，ResNet-18 / LeNet-5 驗證準確率 90% 以上，可以看 feature map 和 CAM。

`PyTorch` `OpenCV` `PyQt5`
</details>

## 🏆 Honors

| | |
|---|---|
| 書卷獎 ×2 | 2025 春（系排 1）、2025 秋（系排 5） |
| 成大資工系展 佳作（第 4 名） | Jun 2026 |
| NCPC 全國大專程式設計競賽 決賽 | Oct 2026 |
| 成大單車節 講者 | Feb–Mar 2026 |

## 🧰 Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=c,cpp,py,bash,linux,arch,ubuntu,pytorch,opencv,docker,git,cmake&perline=12" />
</p>

## 📈 Activity

<div align="center">
  <img height="150" src="https://github-readme-stats.vercel.app/api?username=pukyle&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117" />
  <img height="150" src="https://streak-stats.demolab.com?user=pukyle&theme=tokyonight&hide_border=true&background=0D1117" />
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=pukyle&theme=tokyo-night&hide_border=true&area=true&bg_color=0D1117" />

  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/pukyle/pukyle/output/github-snake-dark.svg" />
    <img alt="snake eating contributions" src="https://raw.githubusercontent.com/pukyle/pukyle/output/github-snake.svg" />
  </picture>
</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:58A6FF,50:1F6FEB,100:0D1117&height=110&section=footer" />
