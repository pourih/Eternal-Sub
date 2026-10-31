# Github-Gemini — Build Report

- **Run:** https://github.com/pourih/Eternal-Sub/actions/runs/41195156304
- **Date (UTC):** 2026-10-31 11:05
- **Duration:** 3 min
- **Xray core:** v26.10.29

## Funnel

- **No-fingerprint excluded:** 8795 configs (require_fingerprint=true — no uTLS fp in link)
- **Tested:** 3476 configs — **alive:** 477 (279 in allowed countries, 198 in other countries skipped)
- **Gemini-OK:** 170 of 279 (109 Gemini-blocked)
- **Quality rejects:** 92 (jitter=32, dl=29, ka=24, up=7) — ka=keep-alive, jitter, dl=download/speed, up=upload
- **In sub:** **131** configs = **131** ♊Gemini + **0** alive-only (allowed country, no Gemini, passed quality)
- **Excluded alive-only:** 56 configs passed quality but are NOT in the sub (include_alive_no_gemini=false)

## ♊Gemini configs in sub by country

| Country | Gemini-OK |
|---|---|
| US 🇺🇸 | 41 |
| NL 🇳🇱 | 33 |
| DE 🇩🇪 | 27 |
| FR 🇫🇷 | 12 |
| TR 🇹🇷 | 7 |
| SG 🇸🇬 | 5 |
| CH 🇨🇭 | 4 |
| GB 🇬🇧 | 2 |

## Per-subscription performance

| # | Subscription | Fetched | Unique | Alive | Gemini OK |
|---|---|---|---|---|---|
| 1 | pourih/verified.txt | 677 | 400 | 186 | 82 |
| 2 | miladtahanian/sub.txt | 221 | 75 | 9 | 7 |
| 3 | rtwo2/top.txt | 1000 | 390 | 79 | 15 |
| 4 | R3ZARAHIMI/Original-Configs.txt | 162 | 52 | 11 | 0 |
| 5 | roosterkid/V2RAY_RAW.txt | 142 | 15 | 7 | 5 |
| 6 | MahanKenway/vless.txt | 151 | 7 | 0 | 0 |
| 7 | luckylukam/configs_tested.txt | 125 | 75 | 9 | 0 |
| 8 | ThomasJasperthecat/sublist1.txt | 12 | 12 | 0 | 0 |
| 9 | teknovpnhub/test2 | 26 | 26 | 0 | 0 |
| 10 | iampedii/base64.txt | 194 | 15 | 5 | 5 |
| 11 | Au1rxx/v2ray-base64.txt | 1446 | 60 | 4 | 2 |
| 12 | 0xRadikal/configs.txt | 1289 | 234 | 107 | 40 |
| 13 | configs_base64.txt | 4929 | 456 | 11 | 3 |
| 14 | F0rc3Run/proxies.txt | 72 | 0 | 0 | 0 |
| 15 | Delta-Kronecker/vless.txt | 826 | 235 | 21 | 8 |
| 16 | ermaozi/v2ray.txt | 417 | 154 | 1 | 0 |
| 17 | ninjastrikers/all.txt | 2561 | 328 | 16 | 1 |
| 18 | Farid-Karimi/mixed_iran.txt | 580 | 81 | 5 | 0 |
| 19 | liketolivefree/sub.txt | 209 | 22 | 4 | 1 |
| 20 | roosterkid/V2RAY_BASE64.txt | 142 | 0 | 0 | 0 |
| 21 | MhdiTaheri/mix.txt | 392 | 72 | 0 | 0 |
| 22 | barry-far/Sub4.txt | 500 | 113 | 0 | 0 |
| 23 | 10ium/merged_base64 | 1453 | 492 | 2 | 1 |
| 24 | Mosifree/Reality | 266 | 162 | 0 | 0 |
| | **TOTAL** | **17792** | **3476** | **477** | **170** |

**Subscription:** https://raw.githubusercontent.com/pourih/Eternal-Sub/main/Github-Gemini.txt
