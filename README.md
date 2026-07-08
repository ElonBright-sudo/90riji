# 90天日课 · 打卡

八正道修炼打卡页。基于正见+正思维主题的90天自我觉察工具。

## 使用方式

**打开网页：**
👉 https://elonbright-sudo.github.io/90riji/

手机、电脑、平板都可以用，数据存在浏览器的本地存储里。

**跨设备同步：**
1. 在旧设备打开网页 → 点「📥 导出」→ 下载 JSON 文件
2. 把 JSON 文件传到新设备（AirDrop/微信/邮件等）
3. 在新设备打开网页 → 点「📥 导出」旁边的「📤 导入」→ 选择 JSON 文件

**本地存档（Mac）：**
把导出的 JSON 放到 Mac 上，运行：
```bash
bash /Users/知识库/Elon的第二大脑/90天日课打卡/import-90riji.sh <导出的JSON文件>
```
会自动写入 day1.md ~ day90.md。

## 技术说明

- 纯前端，无后端服务器
- 数据存储在浏览器 localStorage
- GitHub Pages 托管，永久可用
- 两天权归自己，镜子不说话
