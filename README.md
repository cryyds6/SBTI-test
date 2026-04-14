# SBTI-test

> 一个基于 SBTI 人格测试的静态网页项目

## 项目介绍

本项目是一个基于 **SBTI（可能是某种人格测试系统）** 的在线测试页面，包含多个人格类型的图片和描述。

**原项目地址：** https://github.com/UnluckyNinja/SBTI-test

## 当前版本（cryyds6 修改版）

### 修改内容

- ✅ **回退到初始版本**（commit: d34532f - "实现单题作答流模式"）
  - 该版本为原项目初始提交之一，包含完整的单题作答流模式实现
  - 移除了后续版本中可能存在的争议性内容

- ✅ **补全 image 文件夹**
  - 从原项目完整仓库中恢复全部 **27 张人格图片**
  - 图片列表：ATM-er, BOSS, CTRL, DEAD, Dior-s, DRUNK, FAKE, FUCK, GOGO, HHHH, IMFW, IMSB, JOKE-R, LOVE-R, MALO, MONK, MUM, OH-NO, OJBK, POOR, SEXY, SHIT, SOLO, THAN-K, THIN-K, WOC, ZZZZ

- ✅ **精简"关于本镜像"页面**
  - 去除原项目长篇声明，保留核心信息
  - 显示原项目地址和当前改版作者
  - 添加 Cloudflare Pages 测试部署链接

### 测试部署

**Cloudflare Pages 测试地址：** https://sbti-test-3n1.pages.dev/

### 技术栈

- 纯 HTML/CSS/JavaScript（单页应用）
- 无后端，纯前端部署
- 图片本地托管

### 部署方式

本项目通过 **Cloudflare Pages** 自动部署：
- 代码推送至 GitHub `main` 分支后，Cloudflare 自动拉取并构建
- 支持自定义域名绑定

---

**注意：** 本项目仅供学习参考使用。人格测试结果不作为专业心理评估依据。
