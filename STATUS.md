<a href="#readme">
    <img src="https://img.vim-cn.com/db/018fac69e39167b5a6f692dfe5b715eccf2960.jpg" alt="图裂了😂" title="OpenWrt-DIY" align="right" height="180" />
</a>

[OpenWrt DIY — 多设备固件云编译](https://jq.qq.com/?_wv=1027&k=9Sh2iNhT)
==============================================================================================================

[![](https://img.shields.io/badge/-目录:-696969.svg)](#readme) [![](https://img.shields.io/badge/-固件下载-FFFFFF.svg)](#固件下载-) [![](https://img.shields.io/badge/-基本介绍-FFFFFF.svg)](#基本介绍-) [![](https://img.shields.io/badge/-近期更新-FFFFFF.svg)](#近期更新-) [![](https://img.shields.io/badge/-注意事项-FFFFFF.svg)](#注意事项-) [![](https://img.shields.io/badge/-小贴士-FFFFFF.svg)](#小贴士-) [![](https://img.shields.io/badge/-捐助-FFFFFF.svg)](#捐助-) [![](https://img.shields.io/badge/-鸣谢-FFFFFF.svg)](#鸣谢-)

请 `耐心认真阅读完毕` 本页面，本页面包含如何提升固件下载及使用体验的内容。

如果您未阅读完本页面，可能会遇到 `固件下载问题` ，若遇到问题，请 `返回此页面，认真完整阅读一遍`~

## 固件下载 [![](https://img.shields.io/badge/-支持设备、编译状态及固件下载-FFFFFF.svg)](#固件下载-)
<details>
 <summary><b>&nbsp;&nbsp;&nbsp; X86  设备编译状态及固件下载</b></summary>
    
<br/>
 
点击下表中 [![](https://img.shields.io/badge/设备-passing-32CD32.svg)](https://github.com/zhaocz086/lede_lean/actions) 即可跳转到该设备固件下载页面
|   序号    |     X86设备  |   X86设备编译状态及下载链接 |   插件配置   | 备注说明   |
| :-----------------: | :-------------: |:-----------------: | :-----------------: |  :-----------------: | 
| 1 |   [![](https://img.shields.io/badge/OpenWrt-x86_(64位)-FFFFFF.svg)](https://github.com/zhaocz086/lede_lean/blob/master/.github/workflows/x86_64.yml)    | [![](https://github.com/zhaocz086/lede_lean/workflows/Build%20X86(64bit)%20OpenWrt/badge.svg)](https://github.com/zhaocz086/lede_lean/blob/master/.github/workflows/x86_64.yml) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/zhaocz086/lede_lean/blob/master/diy/config/X86/x86-extra.config) |  |  
| 2 |    [![](https://img.shields.io/badge/OpenWrt-x86_(32位)-FFFFFF.svg)](https://github.com/zhaocz086/lede_lean/blob/main/.github/workflows/x86.yml)     |[![](https://github.com/zhaocz086/lede_lean/workflows/Build%20X86(32bit)%20OpenWrt/badge.svg)](https://github.com/zhaocz086/lede_lean/actions/workflows/x86.yml) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/zhaocz086/lede_lean/blob/main/config/X86/x86-extra.config) | | 

**提示：**[![](https://img.shields.io/badge/设备-passing-32CD32.svg)](https://github.com/zhaocz086/lede_lean/actions) 标志为正常，[![](https://img.shields.io/badge/设备-failing-DC143C.svg)](https://github.com/zhaocz086/lede_lean/actions) 或 [![](https://img.shields.io/badge/设备-no_status-A9A9A9.svg)](https://github.com/zhaocz086/lede_lean/actions) 不代表所有编译均失败。请点击 [![](https://img.shields.io/badge/设备-状态-32CD32.svg)](https://github.com/zhaocz086/lede_lean/actions) 到 **Actions** 进一步查看。

</details>

<details>
 <summary><b>&nbsp;&nbsp;&nbsp; ARM 设备编译状态及固件下载</b></summary>
    
<br/>
 
点击下表中 [![](https://img.shields.io/badge/设备-passing-32CD32.svg)](https://github.com/zhaocz086/lede_lean/actions) 即可跳转到该设备固件下载页面
|    序号   |     ARM设备    |   ARM设备编译状态及下载链接 |   插件配置   | 备注说明   |
| :-----------------: | :-------------: |:-----------------: | :-----------------: |  :-----------------: | 
| 1 |       [![](https://img.shields.io/badge/OpenWrt-N1_盒子-FFFFFF.svg)](https://github.com/zhaocz086/lede_lean/blob/main/.github/workflows/N1.yml)         |[![](https://github.com/zhaocz086/lede_lean/workflows/Build%20PHICOMM%20N1%20OpenWrt/badge.svg)](https://github.com/zhaocz086/lede_lean/actions/workflows/N1.yml) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/zhaocz086/lede_lean/blob/main/config/ARM/arm-mini-extra.config)  | | 
| 2 |    [![](https://img.shields.io/badge/OpenWrt-树莓派_3B/3B+-FFFFFF.svg)](https://github.com/zhaocz086/lede_lean/blob/main/.github/workflows/raspberrypi3.yml)   | [![](https://github.com/zhaocz086/lede_lean/workflows/Build%20RaspBerryPi3%20OpenWrt/badge.svg)](https://github.com/zhaocz086/lede_lean/actions/workflows/raspberrypi3.yml) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/zhaocz086/lede_lean/blob/main/config/ARM/arm-extra.config) | 含 USB 网卡驱动 |
| 3 |    [![](https://img.shields.io/badge/OpenWrt-树莓派_4B-FFFFFF.svg)](https://github.com/zhaocz086/lede_lean/blob/main/.github/workflows/raspberrypi4.yml)    | [![](https://github.com/zhaocz086/lede_lean/workflows/Build%20RaspBerryPi4%20OpenWrt/badge.svg)](https://github.com/zhaocz086/lede_lean/actions/workflows/raspberrypi4.yml)  |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/zhaocz086/lede_lean/blob/main/config/ARM/arm-extra.config)  | 含 USB 网卡驱动 |
|4|      [![](https://img.shields.io/badge/OpenWrt-NanoPi_R2S-FFFFFF.svg)](https://github.com/zhaocz086/lede_lean/blob/main/.github/workflows/r2s.yml)     |  [![](https://github.com/zhaocz086/lede_lean/workflows/Build%20NanoPi%20R2S%20OpenWrt/badge.svg)](https://github.com/zhaocz086/lede_lean/actions/workflows/r2s.yml)  |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/zhaocz086/lede_lean/blob/main/config/ARM/arm-extra.config)  | ZIP 解压后刷写 |
| 5|      [![](https://img.shields.io/badge/OpenWrt-NanoPi_R4S-FFFFFF.svg)](https://github.com/zhaocz086/lede_lean/blob/main/.github/workflows/r4s.yml)|  [![](https://github.com/zhaocz086/lede_lean/workflows/Build%20NanoPi%20R4S%20OpenWrt/badge.svg)](https://github.com/zhaocz086/lede_lean/actions/workflows/r4s.yml) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/zhaocz086/lede_lean/blob/main/config/ARM/arm-extra.config)  | ZIP 解压后刷写 |
| 6|     [![](https://img.shields.io/badge/OpenWrt-Amlogic_S905X3-FFFFFF.svg)](https://github.com/zhaocz086/lede_lean/blob/main/.github/workflows/S905x3.yml)   | [![](https://github.com/zhaocz086/lede_lean/workflows/Build%20Amlogic%20S905X3%20OpenWrt/badge.svg)](https://github.com/zhaocz086/lede_lean/actions/workflows/S905x3.yml) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/zhaocz086/lede_lean/blob/main/config/ARM/arm-extra.config) |   |
| 7|     [![](https://img.shields.io/badge/OpenWrt-香橙派_Zero_Plus-FFFFFF.svg)](https://github.com/zhaocz086/lede_lean/blob/main/.github/workflows/opzp.yml)   | [![](https://github.com/zhaocz086/lede_lean/workflows/Build%20Orange%20Pi%20Zero%20Plus%20OpenWrt/badge.svg)](https://github.com/zhaocz086/lede_lean/actions/workflows/opzp.yml) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/zhaocz086/lede_lean/blob/main/config/ARM/opzp.config) |   |
|8|       [![](https://img.shields.io/badge/OpenWrt-斐讯_K3-FFFFFF.svg)](https://github.com/zhaocz086/lede_lean/blob/main/.github/workflows/K3.yml)           |[![](https://github.com/zhaocz086/lede_lean/workflows/Build%20PHICOMM%20K3%20OpenWrt/badge.svg)](https://github.com/zhaocz086/lede_lean/actions/workflows/K3.yml) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/zhaocz086/lede_lean/blob/main/config/ARM/k3.config)  |  | 
|9|       [![](https://img.shields.io/badge/OpenWrt-Linksys_Wrt1900acs-FFFFFF.svg)](https://github.com/zhaocz086/lede_lean/blob/main/.github/workflows/linksys_wrt1900acs.yml)           |[![](https://github.com/zhaocz086/lede_lean/workflows/Build%20Linksys%20Wrt1900acs%20OpenWrt/badge.svg)](https://github.com/zhaocz086/lede_lean/actions/workflows/linksys_wrt1900acs.yml) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/zhaocz086/lede_lean/blob/main/config/ARM/linksys-extra.config)  |  | 
|10|       [![](https://img.shields.io/badge/OpenWrt-Linksys_Wrt3200acm-FFFFFF.svg)](https://github.com/zhaocz086/lede_lean/blob/main/.github/workflows/linksys_wrt3200acm.yml)           |[![](https://github.com/zhaocz086/lede_lean/workflows/Build%20Linksys%20Wrt3200acm%20OpenWrt/badge.svg)](https://github.com/zhaocz086/lede_lean/actions/workflows/linksys_wrt3200acm.yml) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/zhaocz086/lede_lean/blob/main/config/ARM/linksys-extra.config)  |  | 
|11|       [![](https://img.shields.io/badge/OpenWrt-Linksys_Wrt32x-FFFFFF.svg)](https://github.com/zhaocz086/lede_lean/blob/main/.github/workflows/linksys_wrt32x.yml)           |[![](https://github.com/zhaocz086/lede_lean/workflows/Build%20Linksys%20Wrt32x%20OpenWrt/badge.svg)](https://github.com/zhaocz086/lede_lean/actions/workflows/linksys_wrt32x.yml) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/zhaocz086/lede_lean/blob/main/config/ARM/linksys-extra.config)  |  | 

**提示：**[![](https://img.shields.io/badge/设备-passing-32CD32.svg)](https://github.com/zhaocz086/lede_lean/actions) 标志为正常，[![](https://img.shields.io/badge/设备-failing-DC143C.svg)](https://github.com/zhaocz086/lede_lean/actions) 或 [![](https://img.shields.io/badge/设备-no_status-A9A9A9.svg)](https://github.com/zhaocz086/lede_lean/actions) 不代表所有编译均失败。请点击 [![](https://img.shields.io/badge/设备-状态-32CD32.svg)](https://github.com/zhaocz086/lede_lean/actions) 到 Actions 进一步查看。

</details>

<details>
 <summary><b>&nbsp;&nbsp;&nbsp; 高通 设备编译状态及固件下载</b></summary>
    
<br/>

点击下表中 [![](https://img.shields.io/badge/设备-passing-32CD32.svg)](https://github.com/zhaocz086/lede_lean/actions) 即可跳转到该设备固件下载页面
|    序号   |     高通平台     |   高通设备编译状态及下载链接 |   插件配置   | 备注说明   |
| :-----------------: | :-------------: |:-----------------: | :-----------------: |  :-----------------: | 
| 1 |        [![](https://img.shields.io/badge/OpenWrt-竞斗云-FFFFFF.svg)](https://github.com/zhaocz086/lede_lean/blob/main/.github/workflows/gdock.yml)         |[![](https://github.com/zhaocz086/lede_lean/workflows/Build%20G-Dock%20OpenWrt/badge.svg)](https://github.com/zhaocz086/lede_lean/actions/workflows/gdock.yml) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/zhaocz086/lede_lean/blob/main/config/Qualcomm/Qualcomm-extra.config)  | | 
| 2|     [![](https://img.shields.io/badge/OpenWrt-网件_R7800-FFFFFF.svg)](https://github.com/zhaocz086/lede_lean/blob/main/.github/workflows/R7800.yml)   | [![](https://github.com/zhaocz086/lede_lean/workflows/Build%20Netgear%20R7800%20OpenWrt/badge.svg)](https://github.com/zhaocz086/lede_lean/actions/workflows/R7800.yml) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/zhaocz086/lede_lean/blob/main/config/Qualcomm/Qualcomm-mini-extra.config) |   | 
| 3|     [![](https://img.shields.io/badge/OpenWrt-星际宝盒_CM520-FFFFFF.svg)](https://github.com/zhaocz086/lede_lean/blob/main/.github/workflows/CM520.yml)   | [![](https://github.com/zhaocz086/lede_lean/workflows/Build%20MobiPromo%20CM520%20OpenWrt/badge.svg)](https://github.com/zhaocz086/lede_lean/actions/workflows/CM520.yml) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/zhaocz086/lede_lean/blob/main/config/Qualcomm/Qualcomm-extra.config) |   |
| 4 |        [![](https://img.shields.io/badge/OpenWrt-斐讯_K2T-FFFFFF.svg)](https://github.com/zhaocz086/lede_lean/blob/main/.github/workflows/K2T.yml)           | [![](https://github.com/zhaocz086/lede_lean/workflows/Build%20PHICOMM%20K2T%20OpenWrt/badge.svg)](https://github.com/zhaocz086/lede_lean/actions/workflows/K2T.yml)|[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/zhaocz086/lede_lean/blob/main/config/Qualcomm/Qualcomm-mini-extra.config) | |
| 5 |        [![](https://img.shields.io/badge/OpenWrt-tp841N_V10-FFFFFF.svg)](https://github.com/zhaocz086/lede_lean/blob/main/.github/workflows/841NV10.yml)           | [![](https://github.com/zhaocz086/lede_lean/workflows/Build%20841NV10_ATH79_QCA9533%20OpenWrt/badge.svg)](https://github.com/zhaocz086/lede_lean/actions/workflows/841NV10.yml)|[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/zhaocz086/lede_lean/blob/main/diy/config/ATH79/ath-extra.config) | |
| 6 |        [![](https://img.shields.io/badge/OpenWrt-tp842N_V2-FFFFFF.svg)](https://github.com/zhaocz086/lede_lean/blob/main/.github/workflows/842NV2.yml)           | [![](https://github.com/zhaocz086/lede_lean/workflows/Build%20841NV2_AR71XX_AR9341%20OpenWrt/badge.svg)](https://github.com/zhaocz086/lede_lean/actions/workflows/842NV2.yml)|[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/zhaocz086/lede_lean/blob/main/diy/config/ATH79/ath-extra.config) | |
**提示：**[![](https://img.shields.io/badge/设备-passing-32CD32.svg)](https://github.com/zhaocz086/lede_lean/actions) 标志为正常，[![](https://img.shields.io/badge/设备-failing-DC143C.svg)](https://github.com/zhaocz086/lede_lean/actions) 或 [![](https://img.shields.io/badge/设备-no_status-A9A9A9.svg)](https://github.com/zhaocz086/lede_lean/actions) 不代表所有编译均失败。请点击 [![](https://img.shields.io/badge/设备-状态-32CD32.svg)](https://github.com/zhaocz086/lede_lean/actions) 到 Actions 进一步查看。

</details>

<details>
 <summary><b>&nbsp;&nbsp;&nbsp; MIPS 设备编译状态及固件下载</b></summary>
    
<br/>

**注意：** 考虑到 MIPS 设备的 CPU 性能及 RAM/ROM 量配置，功能较其他设备做了很大范围的删减。 

MIPS 设备推荐使用 Padavan 固件： [![](https://img.shields.io/badge/-Padavan_固件仓库_1-FFFFFF.svg)](https://github.com/hanwckf/rt-n56u) [![](https://img.shields.io/badge/-Padavan_固件仓库_2-FFFFFF.svg)](https://opt.cn2qq.com/padavan/) [![](https://img.shields.io/badge/-Padavan_固件仓库_3-FFFFFF.svg)](https://github.com/gorden5566/padavan)

点击下表中 [![](https://img.shields.io/badge/设备-passing-32CD32.svg)](https://github.com/zhaocz086/lede_lean/actions) 即可跳转到该设备固件下载页面
|    序号   |     MIPS设备     |   MIPS设备编译状态及下载链接 |   插件配置   | 备注说明   |
| :-----------------: | :-------------: |:-----------------: | :-----------------: |  :-----------------: | 
| 1 |        [![](https://img.shields.io/badge/OpenWrt-极路由_B70-FFFFFF.svg)](https://github.com/zhaocz086/lede_lean/blob/main/.github/workflows/B70.yml)        |[![](https://github.com/zhaocz086/lede_lean/workflows/Build%20HiWiFi%20B70%20OpenWrt/badge.svg)](https://github.com/zhaocz086/lede_lean/actions/workflows/B70.yml)|[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/zhaocz086/lede_lean/blob/main/config/MIPS/MIPS-extra.config) | |
|2|        [![](https://img.shields.io/badge/OpenWrt-斐讯_K2P-FFFFFF.svg)](https://github.com/zhaocz086/lede_lean/blob/main/.github/workflows/K2P.yml)           |[![](https://github.com/zhaocz086/lede_lean/workflows/Build%20PHICOMM%20K2P%20OpenWrt/badge.svg)](https://github.com/zhaocz086/lede_lean/actions/workflows/K2P.yml)|[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/zhaocz086/lede_lean/blob/main/config/MIPS/MIPS-extra.config) | |
| 3|    [![](https://img.shields.io/badge/OpenWrt-红米_AC2100-FFFFFF.svg)](https://github.com/zhaocz086/lede_lean/blob/main/.github/workflows/redmi_ac2100.yml)     | [![](https://github.com/zhaocz086/lede_lean/workflows/Build%20Redmi%20AC2100%20OpenWrt/badge.svg)](https://github.com/zhaocz086/lede_lean/actions/workflows/redmi_ac2100.yml) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/zhaocz086/lede_lean/blob/main/config/MIPS/MIPS-extra.config) | | 
| 4 |    [![](https://img.shields.io/badge/OpenWrt-Newifi3_D2-FFFFFF.svg)](https://github.com/zhaocz086/lede_lean/blob/main/.github/workflows/Newifi_D2.yml)      |  [![](https://github.com/zhaocz086/lede_lean/workflows/Build%20Newifi%20D2%20OpenWrt/badge.svg)](https://github.com/zhaocz086/lede_lean/actions/workflows/Newifi_D2.yml) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/zhaocz086/lede_lean/blob/main/config/MIPS/MIPS-extra.config)  | | 
|5|     [![](https://img.shields.io/badge/OpenWrt-小娱_C5-FFFFFF.svg)](https://github.com/zhaocz086/lede_lean/blob/main/.github/workflows/xiaoyu_xy-c5.yml)        | [![](https://github.com/zhaocz086/lede_lean/workflows/Build%20XiaoYu%20XY-C5%20OpenWrt/badge.svg)](https://github.com/zhaocz086/lede_lean/actions/workflows/xiaoyu_xy-c5.yml)   |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/zhaocz086/lede_lean/blob/main/config/MIPS/MIPS-extra.config)  |  |
| 6|     [![](https://img.shields.io/badge/OpenWrt-小米_R3G-FFFFFF.svg)](https://github.com/zhaocz086/lede_lean/blob/main/.github/workflows/R3G.yml)   | [![](https://github.com/zhaocz086/lede_lean/workflows/Build%20Mi%20R3G%20OpenWrt/badge.svg)](https://github.com/zhaocz086/lede_lean/actions/workflows/R3G.yml) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/zhaocz086/lede_lean/blob/main/config/MIPS/MIPS-extra.config) |   |
| 8|     [![](https://img.shields.io/badge/OpenWrt-小米_R3P-FFFFFF.svg)](https://github.com/zhaocz086/lede_lean/blob/main/.github/workflows/R3P.yml)   | [![](https://github.com/zhaocz086/lede_lean/workflows/Build%20Mi%20R3P%20OpenWrt/badge.svg)](https://github.com/zhaocz086/lede_lean/actions/workflows/R3P.yml) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/zhaocz086/lede_lean/blob/main/config/MIPS/MIPS-extra.config) |   |

**提示：**[![](https://img.shields.io/badge/设备-passing-32CD32.svg)](https://github.com/zhaocz086/lede_lean/actions) 标志为正常，[![](https://img.shields.io/badge/设备-failing-DC143C.svg)](https://github.com/zhaocz086/lede_lean/actions) 或 [![](https://img.shields.io/badge/设备-no_status-A9A9A9.svg)](https://github.com/zhaocz086/lede_lean/actions) 不代表所有编译均失败。请点击 [![](https://img.shields.io/badge/设备-状态-32CD32.svg)](https://github.com/zhaocz086/lede_lean/actions) 到 Actions 进一步查看。

</details>

<a href="#readme">
    <img src="https://img.shields.io/badge/-返回顶部-FFFFFF.svg" alt="图裂了😂" title="返回顶部" align="right"/>
</a>

## 基本介绍 [![](https://img.shields.io/badge/-项目基本介绍-FFFFFF.svg)](#基本介绍-)

1. 默认引用[ Lean 的 OpenWrt 库](https://github.com/coolsnowwolf/lede)（部分设备整合[ Lienol 的 Packages 库](https://github.com/Lienol/openwrt-packages)），因为他的 [README](https://github.com/coolsnowwolf/lede/blob/master/README.md) 影响了我开始学习编译；Github Actions 自动云编译代码采用 [P3TERX 的 Actions-OpenWrt 库 ](https://github.com/P3TERX/Actions-OpenWrt)。

2. [插件及功能预览 请点击查看](https://github.com/IvanSolis1989/OpenWrt-DIY/wiki/OpenWrt-DIY%E6%8F%92%E4%BB%B6%E9%A2%84%E8%A7%88)

3. `每周五查询大雕源码是否有更新`，如有更新自动拉取最新源码和第三方软件包项目自动编译（根据设备不同编译时间在1~5个小时），`固件包含必要驱动及常用插件`（各设备的 config 借鉴大雕设置及根据网友需求调整），未逐一经过实机测试，故 `不保证 100% 可靠性`；

4. 如有什么问题、需要增加编译设备或者编译文件配置需要调整的，可以直接在 [Issues](https://github.com/IvanSolis1989/OpenWrt-DIY/issues) 内留言。 我会不定时的根据大家的要求修改`编译配置，插件选项，增加编译设备`等；

5. 为了让更多朋友的设备能用上稳定且功能强大的 OpenWrt 固件，并保持持续更新。也希望动手能力强的朋友去学习编译[（后文有教程）](#小贴士-)，然后根据你自己的需要配置 menuconfig，把配置好的 config 文件提交到本项目，可以根据使用者的需求扩充更多设备。

<a href="#readme">
    <img src="https://img.shields.io/badge/-返回顶部-FFFFFF.svg" alt="图裂了😂" title="返回顶部" align="right"/>
</a>

## 近期更新 [![](https://img.shields.io/badge/-近期固件更新-FFFFFF.svg)](#近期更新-)

1. 默认 [Argon 主题](https://github.com/jerrykuku/luci-theme-argon)，界面更美丽。

<details>
 <summary>&nbsp;&nbsp;&nbsp; Argon 主题效果图</summary>
   
<br/>
<div align=center><img src="https://raw.githubusercontent.com/jerrykuku/staff/master/argon2.gif" alt="图裂了😂需要机场才能正常显示"/></div>
<div align=center><img src="https://img.vim-cn.com/65/37b71b446767d67c388b9507fb9cbf2f1d4462.jpg" alt="图裂了😂需要机场才能正常显示"/></div>
</details>

2. 加入 [ROSY 主题](https://github.com/rosywrt/luci-theme-rosy) 可选

<details>
 <summary>&nbsp;&nbsp;&nbsp; ROSY 主题效果图</summary>
   
<br/>
<div align=center><img src="https://raw.githubusercontent.com/rosywrt/luci-theme-rosy/openwrt-18.06/previews/login-pc.png" alt="图裂了😂需要机场才能正常显示"/></div>
<div align=center><img src="https://raw.githubusercontent.com/rosywrt/luci-theme-rosy/openwrt-18.06/previews/overview-pc.png" alt="图裂了😂需要机场才能正常显示"/></div>
</details>

3. `默认 IP 调整为：192.168.10.1，默认密码：password。`

<a href="#readme">
    <img src="https://img.shields.io/badge/-返回顶部-FFFFFF.svg" alt="图裂了😂" title="返回顶部" align="right"/>
</a>

## 注意事项 [![](https://img.shields.io/badge/-下载注意事项-FFFFFF.svg)](#注意事项-)

1. 在固件编译完成后，会上传一份副本到 WeTransfer 和 奶牛快传，对于国内网络用户，为提高下载体验，可下载存放于这两个网站中的固件副本，副本下载地址位于固件下载页面中固件文件列表下的 Annotations 提示框内，`一段时间后（1~3天）网盘内的文件会失效`，所以推荐周五~周日下载最新版；
<details>
 <summary>&nbsp;&nbsp;&nbsp;找不到？请点击这里！</summary>
 
<br/>
<div align=center><img src="https://img.vim-cn.com/ef/2481045f0a6fac8ee6c0c437b5c225ee880295.png" alt="图裂了😂需要机场才能正常显示"/></div>
<div align=center><img src="https://img.vim-cn.com/f8/d5f01cc3e33460963635eb7b7cf5a472859f88.png" alt="图裂了😂需要机场才能正常显示"/></div>
</details>

2. 在极少数情况下，因网络原因这两份副本可能会上传失败，如果遇到这种情况，就只能下载存放在 Github Action 里的固件了，由于 Github Action 限制，`需要登录 Github 账号才可下载存放于 Github Action 中的固件 (未登录时固件链接不可被点击)`，但 WeTransfer 和 奶牛快传 的固件下载链接在未登录状态下可正常查看，不受影响；

3. 如果需要下载存放于 Github Action 上的固件，由于众所周知的原因，`请尽量使用科学上网方式下载固件`，固件下载完成后，请下载 sha256sums 文件或使用压缩软件的 "测试压缩文件" 功能来验证固件的完整性。

<a href="#readme">
    <img src="https://img.shields.io/badge/-返回顶部-FFFFFF.svg" alt="图裂了😂" title="返回顶部" align="right"/>
</a>

## 小贴士 [![](https://img.shields.io/badge/-日常使用技巧及教程-FFFFFF.svg)](#小贴士-)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 本栏目包含了很多 OpenWrt 日常使用问题解决方案、“不可描述”的教程、广告屏蔽教程，NAS（或路由器共享盘）的多媒体文件整理播放教程、OpenWrt 本地自编译教程。

<details>
 <summary>&nbsp;&nbsp;&nbsp; 基础常用</summary>

<br/>

[OpenWrt 基础配置](https://github.com/IvanSolis1989/OpenWrt-DIY/wiki/OpenWrt-%E5%9F%BA%E7%A1%80%E9%85%8D%E7%BD%AE)

[OpenWrt 软路由 IPv6 上网设置](https://github.com/IvanSolis1989/OpenWrt-DIY/wiki/OpenWrt-%E8%BD%AF%E8%B7%AF%E7%94%B1-IPv6-%E4%B8%8A%E7%BD%91%E8%AE%BE%E7%BD%AE)

[OpenWrt 网络共享文件和 Transmission 使用技巧，再也没有恼人的权限问题](https://youtu.be/wmR7o9p9vSY)

[SD 卡设备固件刷写程序 BalenaEtcher](https://www.balena.io/etcher/)

</details>

<details>
 <summary>&nbsp;&nbsp;&nbsp; USB 网卡</summary>

<br/>

**USB 有线网卡**

推荐使用基于 AX88179（[绿联20256](https://union-click.jd.com/jdc?e=&p=AyIGZRprFQETA10cXSVGTV8LRGtMR1dGFxBFC1pXUwkEAEAdQFkJBVsWAxYPUh1ETEdOWmVdIHFbakcpHD4LGBJsV3suc1ducxNNVxkyEzdWGlsVBhcEVRNYJTISAGVNNRUDEwZUGlgTAhQ3VCtbEgIRAVATUxYCEQdUK1wVCyJcAHVfRVBCUAEYXBQFQQICK2slASI3ZRtrFjJQaVRIWRIEEAZRGQsRUhdVABkLEVIQV1xIDhYDFQdQElkTMhAGVB9S)）或 RTL8153（[山泽UW013](https://union-click.jd.com/jdc?e=&p=AyIGZRtYFAUWA1MdXBYyFQVTH14UByJDCkMFSjJLQhBaGR4cDF8QTwcKWUcYB0UHCwUQAVEeWhAdS0IJRmt9dE9wLGwwV2JUUyliWBxEDEdQGilTDh43VCtYFAISA1AYWx0BIjdVHGtXbFBXCVACQVlKTwErWiUCFQdWHV4dChYBUhtZJQUSDmVADnsGQlUFTA8WBRMABh4MJTIiBGUraxUyETcXdVkcBhIHUxxSFAcXB1AeCBALGwJdEgxHCxpQVhpTRQERN1caWhEL)） 芯片的 USB 有线网卡设备。

**USB 无线网卡**

推荐使用基于雷凌 RT3070(150Mbps)/RT5370(150Mbps)/RT5572(300Mbps+600Mbps) 芯片;  

或 MT7612U(300Mbps+867Mbps) 芯片的 USB 无线网卡设备 (例如华硕 AC55、网件 A6210 等)。

**备注**：个人不建议在软路由设备上用 USB 外接无线网卡，信号强度、稳定性都比较弱。



<a href="#readme">
    <img src="https://img.shields.io/badge/-返回顶部-FFFFFF.svg" alt="图裂了😂" title="返回顶部" align="right"/>
</a>
