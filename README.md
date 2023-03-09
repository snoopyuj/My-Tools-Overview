# 作品集

[[English Version]](./README_EN.md)

## 目錄

- [公司產品](#公司產品)
- [個人作品](#個人作品)
- [其他](#其他)
- [作品預覽](#作品預覽)

## 公司產品

[![](https://markdown-videos.deta.dev/youtube/G-Y7OHUk_xs)](https://youtu.be/G-Y7OHUk_xs)

<span>
    <a href="https://youtu.be/4_J2BJvY6-o" target="_blank">
        <img alt="Asphalt9DX" src="./Previews/Projects/Asphalt9DX.png" width="170">
    </a>
    <a href="https://youtu.be/0NxRoB6_TiM" target="_blank">
        <img alt="Asphalt9VR" src="./Previews/Projects/Asphalt9VR.png" width="170">
    </a>
    <a href="https://youtu.be/5gkZJXwEj4c" target="_blank">
        <img alt="Hypercross" src="./Previews/Projects/Hypercross.png" width="170">
    </a>
    <br/>
    <a href="https://youtu.be/-OFKzzNUtb4" target="_blank">
        <img alt="UltraMotoVR" src="./Previews/Projects/UltraMotoVR.jpg" width="170">
    </a>
    <a href="https://youtu.be/0aCgyzVBEaA" target="_blank">
        <img alt="OvertakeVR" src="./Previews/Projects/OvertakeVR.jpg" width="170">
    </a>
    <a href="https://youtu.be/AB4iQr1gpoc" target="_blank">
        <img alt="OvertakeDX" src="./Previews/Projects/OvertakeDX.jpg" width="170">
    </a>
    <br/>
    <a href="https://youtu.be/x51WJhPdX5E" target="_blank">
        <img alt="SpeedRider3" src="./Previews/Projects/SpeedRider3.jpg" width="170">
    </a>
    <a href="https://youtu.be/katB0DeYiOc" target="_blank">
        <img alt="FluffyRider" src="./Previews/Projects/FluffyRider.jpg" width="170">
    </a>
    <a href="https://youtu.be/xR06M50puak" target="_blank">
        <img alt="CaptainSub" src="./Previews/Projects/CaptainSub.jpg" width="170">
    </a>
</span>

> ### 狂野飆車 9 DX
>
> - 【後台】
>   - 資料庫
>   - Server
>     - 玩家資料、遊戲 Log、營收、活動、排行榜
>   - 玩家帳號登入 Server
>     - 機台 QR -> Server -> 導向第三方登入授權 -> oauth 取得 access token -> 取得資料 -> 登入
>   - 機台校時 Server
> - 【遊戲元件】
>   - Rank Manager
>     - 上傳玩家成績
>     - 同步全球、區網排行榜
>   - Revenue Manager
>   - Player Log Recorder
>   - GIF Recorder
>     - Webcam 拍攝玩家頭像
>     - 導入臉部追蹤
>     - 儲存拍攝畫面並製作成 GIF
>     - 將 GIF 同步至對戰玩家
>   - Webcam Streaming
>     - 影像同步至對戰玩家
>   - Progress Observer
>     - 同步對戰玩家遊戲流程進度
> - 【決策】
>   - 測試 LINE Bot
>     - 向 Server 取得當前玩家人數、營收等資訊
>     - <img src="./Previews/Works/A9DXLineBot.png" width="200"></img>
> - 【工具】
>   - 構想出新方式並教導音樂音效小組製作更逼真車輛音效
>   - [A9CT](#個人作品)
>   - [BSelection](#個人作品)
>   - [BAttach](#個人作品)

> ### 狂野飆車 9 VR
>
> - 【後台】
>   - 資料庫
>   - Server 移植
>   - 玩家帳號登入 Server 移植
>   - 機台校時 Server 移植
> - 【遊戲元件】
>   - Rank Manager 移植
>   - Revenue Manager 移植

> ### 極速雪摩
>
> - 【後台】
>   - 資料庫
>   - Server 移植
>   - 機台校時 Server 移植
> - 【遊戲元件】
>   - Rank Manager 移植
>   - Revenue Manager 移植
> - 【工具】
>   - [Progress Bar](#個人作品)

> ### 勝利摩托 VR
>
> - 【遊戲元件】
>   - Distance Manager
>     - KD-Tree Algorithm
>     - 管理與計算車輛里程數
>   - Event System
>     - Pub/Sub Pattern
>   - [Race Match Net](#個人作品)
>     - 大廳制對戰配對系統
> - 【工具】
>   - [BMidLine](#個人作品)

> ### 火線狂飆 VR
>
> - 【遊戲元件】
>   - AI Controller
>     - 名次戰術
>     - 閃避障礙物
>     - 過彎、甩尾
>   - Audio Manager
>     - 機台日夜音量變更
>     - <img src="./Previews/Works/OvertakeVrVolumeSettings.png" width="200"></img>
>     - 音量平衡動態切換
>     - 真實車輛引擎聲
>     - 車輛甩尾 Pitch 變化
>   - Auto Tester
>     - 自動化測試產品穩定度
>     - <img src="./Previews/Works/OvertakeVrAutoTest.png" width="200"></img>
>   - Sequence Update Manager
>     - 依場景物件階層，固定更新順序
> - 【美術】
>   - 串接運鏡動畫
>   - 優化車輛音效效果: 拉轉、燒胎等
> - 【決策】
>   - 評估與介紹 Unreal 4
>   - 評估與介紹 Wwise
>   - 實驗 Unity3D 中使用確定性同步物理，以降低網路傳輸量
>   - 實驗粒子合成引擎聲
> - 【工具】
>   - [Delete Missing Scripts](#個人作品)
>   - [BInspector](#個人作品)
>   - Find Objects Of Type All In Scene

> ### 極速摩托 3
>
> - 【決策】
>   - 評估 Unity 4.x vs Unity 5.x
>     - LOD 效能優化
>     - 布料、髮絲物理
> - 【遊戲元件】
>   - Distance Manager
>     - KD-Tree Algorithm
>     - 管理與計算車輛里程數
>   - Vehicle Manager
>     - 管理比賽車輛
>   - Event System
>     - Pub/Sub Pattern
>   - 攝影機運鏡
>     - 過場與遊戲攝影機銜接
>     - 狀態優先度與疊加設計
>     - <img src="./Previews/Works/Sr3CameraStrategyController.png" width="250"></img>
>     - Replay Cam 切換
>   - Audio Manager
>     - 機台日夜音量變更
>     - 音量平衡動態切換
>     - 真實車輛引擎聲
>     - 車輛甩尾 Pitch 變化
>   - IO Handler
>     - 管理框體 IO 訊號
> - 【工具】
>   - [B-Midline](#個人作品)
>   - [B-Sound-Editor](#個人作品)
>   - [Unity Debugger](#個人作品)
>   - [Unity Log Helper](#個人作品)

> ### 勝利追擊
>
> - 【優化】
>   - CPU 效能優化
> - 【美術】
>   - 引擎蓋視角嘗試
>   - 粒子特效控制
>   - 攝影機手持運鏡效果

> ### 毛毛童萌會
>
> - 【遊戲元件】
>   - AI 邏輯開發
> - 【美術】
>   - 角色動畫綁定
>   - 角色配件切換
>   - 角色材質切換

> ### 潛艇聯萌
>
> - 【物理】
>   - 物件碰撞
> - 【遊戲元件】
>   - 無限拼接賽道
>   - 障礙物設計
>   - 敵人設計
>   - 子彈設計
>   - 操作員選單設計
>   - Event System
> - 【IO 控制】
>   - 框體方向盤控制
> - 【工具】
>   - Trigger 編輯器
>   - 框體燈光編輯器

## 個人作品

> 以下為過去所開發的工具清單，提升團隊開發效率、協助夥伴。

| No. | Name                                              | Difficulty | Popularity | Description                                                                                                                                                                                                                      |
| --- | ------------------------------------------------- | ---------- | ---------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | [A9CT](#a9ct)                                     | `★★★★`     | `★★★`      | 遊戲修改器: 讓團隊成員能透過修改器自由控制他款遊戲視角，以參考其美術做法                                                                                                                                                         |
| 2   | Any-Struct                                        | `★★`       | `★★★`      | 嘗試製作 struct 基底類，解決 C# 轉型 Boxing [[文章連結]](https://bwaynesu.wordpress.com/2021/08/21/%e5%98%97%e8%a9%a6%e8%a3%bd%e4%bd%9c-struct-%e5%9f%ba%e5%ba%95%e9%a1%9e%ef%bc%8c%e8%a7%a3%e6%b1%ba%e8%bd%89%e5%9e%8b-boxing/) |
| 3   | [B-Attach](#b-attach)                             | `★★`       | `★★★`      | Unity 小工具: 輕鬆控制物件貼地                                                                                                                                                                                                   |
| 4   | [B-Inspector](#b-inspector)                       | `★★★`      | `★★★★`     | Unity 介面優化: 讓 Inspector 更加人性化                                                                                                                                                                                          |
| 5   | [B-Midline](#b-midline)                           | `★★★★★`    | `★★★★`     | Unity 工具: 提高繪製賽道中線效率                                                                                                                                                                                                 |
| 6   | [B-Selection](#b-selection)                       | `★★`       | `★★★★★`    | Unity 小工具: 記憶多選的場景物件，以利下次選取                                                                                                                                                                                   |
| 7   | [B-Shortcut](#b-shortcut)                         | `★★`       | `★★★★★`    | Unity 小工具: 記憶選取的專案資源或資料夾，以利下次選取                                                                                                                                                                           |
| 8   | [B-Sound-Editor](#b-sound-editor)                 | `★★★★`     | `★★★★★`    | Unity 工具: 於編輯面板上修改並預覽場景音效                                                                                                                                                                                       |
| 9   | [B-Sound-Mute](#b-sound-mute)                     | `★★★★`     | `★★★★★`    | Windows 系統工具，快速切換軟體靜音 [[巴哈文章]](https://forum.gamer.com.tw/Co.php?bsn=60030&sn=1868316)                                                                                                                          |
| 10  | [BEPU-Unity](#bepu-unity)                         | `★★★★★`    | `★★`       | 實驗將定點運算 (Fixed Point Math) 的物理系統 BEPU 導入 Unity，嘗試確定性同步 (Deterministic Synchronization) 的可能性                                                                                                            |
| 11  | [Delete-Missing-Scripts](#delete-missing-scripts) | `★★`       | `★★★★`     | Unity 小工具: 找尋物件中已遺失的腳本並刪除                                                                                                                                                                                       |
| 12  | [Dot-Netty-Server](#dot-netty-server)             | `★★★★★`    | `★★★★★`    | 利用 [DotNetty](https://github.com/Azure/DotNetty) 與 [MessagePack](https://github.com/neuecc/MessagePack-CSharp) 所做成的 C# Server 框架，效能、移植性兼具                                                                      |
| 13  | [Full-Screen-Game-View](#full-screen-game-view)   | `★★★`      | `★★`       | Unity 小工具: 能將 Game View 最大化顯示並隱藏工具列                                                                                                                                                                              |
| 14  | Net-Kit-Win7                                      | `★★`       | `★★★★★`    | Windows 系統工具: 快速切換網路介面卡靜態、動態 IP                                                                                                                                                                                |
| 15  | [Progress-Bar](#progress-bar)                     | `★★`       | `★★★★★`    | Windows 工具: 於畫面上顯示進度條與設定的文字內容                                                                                                                                                                                 |
| 16  | [Race-Match-Net](#race-match-net)                 | `★★★★★`    | `★★★★★`    | 可移植的大廳制對戰配對系統                                                                                                                                                                                                       |
| 17  | [Trash-View](#trash-view)                         | `★★★`      | `★★★★★`    | Windows 工具: 透過網路將複製的內容同步至其他電腦的剪貼簿中，方便快速複製貼上                                                                                                                                                     |
| 18  | [Unity-Debugger](#unity-debugger)                 | `★★★`      | `★★★★★`    | Unity 工具: 使開發人員可依據鍵盤功能鍵切換不同 Debug 功能                                                                                                                                                                        |
| 19  | [Unity-Log-Helper](#unity-log-helper)             | `★★`       | `★★★★★`    | Unity 工具: 依標籤的不同，決定是否印出對應的 Log，使開發人員能專注在自己想注意的 Log 上                                                                                                                                          |

## 其他

| No. | Name                                                            | Description                                                                                                          |
| --- | --------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------- |
| 1   | [GTA4-Jason-Statham](#gta4-jason-statham)                       | 製作 GTA4 MOD: 將主角臉型模仿傑森史塔森的模樣 [[MOD 連結]](https://www.gtagaming.com/jason-statham-face-f25156.html) |
| 2   | [The-Witcher-3-White-Wolf](#the-witcher-3-white-wolf)           | 製作巫師三 MOD: 依據小說描述，調整主角模型貼圖 [[MOD 連結]](https://www.nexusmods.com/witcher3/mods/2122)            |
| 3   | [The-Witcher-3-Short-Scar-Ciri](#the-witcher-3-short-scar-ciri) | 製作巫師三 MOD: 美化女主角臉上疤痕 [[MOD 連結]](https://www.nexusmods.com/witcher3/mods/2036)                        |

## 作品預覽

### A9CT

<img src="./Previews/A9CT.png" width="200"></img>

### B-Attach

<img src="./Previews/bAttach.png" width="200"></img>

### B-Inspector

[![](https://markdown-videos.deta.dev/youtube/fo9jejYDZWY)](https://youtu.be/fo9jejYDZWY)

### B-Midline

<img src="./Previews/bMidline.png" width="400"></img>
[![](https://markdown-videos.deta.dev/youtube/bk95cM1o4-E)](https://youtu.be/bk95cM1o4-E)

### B-Selection

<img src="./Previews/bSelection.png" width="400"></img>
![bSelectionDemo](./Previews/bSelectionDemo.gif)

### B-Shortcut

![bShortcutDemo](./Previews/bShortcutDemo.gif)

### B-Sound-Editor

<img src="./Previews/SceneSoundEditor.png" width="500"></img>
[![](https://markdown-videos.deta.dev/youtube/W-92XYgx0m4)](https://youtu.be/W-92XYgx0m4)

### B-Sound-Mute

<img src="https://truth.bahamut.com.tw/s01/201508/e0f0c61736dcfb07f3c13e49d5df7c9b.JPG" width="200"></img>

### Dot-Netty-Server

<img src="./Previews/DotNettyServer.png" width="400"></img>

### BEPU-Unity

<img src="./Previews/BepuRecorder.png" width="250"></img>

### Delete-Missing-Scripts

[![](https://markdown-videos.deta.dev/youtube/LxU48mpaAdA)](https://youtu.be/LxU48mpaAdA)

### Full-Screen-Game-View

![FullScreenGameView](./Previews/FullScreenGameView.gif)

### Progress-Bar

<img src="./Previews/ProgressBar.gif" width="250"></img>

### Race-Match-Net

<img src="./Previews/RaceMatchNet.jpg" width="250"></img>
</br>
<img src="./Previews/LocalNetFlowChart.png" height="60"></img>

### Trash-View

![TrashView](./Previews/TrashViewDemo.gif)

### Unity-Debugger

<img src="./Previews/UnityDebugger.png" width="250"></img>

### Unity-Log-Helper

<img src="./Previews/UnityLogHelper.png" width="250"></img>

### GTA4-Jason-Statham

<img src="https://www.gtagaming.com/images/25156/1386777654_cover.jpg" width="400"></img>

### The-Witcher-3-White-Wolf

<img src="https://staticdelivery.nexusmods.com/mods/952/images/2122-15-1480221687.jpg" width="400"></img>

### The-Witcher-3-Short-Scar-Ciri

<img src="https://staticdelivery.nexusmods.com/mods/952/images/2036-1-1475309423.png" width="400"></img>
