# Github-Gemini — Build Report

- **Run:** https://github.com/pourih/Eternal-Sub/actions/runs/41048530035
- **Date (UTC):** 2026-10-30 11:33
- **Duration:** 3 min
- **Xray core:** v26.10.29

## Funnel

- **No-fingerprint excluded:** 8672 configs (require_fingerprint=true — no uTLS fp in link)
- **Tested:** 3702 configs — **alive:** 462 (279 in allowed countries, 183 in other countries skipped)
- **Gemini-OK:** 198 of 279 (81 Gemini-blocked)
- **Quality rejects:** 87 (jitter=56, dl=16, ka=12, up=3) — ka=keep-alive, jitter, dl=download/speed, up=upload
- **In sub:** **143** configs = **143** ♊Gemini + **0** alive-only (allowed country, no Gemini, passed quality)
- **Excluded alive-only:** 49 configs passed quality but are NOT in the sub (include_alive_no_gemini=false)

## ♊Gemini configs in sub by country

| Country | Gemini-OK |
|---|---|
| NL 🇳🇱 | 53 |
| DE 🇩🇪 | 31 |
| US 🇺🇸 | 29 |
| FR 🇫🇷 | 9 |
| SG 🇸🇬 | 9 |
| GB 🇬🇧 | 7 |
| TR 🇹🇷 | 5 |

## Per-subscription performance

| # | Subscription | Fetched | Unique | Alive | Gemini OK |
|---|---|---|---|---|---|
| 1 | pourih/verified.txt | 657 | 355 | 165 | 85 |
| 2 | miladtahanian/sub.txt | 200 | 46 | 1 | 0 |
| 3 | rtwo2/top.txt | 1000 | 403 | 78 | 18 |
| 4 | R3ZARAHIMI/Original-Configs.txt | 161 | 50 | 8 | 4 |
| 5 | roosterkid/V2RAY_RAW.txt | 130 | 12 | 0 | 0 |
| 6 | MahanKenway/vless.txt | 139 | 8 | 1 | 0 |
| 7 | luckylukam/configs_tested.txt | 125 | 75 | 10 | 0 |
| 8 | ThomasJasperthecat/sublist1.txt | 12 | 12 | 0 | 0 |
| 9 | teknovpnhub/test2 | 26 | 26 | 0 | 0 |
| 10 | iampedii/base64.txt | 203 | 10 | 4 | 3 |
| 11 | Au1rxx/v2ray-base64.txt | 1446 | 58 | 2 | 2 |
| 12 | 0xRadikal/configs.txt | 1190 | 233 | 118 | 56 |
| 13 | configs_base64.txt | 4758 | 496 | 18 | 9 |
| 14 | F0rc3Run/proxies.txt | 55 | 0 | 0 | 0 |
| 15 | Delta-Kronecker/vless.txt | 820 | 247 | 37 | 17 |
| 16 | ermaozi/v2ray.txt | 398 | 145 | 1 | 0 |
| 17 | ninjastrikers/all.txt | 2554 | 390 | 8 | 1 |
| 18 | Farid-Karimi/mixed_iran.txt | 560 | 71 | 3 | 1 |
| 19 | liketolivefree/sub.txt | 425 | 192 | 2 | 1 |
| 20 | roosterkid/V2RAY_BASE64.txt | 130 | 0 | 0 | 0 |
| 21 | MhdiTaheri/mix.txt | 389 | 63 | 0 | 0 |
| 22 | barry-far/Sub4.txt | 500 | 160 | 0 | 0 |
| 23 | 10ium/merged_base64 | 1454 | 485 | 6 | 1 |
| 24 | Mosifree/Reality | 266 | 165 | 0 | 0 |
| | **TOTAL** | **17598** | **3702** | **462** | **198** |

**Subscription:** https://raw.githubusercontent.com/pourih/Eternal-Sub/main/Github-Gemini.txt
