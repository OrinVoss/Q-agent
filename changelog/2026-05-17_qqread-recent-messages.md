# QQReadTool 新增 recent_messages 操作（#60）

**日期**: 2026-05-17
**类型**: 功能新增

## 变更内容
- NapCatApi 新增 `get_group_msg_history()` 和 `get_friend_msg_history()` 方法
- QQReadTool 新增 `recent_messages` 操作，支持群聊和私聊历史消息读取
- qq_read 工具描述更新

## 变更文件
- src/napcat/api.rs（新增两个历史消息 API 方法）
- src/tools/qq_read.rs（新增 recent_messages 操作）
