# HHT_AutoConNet_nodemcu

使用單片機程序自動登錄hht

無需使用服務器，低成本，實現無縫重連，智能&共享，的寬帶優化體驗


## 開發平臺

- VScode

- PlatformIO

- Arduino


## 開發日志

hht_ACN_esp32c3_pio 基本本地功能已實現 2023.9.1，api.HHT/ 是詐騙慣了，總是返回虛假的404，最終不再使用返回值檢測，通過get了*Du娘*作爲連接成功的返回值


## 使用説明

1. 下載本項目源碼

2. 選擇對應的mcu型號

3. 用vscode打開，安裝platformIO插件

4. 連接開發板

5. 編譯后燒錄固件

6. 觸摸gpio0恢復出廠設置


## TODO

* 基本功能 *

- [x] WiFi連接
- [x] 登錄HHT網絡服務
- [X] 恢復出廠設置
- [x] 定時重連系統
- [X] 工作指示燈
- [X] adc觸摸代替短接恢復出廠設置
- [X] boot键位与fac复用
- [ ] rtos多task调度
- [ ] 掉電不丟失數據管理
- [ ] 配置页面填写数据正确检测


* 雲服務 *

- [ ] 套餐額度計費功能
- [ ] 用戶訂套餐系統
- [ ] 用戶支付系統接入
- [ ] 雲服務器後端
- [ ] 雲端OTA升級固件
- [ ] 後臺雲服務


* 硬件部分 *

- [ ] 適配esp8266-1M
- [X] 適配esp32c3


* 機械部分 *

- [ ] esp32c3外殼：甲方需求如下
- [X] 長方體外殼
- [X] usb-c口開孔，給電綫大頭留位置
- [x] 兩個led指示燈挖孔
- [X] reset按鍵挖孔
- [X] 板載wifi天綫挖孔
- [X] 恢復出廠設置引脚開孔
- [ ] 一面浮雕上使用説明書
- [ ] 镂空logo
- [ ] 圆角
- [ ] 
- [ ] 把192.168.4.1生成貼紙貼上




* 固件移植 *

- [ ] 適配esp8266-4M
- [ ] 適配esp01s-1M
- [ ] 適配esp32_s1-4M
- [ ] 適配esp32_s2
- [ ] 適配esp32_s3
- [x] 適配esp32_c3-4M



## THANKS

- 本项目收录于 https://github.com/JMasterFull-StackGroup/4w4-2-ssypu —— 4w4 GoTo Pussy

- 感謝項目 https://github.com/XJTLU-Geek/hht-network 和 https://github.com/kaijianyi/NJUCM_NET 的支持和幫助

- 親情贊助 / 商務大使 /形象代言 : **山坤坤**

