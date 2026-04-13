# 📖 每日读经云端推送

通过 GitHub Actions 实现每天自动推送读经计划到微信

## 📋 部署步骤

### 1. 创建 GitHub 仓库
1. 访问 https://github.com/new
2. 仓库名称：`daily-bible-reading`（或其他名称）
3. 设为 **Public**（公开仓库）
4. 点击 **Create repository**

### 2. 上传文件到仓库
将以下文件上传到仓库：
- `.github/workflows/daily-bible-reading.yml`
- `bible-reading.py`

### 3. 配置 Server酱 SendKey
1. 进入仓库 → **Settings** → **Secrets and variables** → **Actions**
2. 点击 **New repository secret**
3. Name: `SENDKEY`
4. Value: `SCT337074TlJOKZPI5ZoFzuxp4rSafHCpV`
5. 点击 **Add secret**

### 4. 测试运行
1. 进入仓库 → **Actions** 标签
2. 点击左侧 **每日读经推送**
3. 点击 **Run workflow** → **Run workflow** 手动触发测试
4. 检查微信是否收到推送

## ⏰ 推送时间
- **UTC 23:00** = **北京时间 07:00**
- 每天自动执行，无需电脑开机

## 📅 读经计划
- 起始日期：2026年4月13日
- 每天7章，自动补足
- 第1天：约拿书(4章) + 阿摩斯书(1-3章)

## 🎯 完成状态
- 总计：108天完成66卷
- 当前进度：约珥书已完成

---

*愿神赐福你的读经之旅！🙏*
