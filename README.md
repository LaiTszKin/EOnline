# EOnline

EOnline 是一個使用 Rust 開發中的專案，目前提供最小化的 CLI 骨架，作為未來 Discord 生活模擬遊戲的起點。

## 目前狀態

- 現有程式會輸出 `Hello, world!`
- 尚未整合 Discord Bot framework
- 尚未實作玩家資料、事件循環與持久化

## 專案目標

- 建立可互動的 Discord 遊戲體驗
- 模擬現實生活中的角色狀態、行動與事件
- 提供可擴充的遊戲系統（經濟、任務、成長等）

## 開發

### 需求

- Rust（建議最新 stable）
- Cargo

### 執行

```bash
cargo run
```

預期輸出：

```text
Hello, world!
```

### 測試

```bash
cargo test
```

## 路線圖

- [ ] 整合 Discord Bot framework
- [ ] 設計玩家資料模型
- [ ] 建立指令系統與事件循環
- [ ] 加入持久化儲存
