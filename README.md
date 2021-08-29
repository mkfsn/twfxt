# TW Foreign eXchange Rate

目前提供一個簡單的 API 來抓取
[台灣銀行非營業時間牌告匯率](https://rate.bot.com.tw/xrt?Lang=zh-TW)
的結果，然後附上一個簡易的 CLI。

## 安裝

```bash
go install github.com/mkfsn/twfxr
```

## 產生 CLI 執行檔

```bash
go build ./cmd/twfxr
```

### 執行結果範例

```bash
$ ./twfxr 
| 外幣  | 本行買入:現金   | 本行買入:即期   | 本行賣出:現金   | 本行賣出:即期   |
|------|---------------|---------------|---------------|---------------|
|  USD |     27.520000 |     27.845000 |     28.190000 |     27.995000 |
|  HKD |      3.430000 |      3.551000 |      3.634000 |      3.621000 |
|  GBP |     37.260000 |     38.155000 |     39.380000 |     38.785000 |
|  AUD |     20.030000 |     20.245000 |     20.810000 |     20.590000 |
|  CAD |     21.650000 |     21.980000 |     22.560000 |     22.310000 |
|  SGD |     20.170000 |     20.640000 |     21.080000 |     20.860000 |
|  CHF |     29.820000 |     30.430000 |     31.020000 |     30.820000 |
|  JPY |      0.244900 |      0.251900 |      0.257700 |      0.256500 |
|  ZAR |             - |      1.851000 |             - |      1.941000 |
|  SEK |      2.850000 |      3.180000 |      3.370000 |      3.300000 |
|  NZD |     19.090000 |     19.420000 |     19.940000 |     19.720000 |
|  THB |      0.730300 |      0.839700 |      0.920300 |      0.885700 |
|  PHP |      0.486400 |             - |      0.619400 |             - |
|  IDR |      0.001580 |             - |      0.002280 |             - |
|  EUR |     32.120000 |     32.635000 |     33.460000 |     33.235000 |
|  KRW |      0.022290 |             - |      0.026190 |             - |
|  VND |      0.000980 |             - |      0.001390 |             - |
|  MYR |      5.652000 |             - |      7.132000 |             - |
|  CNY |      4.225000 |      4.292000 |      4.387000 |      4.352000 |
```
