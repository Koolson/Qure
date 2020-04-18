# Qure<br>
![Image text](https://raw.githubusercontent.com/Koolson/Qure/master/Other/Qure_Logo.png)
<br>

## 简介
Qure 是一套专为 [Quantumult X](https://github.com/crossutility/Quantumult-X/) 内策略组而精心设计的图标组。在这里你可以订阅、下载并更新它们。<br>

## 使用说明
### 方式对比
| 方式 | 添加图标 | 更新图标 | 图标维护 | 获取及时性 | 操作便利性 | 
| :---: | :---: | :---: | :---: | :---: | :---: |
| 远程图标 | 编辑配置 | 清理缓存 | 图标作者 | ✅ | ✅ |
| 本地图标 | 编辑配置+文件操作 | 文件操作 | 用户本人 | ❌ | ❌|

### 方式一：远程图标<br>
*跨设备同步策略组图标，及时获取图标更新*<br>
*该操作以 Quantumult X v1.0.8-build249 为例*<br>
1. 在 [常规图标预览](https://github.com/Koolson/Qure#%E6%95%88%E6%9E%9C%E5%9B%BE%E9%A2%84%E8%A7%88)、[归档图标预览](https://raw.githubusercontent.com/Koolson/Qure/master/Other/Qure_Preview_Archived.png) 或 [IconSet 页面](https://github.com/Koolson/Qure/tree/master/IconSet) 中找到需要的策略组图标并记下**图标名称**；<br>
2. 在 Quantumult X 的“配置文件-编辑”中找到[policy]下的策略组字段，并在该策略组的最后一个节点后方加上：<br>
`img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/图标名称.png`<br>
例如：<br>
`static=Hong Kong, 🇭🇰01, img-url=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Hong_Kong.png`<br>

```ruby
注意：此处“img”前的英文逗号和空格以及“Hong_Kong.png”图标名称中的下划短横线和字母大小写
```

3. 重启 Quantumult X 即可见到效果。<br>

><font color=red>更新方法：当远程图标更新时，请手动清理本地图标缓存(打开“文件”应用，依次进入“**我的 iPhone 或 iCloud Drive-Quantumult X-Images**”，删除Images文件夹内所有缓存文件)，并重启 Quantumult X，远程图标会重新下载并生效。</font>

[查看大图](https://raw.githubusercontent.com/Koolson/Qure/master/Other/Remote_Icon.png)<br>
![Image text](https://raw.githubusercontent.com/Koolson/Qure/master/Other/Remote_Icon.png)

### 方式二：本地图标<br>
*不支持多设备同步图标；图标更新时，需要手动下载图标并进行本地替换操作*<br>
*该操作以 Quantumult X v1.0.0-build91 为例*<br>

1. 打开"文件"应用后，依次进入“我的 iPhone 或 iCloud Drive→Quantumult X→Images”；<br>
2. 将**个人设定**的策略组名称 **同名的.png** 图标文件(.png图标文件可在 [IconSet 页面](https://github.com/Koolson/Qure/tree/master/IconSet)根据个人需求自行下载)粘贴到 Images 文件夹内，重启 Quantumult X 即可见到效果。<br>
 [查看大图](https://raw.githubusercontent.com/Koolson/Qure/master/Other/Local_Icon.png)<br>
![Image text](https://raw.githubusercontent.com/Koolson/Qure/master/Other/Local_Icon.png)

## 补充说明
1. 转载请注明出处，谢谢！<br>
2. 归档图标：图标默认不展示，但仍支持订阅；具体可查看 [归档图标预览](https://raw.githubusercontent.com/Koolson/Qure/master/Other/Qure_Preview_Archived.png) 及归档图标名称；<br>
3. 需要新增策略图标，请提 Issues 或 Telegram 中说明图标名称并附上相关图标资源链接；<br>
4. ~~推荐使用 Hua姐的 [神机规则](https://github.com/ConnersHua/Profiles/blob/master/README.md) - [Filter Remote](https://github.com/ConnersHua/Profiles/tree/master/Quantumult/X) 与 Qure 搭配以强化 Quantumult X 使用体验；~~<br>
</details>

## 免责声明
1. Qure 项目内所涉及图标、LOGO 仅为资源共享、学习参考之目的，不保证其合法性、正当性、准确性；切勿使用 Qure 项目做任何商业用途或牟利；<br>
2. 遵循避风港原则，若有图片和内容侵权，请在 Issues 告知，核实后删除，其版权均归原作者及其网站所有；<br>
3. 本人不对任何内容承担任何责任，包括但不限于任何内容错误导致的任何损失、损害；<br>
4. 其它人通过任何方式登陆本网站或直接、间接使用 Qure 项目相关资源，均应仔细阅读本声明，一旦使用、转载 Qure 项目任何相关教程或资源，即被视为您已接受此免责声明。<br>
</details>

## 更新日志
<details>
<summary><strong>所有日志</strong></summary><br>
<strong>v2.7</strong><br>
2020-4-12<br>
*所有图标名称均可在效果图中获知；<br>
1. 图标新增：direct.png、proxy.png、reject.png、TestFlight.png、App_Store.png、iCloud.png、Apple_Music.png、AmyTelecom.png、CCCAT_C.png、CCCAT.png、JIYOU.png、CONAIR.png、CrossWall.png、NyanCat.png、Airport.png、Server.png、SS_Letter.png、SS.png、SSR_Letter.png、SSR.png、Trojan_Letter.png、Trojan.png、VMess_Letter.png、VMess.png、MY.png、Malaysia.png、IEPL.png<br>
2. 图标优化：Bookpedia.png、Download.png、Quantumult_X.png、VMess_Letter.png<br>
3. 图标更名：ITV_Hub.png、x0.1.png、x0.3.png、x0.5.png、x0.png、x1.png、x2.png、x3.png<br>
4. 图标归档：＊0.png、＊0.1.png、＊0.3.png、＊0.5.png、＊1.png、＊2.png、＊3.png、Direct.png、Proxy.png、Reject.png5. 图标归档：＊0.png、＊0.1.png、＊0.3.png、＊0.5.png、＊1.png、＊2.png、＊3.png、Direct.png、Proxy.png、Reject.png<br>
5. 图标删除：ITV Hub.png<br>
<br>

v2.6<br>
2020-2-27<br>
1.图标新增：5iTV.png、Flamingo.png、Want_Want_Letter.png、Want_Want.png、Apple_Update.png、StreamingSE.png、Streaming.png、Drill.png、Cydia.png、Puzzle.png、Bookpedia.png<br>


v2.5<br>
2020-1-5<br>
1.图标新增：Quantumult_X.png、Qure.png、China_Map.png、United_States_Map.png、Pig.png、Mouse.png<br>


v2.4<br>
2019-12-28<br>
1.图标新增：Google_Opinion_Rewards.png、WeTV_Letter.png、WeTV.png<br>
2.图标优化：EU.png<br>

v2.3<br>
2019-12-3<br>
1.图标新增：Apple_TV.png、Apple_TV_Plus.png、Ingress.png、EU.png、GT.png、GIA.png、CHT.png、aaex.png<br>

v2.2<br>
2019-11-12<br>
1.图标新增：JOOX_Letter.png、GlobalMedia.png、Game.png、VIP.png<br>
2.图标优化：Static.png、HKMTMedia.png、Prime_Video.png、Dler.png、JOOX.png、YTOO.png、N3RO.png<br>

v2.1<br>
2019-11-5<br>
1.图标新增：niconico.png、niconico_Letter.png、Germany.png<br>
2.图标优化：deezer_Letter.png<br>
3.图标更名：Deezer→deezer.png、Deezer_Letter.png→deezer_Letter.png<br>

v2.0.1<br>
2019-11-2<br>
1.图标新增：Rocket.png<br>
2.图标优化：Download.png<br>

v2.0<br>
2019-11-2<br>
Quantumult X最美简雅风策略组图标现以Qure全新呈现<br>
图标名录：<br>
**Default**：Direct.png、Proxy.png、Reject.png、Static.png、Round_Robin.png、SSID.png、Available.png<br>
**Common**：Back.png、Final.png、ForeignMedia.png、DomesticMedia.png、HKMTMedia.png、Domestic.png、Global.png、Auto.png<br>
**Inhibition**：Hijacking.png、AdWhite.png、AdBlack.png、Advertising.png<br>
**Service**：Cloudflare.png、Apple.png、Google.png、Mail.png、Microsoft.png、Windows.png、Yahoo.png、Yahoo_Letter.png<br>
**App**：Telegram.png、Telegram_X.png、Speedtest.png、Spark.png、OneDrive.png、PayPal.png、Apple_News.png、Twitter.png、Facebook.png、Instagram.png<br>
**Other**：Star.png、Heart.png、Download.png、Bot.png、Loop.png、Lab.png、Bypass.png、Magic.png、Daily.png<br>
**Area**：Russia.png、Singapore.png、United_States.png、China.png、Japan.png、Korea.png、Hong_Kong.png、Macao.png、United_Kingdom.png、United_Nations.png、Canada.png、Turkey.png、UK.png、CN.png、HK.png、MO.png、US.png、SG.png、JP.png、RU.png、KR.png、TR.png、CA.png、IN.png、UN.png、DE.png、FI.png、TW.png<br>
**Media**：YouTube.png、YouTube_Letter.png、bilibili.png、myTV_SUPER.png、PBS.png、My5.png、encoreTVB.png、LineTV_Letter.png、LineTV.png、LiTV.png、ESPN+.png、Prime_Video.png、Deezer_Letter.png、ITV Hub.png、JOOX.png、DAZN.png、Deezer.png、Bahamut.png、All4.png、AbemaTV_Letter.png、AbemaTV.png、Netease_Music_Unlock.png、Netease_Music.png、Pandora.png、Disney+.png、KKBOX.png、HBO.png、KKTV.png、BBC_iPlayer.png、FOX.png、YouTube_Music.png、TIDAL.png、ViuTV.png、Vimeo.png、Spotify.png、Pornhub.png、iQIYI&bilibili.png、Netflix.png、iQIYI.png、Netflix_Letter.png、TikTok.png、Hulu.png、TVB.png、Twitch.png<br>
**Server**：IPLC.png、BGP.png、CN2_GIA.png、Oracle.png、BBTEC.png、DMIT.png、CN2_GT.png、SoftBank_Letter.png、SoftBank.png、CN2.png、KT.png、IIJ.png、SK.png、HiNet.png、NTT.png、WTT.png、Apol.png、PCCW.png、HKT.png、CTM.png、HGC.png、Tencent_Cloud.png、HKBN.png、CMI.png、Azure.png、Alibaba_Cloud.png、AWS.png、GCP.png、Baidu_Cloud.png、＊0.png、＊0.1.png、＊0.3.png、＊0.5.png、＊1.png、＊2.png、＊3.png<br>
**Archived**：Dler.png、rix.png、N3RO.png、YoYu.png、MAYING.png、Nexitally.png、BosLife.png、BosLife_Letter.png、YTOO_Letter.png、YTOO.png、Taiwan.png<br>
</details>

## 效果图预览
[查看大图](https://raw.githubusercontent.com/Koolson/Qure/master/Other/Qure_Preview_All.png)<br>
![Image text](https://raw.githubusercontent.com/Koolson/Qure/master/Other/Qure_Preview_All.png)
