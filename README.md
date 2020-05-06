# 中州韻粵語拼音輸入法分歧拼音系統補丁
* 依賴於：[`rime/rime-cantonese`](github.com/rime/rime-cantonese)
* 呢個補丁將jyut6ping3.dict.yaml嘅詞句轉換成其他主流拼音系統，方便用開GBoard或者其他廣東話輸入法嘅用家使用。
* **長遠請考慮轉用香港語言學學會嘅粵語拼音方案（「粵拼」），一嚟比較貼近國際音標，二嚟大部分嘅現代粵語資源都係用「粵拼」標音。如果閣下希望同本地粵語文化接軌，請考慮轉用粵拼**

## 點樣先知我用緊邊種拼音系統？
| 你會將「出」字拼成... | 拼音系統  |
| :------------- | :------------- |
| ceot       | **粵拼** (/œː/作`oe`，/ɵ/作`eo`)|
| cheut      | 耶魯拼音 (/œː/、/ɵ/ 一律作`eu`)|
| coet       | 教院式拼音 (/œː/、/ɵ/ 一律作`oe`)|
| chut       | 劉錫祥式拼音 (/œː/作`eu`，/ɵ/作`u`) |

## 安裝方法
* 入去你個拼音方案個資料夾度。
* 下載入面個jyut6ping3.custom.yaml，然後放入去[「用戶資料夾」](https://github.com/rime/home/wiki/UserData)度。
* 重新部署