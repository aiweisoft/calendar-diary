# 📔 日历日记

一个简单的网页版日记应用，支持按日历记录每日心情。

## 功能特点

- 📅 日历视图浏览，支持定位到今天
- ✍️ 同一天可记录多条日记，每条带时间戳
- 📋 日记列表管理，支持按日期/时间查看
- 💾 数据本地存储
- ☁️ 支持 GitHub Gist 云端同步，多设备同步
- 🔄 GitHub Actions 自动部署

## 在线访问

访问地址：https://aiweisoft.github.io/calendar-diary

## 使用说明

### 写日记
1. 点击日历上的日期选择要写日记的日子
2. 在文本框中输入日记内容
3. 点击"保存日记"按钮保存
4. 点击"新建日记"可继续添加当天日记

### 日记列表
1. 点击"日记列表"标签查看所有日记
2. 点击任意日记可查看和编辑
3. 支持删除日记

### 云端同步
1. 点击右上角"同步"按钮
2. 首次需要设置 GitHub Token：
   - 创建 Token：https://github.com/settings/tokens/new?scopes=gist
   - 勾选 **gist** 权限
   - 复制生成的 Token 填入
3. 同步会自动创建 Gist，后续点击同步即可

## 技术栈

- HTML + CSS + JavaScript
- GitHub Gist 数据存储
- GitHub Pages 部署
- GitHub Actions 自动部署
