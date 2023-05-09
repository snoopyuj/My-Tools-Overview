# 作品集

[[English Version]](./README_EN.md)

## 目錄

- [公司產品](#公司產品)
- [個人作品](#個人作品)
- [其他](#其他)
- [作品預覽](#作品預覽)

## 公司產品

[![](https://markdown-videos.deta.dev/youtube/ucg_tkJpu4o)](https://youtu.be/ucg_tkJpu4o)

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

### 主要貢獻

| No. | Description                                                                                               |
| --- | --------------------------------------------------------------------------------------------------------- |
| 1   | 獨力完成遊戲 Prototype，以最少的人力成本驗證核心玩法                                                      |
| 2   | 攝影機運鏡邏輯，過場與遊戲攝影機銜接，狀態優先度與疊加等設計 (如同 Cinemachine)                           |
| 3   | 導入 KD Tree 演算法，大幅提升搜尋賽道上物件效能 (O(logN) Time)                                            |
| 4   | 自動驗證遊戲穩定度機制，減少驗證時的人力成本                                                              |
| 5   | 開發音效編輯介面，改善開發流程                                                                            |
| 6   | 改善車輛 AI 效能 1.5 ms 至 0.05 ms                                                                        |
| 7   | 可移植的大廳制對戰配對系統                                                                                |
| 8   | 以 [DotNetty](https://github.com/Azure/DotNetty) 框架實作高穩定度與高效能的 Game Server，並移植至三個專案 |
| 9   | 構想出一套策略，使 Game Server 減少 75% 排行榜請求數                                                      |

## 個人作品

> 以下為過去開發的工具清單，提升開發效率、解決同伴困難。

| No. | Name                                              | Description                                                                                                                                              |
| --- | ------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | AnyStruct                                         | ★ 嘗試製作 struct 基底類，解決 C# 轉型 Boxing [[GitHub]](https://github.com/snoopyuj/AnyStruct)                                                          |
| 2   | [BInspector](#binspector)                         | ★ Unity 介面優化: 讓 Inspector 更加人性化 [[GitHub]](https://github.com/snoopyuj/BInspector)                                                             |
| 3   | [BSelection](#bselection)                         | ★ Unity 小工具: 記憶多選的場景物件，以利下次選取 [[GitHub]](https://github.com/snoopyuj/BSelection)                                                      |
| 4   | [BShortcut](#bshortcut)                           | ★ Unity 小工具: 記憶選取的專案資源或資料夾，以利下次選取 [[GitHub]](https://github.com/snoopyuj/BShortcut)                                               |
| 5   | [BSoundMute](#bsoundmute)                         | ★ Windows 工具，快速切換軟體靜音 [[GitHub]](https://github.com/snoopyuj/bSoundMute) [[巴哈文章]](https://forum.gamer.com.tw/Co.php?bsn=60030&sn=1868316) |
| 6   | [BSoundEditor](#bsoundeditor)                     | ★ Unity 工具: 於編輯面板上修改並預覽場景音效                                                                                                             |
| 7   | [Odin Array Enum Title](#odin-array-enum-title)   | ★ Unity 介面優化: 根據 Enum 命名陣列中的元素標題 [[GitHub]](https://github.com/snoopyuj/OdinEnumArrayTitle)                                              |
| 8   | [Full Screen Game View](#full-screen-game-view)   | Unity 小工具: 能將 Game View 最大化顯示並隱藏工具列 [[GitHub]](https://gist.github.com/snoopyuj/92e0b62ca687aeb5d5c76af573c32370)                        |
| 9   | [BMidline](#bmidline)                             | Unity 工具: 提高繪製賽道中線效率                                                                                                                         |
| 10  | [BEPU Unity](#bepu-unity)                         | 實驗將定點運算 (Fixed Point Math) 的物理系統 BEPU 導入 Unity，嘗試確定性同步 (Deterministic Synchronization) 的可能性                                    |
| 11  | [Unity Debugger](#unity-debugger)                 | Unity 工具: 使開發人員可依據鍵盤功能鍵切換不同 Debug 功能                                                                                                |
| 12  | [Unity Log Helper](#unity-log-helper)             | Unity 工具: 依標籤的不同，決定是否印出對應的 Log，使開發人員能專注在自己想注意的 Log 上                                                                  |
| 13  | [Delete Missing Scripts](#delete-missing-scripts) | Unity 小工具: 找尋物件中已遺失的腳本並刪除                                                                                                               |
| 14  | [BAttach](#battach)                               | Unity 小工具: 輕鬆控制物件貼地                                                                                                                           |
| 15  | [Trash View](#trash-view)                         | Windows 工具: 透過網路將複製的內容同步至其他電腦的剪貼簿中，方便快速複製貼上                                                                             |

## 其他

| No. | Name                                                            | Description                                                                                                     |
| --- | --------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- |
| 1   | [Ringash](#ringash)                                             | 協助獨立遊戲開發 [[Steam 連結]](https://store.steampowered.com/app/2323140/Ringash/)                            |
| 2   | [GTA4 Jason Statham](#gta4-jason-statham)                       | GTA4 MOD: 將主角臉型模仿傑森史塔森的模樣 [[MOD 連結]](https://www.gtagaming.com/jason-statham-face-f25156.html) |
| 3   | [The Witcher 3 White Wolf](#the-witcher-3-white-wolf)           | 巫師三 MOD: 依據小說描述，調整主角模型貼圖 [[MOD 連結]](https://www.nexusmods.com/witcher3/mods/2122)           |
| 4   | [The Witcher 3 Short Scar Ciri](#the-witcher-3-short-scar-ciri) | 巫師三 MOD: 美化女主角臉上疤痕 [[MOD 連結]](https://www.nexusmods.com/witcher3/mods/2036)                       |

## 作品預覽

### BInspector

[![](https://markdown-videos.deta.dev/youtube/fo9jejYDZWY)](https://youtu.be/fo9jejYDZWY)

### BSelection

<img src="./Previews/bSelection.png" width="400"></img>
![bSelectionDemo](./Previews/bSelectionDemo.gif)

### BShortcut

![bShortcutDemo](./Previews/bShortcutDemo.gif)

### BSoundMute

<img src="https://truth.bahamut.com.tw/s01/201508/e0f0c61736dcfb07f3c13e49d5df7c9b.JPG" width="200"></img>

### BSoundEditor

<img src="./Previews/SceneSoundEditor.png" width="500"></img>
[![](https://markdown-videos.deta.dev/youtube/W-92XYgx0m4)](https://youtu.be/W-92XYgx0m4)

### Odin Array Enum Title

![OdinArrayEnumTitle](https://github.com/snoopyuj/OdinEnumArrayTitle/raw/main/BTools/BInspector/Demo/demo.gif)

### Full Screen Game View

![FullScreenGameView](./Previews/FullScreenGameView.gif)

### BMidline

<img src="./Previews/bMidline.png" width="400"></img>
[![](https://markdown-videos.deta.dev/youtube/bk95cM1o4-E)](https://youtu.be/bk95cM1o4-E)

### BEPU Unity

<img src="./Previews/BepuUnity.gif" width="400"></img>

### Unity Debugger

<img src="./Previews/UnityDebugger.png" width="250"></img>

### Unity Log Helper

<img src="./Previews/UnityLogHelper.png" width="250"></img>

### Delete Missing Scripts

[![](https://markdown-videos.deta.dev/youtube/LxU48mpaAdA)](https://youtu.be/LxU48mpaAdA)

### BAttach

<img src="./Previews/bAttach.png" width="200"></img>

### Trash View

![TrashView](./Previews/TrashViewDemo.gif)

### Ringash

<img src="./Previews/Ringash.png" width="400"></img>
[![](https://markdown-videos.deta.dev/youtube/mC6Kpu-0aUU)](https://youtu.be/mC6Kpu-0aUU)

### GTA4 Jason Statham

<img src="https://www.gtagaming.com/images/25156/1386777654_cover.jpg" width="400"></img>

### The Witcher 3 White Wolf

<img src="https://staticdelivery.nexusmods.com/mods/952/images/2122-15-1480221687.jpg" width="400"></img>

### The Witcher 3 Short Scar Ciri

<img src="https://staticdelivery.nexusmods.com/mods/952/images/2036-1-1475309423.png" width="400"></img>
