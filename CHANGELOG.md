# 更新记录 / Changelog

## 0.4.4-pro-preview · 2026-10-21

本仓库首个公开内测候选。APK 构建于2026年10月20日，2026年10月21日收到用户真机验收通过反馈；GitHub 实际发布日期以 Release 时间为准。

### 本版修复

- 修复收藏时普通保存遮罩造成的全屏闪烁。
- 普通成功提示改为紧凑样式，约2.5秒自动消失，连续操作重新计时。
- 消除详情页同一提示在正文与底部重复显示的问题。
- 照片管理、箱内移动和复制成功提示自动收起；错误与需要继续操作的信息保留。
- 草稿处理不再使用不透明全屏遮罩，慢操作才显示局部状态。
- 点击已选状态不重复保存；“再记一件”入口不因短提示消失而丢失。

### 当前能力

本地物品档案、中英文界面、搜索筛选、长按多选与批量整理、位置及收纳箱、照片管理、单件草稿、完整备份恢复，以及同一应用中的单设备专业版激活。

### English

First public-preview candidate for this repository. The APK was built on October 20, 2026; a passing user phone-acceptance report was received on October 21. The actual GitHub publication date is the Release timestamp.

- Removed the full-screen save flash when toggling favorites.
- Made routine success messages compact and temporary, dismissing after about 2.5 seconds and restarting for repeated actions.
- Removed duplicate status feedback from item details.
- Photo, box-move, and copy success messages now clear automatically; errors and actionable information remain available.
- Replaced the opaque draft-processing screen with local status feedback.
- Selecting an already active status does not write again. The add-another-item action remains available after a temporary message clears.

Current capabilities include a local archive, Chinese/English UI, search and filters, multi-select and bulk organization, storage locations, photo management, single-item drafts, full backup/restore, and one-device Pro activation within the same app.
