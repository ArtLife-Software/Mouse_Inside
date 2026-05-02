# Mouse Inside

![OS](https://img.shields.io/badge/OS-Windows-blue?style=flat-square&logo=windows)
![Language](https://img.shields.io/badge/Language-AutoHotkey_v2-green?style=flat-square&logo=autohotkey)
![Locale](https://img.shields.io/badge/Locale-正體中文-orange?style=flat-square)
![License](https://img.shields.io/badge/License-GPL_v3-red?style=flat-square)
![Latest Release](https://img.shields.io/github/v/release/ArtLife-Software/Mouse_Inside?style=flat-square&color=blue)
![Downloads](https://img.shields.io/github/downloads/ArtLife-Software/Mouse_Inside/total?style=flat-square&logo=github)

**Mouse Inside** 是一款專為多螢幕使用者設計的鼠標鎖定工具。它能將鼠標限制在當前使用的螢幕範圍內，防止在進行激烈遊戲、簡報或精細繪圖時，鼠標意外滑入另一個螢幕而導致誤觸或失焦。

---

## 🌟 核心功能

*   **智慧鎖定**：自動偵測鼠標所在螢幕並立即鎖定範圍。
*   **動態解鎖**：按住快捷鍵即可暫時解除限制，自由穿梭於螢幕之間。
*   **快速跳轉**：透過快捷鍵直接將鼠標切換至上一個或下一個螢幕。
*   **強效防穿透**：結合 `WinEventHook` 與備援檢查機制，有效防止 Windows 因切換視窗而自動解除鎖定。
*   **高相容性**：支援多螢幕、不同解析度及 DPI 縮放環境。

---

## ⌨️ 快捷鍵指南

| 功能 | 快捷鍵 |
| :--- | :--- |
| **暫時解除鎖定** | 長按 `Ctrl` |
| **重新鎖定** | 放開 `Ctrl` (自動鎖定於當前所在螢幕) |
| **跳轉至相鄰螢幕** | `Ctrl` + `Alt` + `←` / `→` |

---

## 🚀 安裝與使用

1.  前往 [Releases](https://github.com/ArtLife-Software/Mouse_Inside/releases) 頁面下載最新版本的執行檔 (`.exe`)。
2.  以 **管理員權限** 執行程式（為了確保在全螢幕遊戲或高權限視窗下依然有效）。
3.  程式執行後會自動鎖定鼠標於主螢幕，您可以透過系統匣 (Tray Icon) 圖示查看說明或結束程式。

---

## 🛠️ 開發資訊

*   **語言**：AutoHotkey v2.0
*   **環境**：Windows 10 / 11 (x64)
*   **授權**：GPL-3.0 License
*   **技術重點**：
    *   使用 `ClipCursor` API 進行硬體級限制。
    *   實作 `SetWinEventHook` 監聽系統事件，確保鎖定不因焦點改變而失效。
    *   採用物理座標計算，支援非對稱螢幕排列。

---

## 👨‍💻 關於作者

**林彥丞 (Yancheng Lin)**
*   **Email**: [lin.yancheng@outlook.com](mailto:lin.yancheng@outlook.com)
*   **GitHub**: [ArtLife-Software](https://github.com/ArtLife-Software)
*   **社群交流**: [O & C VBA研究社 (Facebook)](https://www.facebook.com/groups/vba.club)
*   **所在地**: 中華民國台灣

---

## ⚖️ 授權協議

本專案採用 **GPL-3.0 開源協議**。您可以自由地使用、修改及分發本軟體，但請務必遵守協議中的相關規定。

---

### 💡 意見回饋
如果您在使用過程中遇到任何問題或有功能建議，歡迎透過 [Issues](https://github.com/ArtLife-Software/Mouse_Inside/issues) 提交，或直接聯繫開發者。
