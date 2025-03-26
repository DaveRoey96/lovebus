# 🚍 情缘巴士 LoveBus · 缘分的移动站台

![LoveBanner](https://user-images.githubusercontent.com/xxx/xxx.png) 
*(可替换为项目封面图，建议使用巴士+爱心元素的插画风格)*

> 「在城市的喧嚣中，为相遇按下快捷键」  
> 一款基于实时定位的浪漫社交应用，让每一次乘车都成为邂逅的可能

## ✨ 功能亮点
- **巴士缘分雷达**  
  实时显示同车乘客的匿名社交档案，匹配共同兴趣
- **心动滑动机制**  
  👉👈 双盲匹配，同时点赞即可解锁聊天
- **目的地社交**  
  预测下车点，推荐沿线共同目的地的社交活动
- **时光胶囊信件**  
  给常坐同一班次的TA留下加密留言
- **安全护航模式**  
  公安系统联网验证 + 紧急联系人自动分享行程

## 🛠️ 技术栈
| 领域        | 技术选型                                                                 |
|-------------|--------------------------------------------------------------------------|
| **前端**    | Flutter 3.0 (支持iOS/Android/Web三端)                                    |
| **后端**    | Go + Gin (高性能API) + gRPC (微服务通信)                                 |
| **数据库**  | PostgreSQL (关系型) + Redis (实时位置缓存) + Neo4j (社交图谱)            |
| **GIS**     | 高德地图API (实时位置追踪) + Turf.js (地理围栏计算)                      |
| **安全**    | JWT + 国密SM4加密 + 阿里云人机验证                                       |
| **DevOps**  | Docker + Kubernetes + GitHub Actions (CI/CD)                             |

## 🚀 快速体验
1. **开发模式运行** (需安装Flutter SDK)
   ```bash
   git clone https://github.com/yourname/lovebus.git
   cd lovebus/app
   flutter pub get
   flutter run --profile
📜 特别声明
位置数据仅加密存储24小时
采用「阅后即焚」聊天机制
已通过等保2.0二级认证
拒绝一切形式的数据买卖


💌 联系我们
商务合作：bus@lovebus.dating

安全漏洞报告：security@lovebus.dating

请使用PGP加密通信
