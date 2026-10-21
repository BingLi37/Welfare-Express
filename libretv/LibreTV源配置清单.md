# LibreTV 源合集

> 为 [LibreTV](https://github.com/LibreSpark/LibreTV)（免费在线影视聚合站）整理的源订阅合集：**75 个点播源 + 3 个直播源**，填入订阅地址即可一键导入，自动去重、自动探活、每 24 小时静默刷新。

## ✨ 快速使用

1. 部署并打开 LibreTV（`http://localhost:8080`，输入访问密码）
2. 进入 **设置 → 源管理 → 数据源订阅**
3. 粘贴本仓库 `LibreTV-sources.json` 的 raw 链接，点击 **订阅**
4. 点播源自动勾选、直播源自动启用，即刻可用

**订阅地址**（任选其一；国内访问建议优先使用备选线路）：

```text
# ① 主地址（GitHub raw）
https://raw.githubusercontent.com/BingLi37/Welfare-Express/main/libretv/LibreTV-sources.json

# ② 国内备选（jsdelivr Fastly 节点）
https://fastly.jsdelivr.net/gh/BingLi37/Welfare-Express@main/libretv/LibreTV-sources.json

# ③ 国内备选（gh-proxy 加速代理）
https://gh-proxy.com/https://raw.githubusercontent.com/BingLi37/Welfare-Express/main/libretv/LibreTV-sources.json
```

也可以直接填任意 TVBOX 配置地址或本合集内列出的其他订阅（LibreTV 会自动识别格式并导入其中可用的源）。

## 📦 点播源（75 个）

| # | 源名称 | 接口地址 |
|---|--------|----------|
| 1 | 红牛资源 | `http://hongniuzy2.com/api.php/provide/vod/from/hnm3u8` |
| 2 | 量子资源 | `http://cj.lziapi.com/api.php/provide/vod/from/lzm3u8` |
| 3 | 开放电影 | `http://vod-demo.onrender.com/pubdovod.php` |
| 4 | 优质资源库 | `http://api.1080zyku.com/inc/api.php/provide/vod` |
| 5 | 39影视 | `http://39kan.com/api.php/provide/vod` |
| 6 | 天堂资源 | `http://vipmv.cc/api.php/provide/vod` |
| 7 | 乐活影视 | `http://lehootv.com/api.php/provide/vod` |
| 8 | 唐人街 | `http://tangrenjie.tv/api.php/provide/vod` |
| 9 | 酷点资源 | `http://api.kuapi.cc/api.php/provide/vod` |
| 10 | 卧龙资源 | `http://collect.wolongzyw.com/api.php/provide/vod` |
| 11 | 酷点资源2 | `http://kudian10.com/api.php/provide/vod` |
| 12 | 唐人街xm | `http://tangrenjie.tv/api.php/provide/vod/at/xm` |
| 13 | 森林资源 | `http://slapibf.com/api.php/provide/vod` |
| 14 | 影库资源网 | `http://api.ykapi.net/api.php/provide/vod` |
| 15 | 快车资源 | `http://caiji.kczyapi.com/api.php/provide/vod/from/kcm3u8` |
| 16 | 探探资源 | `http://apittzy.com/api.php/provide/vod` |
| 17 | 闪电资源 | `http://sdzyapi.com/api.php/provide/vod/from/sdm3u8` |
| 18 | 金鹰资源 | `http://jyzyapi.com/provide/vod/from/jinyingm3u8` |
| 19 | 光速资源 | `http://api.guangsuapi.com/api.php/provide/vod/from/gsm3u8` |
| 20 | 奥斯卡资源网 | `http://aosikazy.com/api.php/provide/vod` |
| 21 | 老鸭资源采集 | `http://api.apilyzy.com/api.php/provide/vod` |
| 22 | U酷资源 | `http://api.ukuapi.com/api.php/provide/vod` |
| 23 | 北斗星资源 | `http://m3u8.bdxzyapi.com/api.php/provide/vod` |
| 24 | 樱花资源网 | `http://m3u8.apiyhzy.com/api.php/provide/vod` |
| 25 | 闪电资源2 | `http://sdzyapi.com/api.php/provide/vod` |
| 26 | 飞速资源 | `http://feisuzy.com/api.php/provide/vod` |
| 27 | 快播资源 | `http://www.kuaibozy.com/api.php/provide/vod` |
| 28 | 百度资源 | `http://api.apibdzy.com/api.php/provide/vod` |
| 29 | 艾旦影视 | `http://lovedan.net/api.php/provide/vod` |
| 30 | 飘花电影 | `http://www.zzrhgg.com/api.php/provide/vod` |
| 31 | 网民电影 | `http://prinevillesda.org/api.php/provide/vod` |
| 32 | 丝袜资源 | `http://siwazyw.cc/api.php/provide/vod` |
| 33 | 天空资源 | `http://m3u8.tiankongapi.com/api.php/provide/vod/from/tkm3u8` |
| 34 | 海外看资源 | `http://haiwaikan.com/api.php/provide/vod` |
| 35 | 海外看点播 | `https://haiwaikan.com/api.php/provide/vod` |
| 36 | 360点播 | `https://360zy.com/api.php/provide/vod` |
| 37 | 黑木耳点播 | `https://www.heimuer.tv/api.php/provide/vod` |
| 38 | 刺桐点播 | `http://ys9.cttv.vip/api.php/provide/vod` |
| 39 | 官网点播 | `http://gwcms.cttv.vip/api.php/provide/vod` |
| 40 | 业余点播 | `https://yyff.540734621.xyz/api.php/provide/vod` |
| 41 | 华为吧点播 | `https://hw8.live/api.php/provide/vod` |
| 42 | 小黄人点播 | `https://iqyi.xiaohuangrentv.com/api.php/provide/vod` |
| 43 | 牛牛点播 | `https://api.niuniuzy.me/api.php/provide/vod` |
| 44 | 丫丫点播 | `https://cj.yayazy.net/api.php/provide/vod` |
| 45 | U酷点播 | `https://api.ukuapi.com/api.php/provide/vod` |
| 46 | 豪华点播 | `https://hhzyapi.com/api.php/provide/vod` |
| 47 | 极速点播 | `https://jszyapi.com/api.php/provide/vod` |
| 48 | 四九点播 | `https://49zyw.com/api.php/provide/vod` |
| 49 | 索尼点播 | `https://suoniapi.com/api.php/provide/vod` |
| 50 | ikun点播 | `https://ikunzyapi.com/api.php/provide/vod` |
| 51 | 非凡点播 | `http://cj.ffzyapi.com/api.php/provide/vod` |
| 52 | 量子点播 | `https://cj.lziapi.com/api.php/provide/vod` |
| 53 | 暴风点播 | `https://bfzyapi.com/api.php/provide/vod` |
| 54 | 红牛点播 | `https://www.hongniuzy2.com/api.php/provide/vod` |
| 55 | 飞速点播 | `https://www.feisuzyapi.com/api.php/provide/vod` |
| 56 | 快看点播 | `https://www.kuaikan-api.com/api.php/provide/vod` |
| 57 | 熊掌点播 | `https://xzcjz.com/api.php/provide/vod` |
| 58 | 快车点播 | `https://caiji.kczyapi.com/api.php/provide/vod/from/kcm3u8` |
| 59 | 樱花点播 | `https://m3u8.apiyhzy.com/api.php/provide/vod` |
| 60 | 卧龙点播 | `https://collect.wolongzyw.com/api.php/provide/vod` |
| 61 | 飘花点播 | `http://www.ahjiuman.com/api.php/provide/vod/at/json` |
| 62 | 天翼点播 | `https://www.911ysw.top/tianyi.php/provide/vod` |
| 63 | 虎牙点播 | `https://www.huyaapi.com/api.php/provide/vod` |
| 64 | 百度点播 | `https://api.apibdzy.com/api.php/provide/vod` |
| 65 | 飘零点播 | `https://p2100.net/api.php/provide/vod` |
| 66 | 无尽点播 | `https://api.wujinapi.com/api.php/provide/vod` |
| 67 | 速博点播 | `https://subocaiji.com/api.php/provide/vod` |
| 68 | 魔都点播 | `https://caiji.moduapi.cc/api.php/provide/vod` |
| 69 | 最大点播 | `http://zuidazy.me/api.php/provide/vod` |
| 70 | 奇虎点播 | `https://caiji.qhzyapi.com/api.php/provide/vod` |
| 71 | 新浪点播 | `https://api.xinlangapi.com/xinlangapi.php/provide/vod` |
| 72 | 快云点播 | `https://www.kuaiyunzy.com/api.php/provide/vod` |
| 73 | 非凡采集站 | `http://ffzy5.tv/api.php/provide/vod` |
| 74 | 量子采集站 | `http://lzizy.net/api.php/provide/vod` |
| 75 | 索尼采集站 | `https://suonizy.net/api.php/provide/vod` |

## 📺 直播源（3 个）

| # | 直播源名 | M3U 地址 | EPG 节目单 |
|---|----------|----------|------------|
| 1 | 直播电视IPV4 | `https://live.zbds.top/tv/iptv4.m3u` | `http://epg.51zmt.top:8000/e.xml` |
| 2 | IPTV默认源 | `https://raw.githubusercontent.com/Guovin/iptv-api/gd/output/result.m3u` | `https://gh-proxy.com/https://raw.githubusercontent.com/Guovin/iptv-api/refs/heads/master/output/epg/epg.gz` |
| 3 | Jesse-Lam IPTV | `https://raw.githubusercontent.com/Jesse-Lam/TVBOX/main/IPTV.m3u` | — |

## 🔗 推荐附加订阅（9 个，可选）

以下为第三方维护的源配置，可在同一页面逐个订阅（LibreTV 自动导入其中可用的 AppleCMS 点播源与 M3U 直播源，Spider/JS 类源自动跳过）：

| # | 订阅名 | 地址 | 实测导入量 |
|---|--------|------|-----------|
| 1 | 哈基米 | `https://17264.kstore.space/哈基米.png` | 18 点播 + 3 直播 |
| 2 | 分享 | `https://raw.githubusercontent.com/maoystv/6/main/000.json` | 20 点播 + 3 直播 |
| 3 | 真心 | `https://www.252035.xyz/z/FongMi.json` | 4 点播 |
| 4 | dxawi | `https://dxawi.github.io/0/0.json` | 3 点播 + 2 直播 |
| 5 | 东篱线路 | `https://raw.githubusercontent.com/chitue/dongliTV/main/api.json` | 4 点播 + 9 直播 |
| 6 | foxmurphy点播合集 | `https://raw.githubusercontent.com/foxmurphy/libretv-subscribe/main/libretv_sources.json` | 27 点播 |
| 7 | haojun双源合集 | `https://raw.githubusercontent.com/haojun19980728-prog/libretv-source-list/main/libretv-sources.json` | 39 点播 + 2 直播 |
| 8 | wholove99 | `https://raw.githubusercontent.com/wholove99/tvbox/main/box.json` | 5 点播 |
| 9 | 老刘备 | `https://raw.liucn.cc/box/m.json` | 14 点播 |

## 🔄 更新与维护

- 第三方接口随时可能失效，属于正常现象；LibreTV 会自动探活，对连续失败的源按阶梯时长自动停用（30 分钟 → 24 小时 → 长期），可在「设置 → 源管理」一键恢复
- 需要增删源时，建议 **fork 本仓库** 后修改 `LibreTV-sources.json`，或在 LibreTV 内「导出数据源 → 发布为链接」快速生成新的订阅地址
- 点播源最多 100 个、直播源最多 50 个，超出部分会截断

## ⚠️ 免责声明

- 所有源均来自公开接口与第三方分享，仅用于技术学习与交流，请勿商用
- 本项目不存储、不制作任何视频内容，内容的合法性由对应数据源负责
- 部分源可能包含成人内容，请保持设置中的「成人内容过滤」开启（默认开启）
- 接口版权归原作者所有，如有冒犯请联系删除
