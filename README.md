
# I Ching Divination | 周易占卜 | 周易占卜工具

[![GitHub stars](https://img.shields.io/github/stars/deepseek7878/Zhouyi?style=for-the-badge)](https://github.com/deepseek7878/Zhouyi)
[![GitHub forks](https://img.shields.io/github/forks/deepseek7878/Zhouyi?style=for-the-badge)](https://github.com/deepseek7878/Zhouyi)
[![GitHub issues](https://img.shields.io/github/issues/deepseek7878/Zhouyi?style=for-the-badge)](https://github.com/deepseek7878/Zhouyi/issues)
[![GitHub license](https://img.shields.io/github/license/deepseek7878/Zhouyi?style=for-the-badge)](https://github.com/deepseek7878/Zhouyi/blob/main/LICENSE)
[![Release](https://img.shields.io/github/v/release/deepseek7878/Zhouyi?style=for-the-badge)](https://github.com/deepseek7878/Zhouyi/releases)

**I Ching (Zhouyi) divination tool using traditional coin-toss method / 周易传统掷币占卜工具 / 周易傳統擲幣占卜工具**  
Ask your question → Toss 6 coins → Get hexagram interpretation with changing lines / 提出问题 → 掷6次铜钱 → 获取含变爻的卦象解读 / 提出問題 → 擲6次銅錢 → 獲取含變爻的卦象解讀.

## 🎯 一键演示 / Quick Demo / 快速示範

**Step 1: Ask your question / 提出问题 / 提出問題**
"Should I accept this job offer?" / "我应该接受这份工作吗？" / "我應該接受這份工作嗎？"

text

**Step 2: Toss 6 coins (traditional method) / 掷6次铜钱 / 擲6次銅錢**
Result: ☰☰☰☰☷☰ (Qian → Gou)

text

**Step 3: Get interpretation / 获取解读 / 獲取解讀**
本卦: 乾 (Heaven) - 元亨利贞
动爻: 第六爻 "亢龙有悔"
变卦: 姤 (Encountering) - 女壮勿用取女
建议: 时机未到，宜静不宜动

## 📱 💰 获取源码 | Contact


📱 Telegram：@fox_lovemyself
📧 Email：lihongbo9414@gmail.com

👉 联系我获取演示 + 详细报价



## 📱 实时演示截图 / Live Demo Screenshots / 即時示範截圖
<img width="2471" height="1285" alt="屏幕截图 2025-03-15 113242" src="https://github.com/user-attachments/assets/4eaf29e3-5153-4649-b815-19151481f9c4" />
!<img width="1247" height="668" alt="微信图片_20260207202257" src="https://github.com/user-attachments/assets/93f33324-522b-458d-a33b-9eb506c80a40" />
<img width="2539" height="1369" alt="屏幕截图 2025-04-18 194842" src="https://github.com/user-attachments/assets/ea67a6c5-5b62-4c7b-9fc3-535e028b151c" />
<img width="2446" height="1292" alt="屏幕截图 2024-10-29 115251" src="https://github.com/user-attachments/assets/375837a6-f5d4-4543-b768-381fcee4b473" />
<img width="2306" height="1369" alt="屏幕截图 2024-10-29 114720" src="https://github.com/user-attachments/assets/9397cb84-8ca4-418d-a5c6-7acca656e1c1" />
<img width="2540" height="1381" alt="屏幕截图 2024-10-29 114423" src="https://github.com/user-attachments/assets/5324ed8a-e66a-4de3-b917-168234427777" />



---

## 🚀 三步启动 / 3-Step Quick Start / 三步啟動

```bash
# 1. 下载项目
git clone https://github.com/deepseek7878/Zhouyi.git
cd Zhouyi

# 2. 安装依赖
npm install   # Node.js项目
# 或
pip install -r requirements.txt  # Python项目

# 3. 开始占卜
npm start     # 访问 http://localhost:3000
# 或
python main.py
```

**30秒内即可开始占卜！ / Ready in 30 seconds! / 30秒內即可開始占卜！**

---

## ✨ 核心功能 / Key Features / 核心功能

| 功能 / Feature / 功能 | 描述 / Description / 描述 |
|---|---|
| 🎲 **传统掷币法** | 6次铜钱掷法，老阴老阳准确计算 / Traditional 6-coin method / 傳統6次擲幣法 |
| 🔮 **64卦全解读** | 完整卦辞爻辞，王弼译本 / 64 hexagrams complete / 64卦完整解讀 |
| ⚡ **动爻分析** | 本卦→变卦完整演变路径 / Moving lines analysis / 動爻分析 |
| 🌏 **三语支持** | 中/英/繁体完整多语言 / Multi-language support / 三語支援 |
| 💾 **历史记录** | 保存分享你的占卜记录 / Save/share history / 保存分享紀錄 |
| 📱 **响应式设计** | 手机电脑均可使用 / Mobile-friendly / 手機電腦通用 |

---

## 📚 占卜流程 / Divination Process / 占卜流程
清静心神，提出具体问题

点击"开始占卜"，系统自动掷6次铜钱

查看本卦、动爻、变卦完整解读

结合实际情况参考建议

**示例问题 / Example Questions / 範例問題：**
职业: "这份工作适合我吗？"
感情: "我们还有机会吗？"
健康: "我的身体有什么问题？"
学业: "换专业对吗？"

---

## 🏗️ 项目结构 / Project Structure / 專案結構
Zhouyi/
├── src/
│ ├── coins.js # 掷币算法 / Coin toss logic / 擲幣演算法
│ ├── hexagrams.js # 64卦数据 / 64 hexagrams data / 64卦資料
│ ├── lines.js # 爻辞解析 / Line interpretations / 爻辭解析
│ └── interpreter.js # 综合解读 / Full interpretation / 綜合解讀
├── public/ # 前端资源 / Frontend assets / 前端資源
├── docs/ # 详细说明 / Documentation / 詳細說明
└── examples/ # 占卜案例 / Examples / 範例


---

## 🎯 适用场景 / Use Cases / 適用場景

- 🔮 **个人占卜** - 生活决策参考
- 📚 **易经学习** - 64卦爻辞系统学习
- 🌐 **网站集成** - 占卜功能模块
- 📱 **小程序开发** - 移动端占卜服务
- 🎓 **教学演示** - 易经教学工具

---

## ❓ 常见问题 / FAQ / 常見問題

**Q: 占卜准确吗？**  
**A:** 传统智慧指导，非科学预测，结合实际判断

**Q: 如何提问题？**  
**A:** 用具体的是非问题，避免过于宽泛

**Q: 动爻怎么看？**  
**A:** 本卦反映现在，变卦指未来趋势，动爻最重要

**Q: 可以商用吗？**  
**A:** MIT License，完全开源商用友好

**Q: 手机能用吗？**  
**A:** 完美适配手机、平板、电脑

---

## 📦 版本发布 / Releases / 版本發佈

### ⭐ v1.0.0 (最新版)
✅ 传统掷币占卜完整流程  
✅ 64卦全解读（王弼译本）  
✅ 动爻变卦分析  
✅ 三语界面支持  
✅ 响应式设计  

**[下载最新版](https://github.com/deepseek7878/Zhouyi/releases/latest)**

### 🚀 v1.1.0 计划
- 梅花易数支持
- 六爻专业版
- 在线多人占卜
- 卦象可视化

---

## 🤝 贡献指南 / Contributing / 貢獻指南

欢迎贡献！任何帮助完善易经智慧传播的努力都受欢迎！

```bash
1. Fork 项目
2. 创建功能分支 `git checkout -b feature/xxx`
3. 提交代码 `git commit -m "xxx"`
4. 推送并提PR `git push origin feature/xxx`
```

**贡献方向：**
- 新占卜方法
- 更多译本支持
- UI美化
- 移动端优化

---

## 📄 开源许可 / License / 授權
MIT License - 完全开源
个人使用 | 学习研究 | 商业部署 | 二次开发
Copyright (c) 2026 deepseek7878

**[查看完整许可](LICENSE)**

---

## 🌟 相关主题 / Related Topics / 相關主題
#i-ching #iching #zhouyi #周易 #divination #占卜 #易经 #oracle #fortune-telling #chinese-philosophy

---

**⭐ 如果这个工具帮到你，请点亮小⭐ 支持开源易经智慧传播！ / If this helps you, please ⭐ to support open source I Ching wisdom! / 如果這個工具幫到你，請點亮小⭐ 支持開源易經智慧傳播！**

**🙏 愿周易智慧伴你左右，趋吉避凶！ / May I Ching wisdom guide you to good fortune! / 願周易智慧伴你左右，趨吉避凶！**




# Zhouyi 周易；周易源碼，易經源碼，周易排盤，紫微斗數，七政四餘，大六壬，等源碼
这是一套基于js语言开发的经典工具，专为对周易文化感兴趣的技术爱好者准备。本资源集合了八字命理、六爻占卜、奇门遁甲，周易八卦，七政四余源码，四柱八字源码，周易源码，排盘，易经源码，玄学，婚姻，运势源码，星座，紫微斗数，大六壬，算命源码，刑冲关等多种传统预测学的计算与排盘功能。通过简单的部署，您便可以在个人网站或app上实现这些古老智慧的数字化应用。tg：fox_lovemyself

特性概述
全面的命理工具：涵盖八字（四柱命盘）、六爻（摇卦预测）和奇门遁甲（时家奇门），紫微斗數，七政四余，大六壬，神煞，四柱八字，形蟲關係满足不同用户对易经应用的需求。
经典js实现：代码采用经典的js编写，适合初級开发者快速上手。
即传即用：将源码上传至支持js环境的Web服务器后，无需复杂配置即可开始使用，适合快速搭建易学交流平台。
教育与研究价值：对于学习传统文化结合的同学及研究人员，提供了宝贵的实践材料。
