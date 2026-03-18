# 組員貢獻紀錄

> 每位組員完成自己的分支後，把自己的名字和任務填進來，送出 PR。
> 這個檔案是刻意設計成「大家都要修改」，會產生 Merge Conflict，練習解決！

---

## 第 X 組

| 角色 | 姓名 | 負責分支 | 任務 | 狀態 |
|------|------|---------|------|------|
| 組長 | 林伽紜 | `main` `feature/change-title&header-color` | 修改標題 & header 顏色 | ✔️ |
| 組員 A | 朱覺祥 | `feature/member-a` | 修改使用者訊息顏色 & 加計數器 | ✔️ |

狀態：⬜ 未開始 / 🔄 進行中 / ✅ 已完成 / 🔀 PR 已開 / ✔️ 已 Merge

---

## 各組員任務說明

### 組長（`main` `feature/change-title&header-color` branch）
- [v] 把 `index.html` 裡的「第 X 組」改成你們組的實際名稱
- [v] 修改 `style.css` 裡 `header` 的背景顏色
- [v] 在這個檔案填入所有組員姓名
- [v] 最後負責 review 所有 PR 並 merge

### 組員 A（`feature/member-a` branch）
- [v] 修改 `style.css` 裡 `.message.user` 的 `background` 顏色
- [v] 在 `index.html` 加上訊息計數顯示（取消那行 comment）
- [v] 在 `sendMessage()` 函數中加上更新計數的邏輯
- [v] 開 PR，請組長 review

---

## 預期會出現的 Conflict

組員 A、B、D、E 都會修改 `style.css`，
組員 A、C、D、E 都會修改 `index.html`。

合併時會出現 conflict ── 這是**刻意設計的**，練習解決！
