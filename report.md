# 6J0 Aviation Weather
*Experimental - Verify official sources*
Base time 15:00 EST Sat Nov 14.
Generated 15:10 EST. Winds kt, directions TRUE (magnetic = true + 7°). Sunset 17:22.

## Now
- **Wind (est.)** NW 304° at **8 kt**, gust/peak est. **15 kt** — speed = mean of KCAE/KCUB/KAIK/KAGS obs (estimate); direction = KCAE/KCUB METAR distance-weighted vector average.
- **RC Winds Lexington County Airport (observed; converted from mph to kt):** NW 9.0 kt, peak 12.7 kt at 15:00 EST. Last-hour mean 7.4, max peak 12.9; 3-h range 3.0–9.0.
- Feels-like next 6 h: 21:00 41 °F (wind chill)
- Rwy 18: headwind -6, crosswind 6 R · Rwy 36: headwind 6, crosswind 6 L (sustained).
- Temp/dew **58/28 °F** (KCAE/KCUB obs; 6J0 sensor broken) · Altimeter 30.07 · **DA 380 ft** · KCAE sky SCT060

## Next 6 h

| Time | Wind | Gust | Rwy 36 HW / XW | Temp/Dew °F | DA ft | Mix ft AGL | Sky % | Ceiling | Decay chk |
|---|---|---|---|---|---|---|---|---|---|
| 15:00 (obs/est) | 304° 8 | 15 | 6 / 6 L (g 11 L) | 58/28 | 380 | 6310 | 2 | none |  |
| 16:00 | 319° 8 | 13 | 7 / 4 L (g 7 L) | 58/30 | 390 | 5890 | 1 | none | 8 |
| 17:00 | 322° 6 | 10 | 5 / 3 L (g 5 L) | 56/31 | 260 | 2440 | 1 | none | 6 |
| 18:00 | 325° 4 | 8 | 4 / 2 L (g 3 L) | 52/31 | -0 | 1250 | 1 | none | 4 |
| 19:00 | 331° 2 | 6 | 2 / 1 L (g 2 L) | 48/31 | -270 | 420 | 1 | none | 3 |
| 20:00 | 341° 2 | 7 | 2 / 0 (g 1 L) | 43/31 | -610 | 410 | 1 | none | 2 |
| 21:00 | 351° 3 | 7 | 3 / 0 (g 0) | 42/31 | -680 | 410 | 1 | none | 2 |

**Outlook:** wind NW–N 2–8 kt, peak gust ~13 kt around 16:00. Max 36 crosswind 4 kt sustained / 7 kt gust. DA up to 390 ft.

## Winds aloft (ft MSL) — speed kt, true dir, temp °C; **bold** = flagged
| ft MSL | 15:00 | 16:00 | 17:00 | 18:00 | 19:00 | 20:00 | 21:00 |
|---|---|---|---|---|---|---|---|
| 12000 | 24 kt 321° -9°C | 22 kt 323° -9°C | 20 kt 325° -9°C | 17 kt 329° -8°C | 14 kt 339° -8°C | 12 kt 341° -8°C | 12 kt 334° -8°C |
| 10500 | 20 kt 327° -7°C | 20 kt 328° -7°C | 19 kt 329° -7°C | 17 kt 331° -6°C | 14 kt 340° -6°C | 12 kt 342° -5°C | 11 kt 335° -5°C |
| 9000 | 16 kt 329° -6°C | 17 kt 329° -6°C | 18 kt 329° -5°C | 18 kt 330° -4°C | 15 kt 337° -4°C | 13 kt 341° -3°C | 11 kt 340° -3°C |
| 7500 | 14 kt 325° -5°C | 15 kt 325° -5°C | 16 kt 323° -5°C | 17 kt 323° -4°C | 16 kt 328° -3°C | 14 kt 329° -3°C | 12 kt 336° -2°C |
| 6000 | 13 kt 321° -4°C | 13 kt 321° -4°C | 13 kt 317° -3°C | 14 kt 315° -3°C | 15 kt 318° -2°C | 15 kt 317° -2°C | 14 kt 321° -2°C |
| 4500 | 13 kt 320° +0°C | 14 kt 322° +0°C | 13 kt 321° +0°C | 12 kt 318° +0°C | 12 kt 321° +0°C | 13 kt 320° +0°C | 12 kt 317° +0°C |
| 3000 | 13 kt 322° +5°C | 14 kt 323° +5°C | 13 kt 326° +5°C | 12 kt 330° +5°C | 12 kt 339° +4°C | 12 kt 343° +4°C | 10 kt 002° +4°C |
| 1500 | 13 kt 322° +9°C | 13 kt 325° +9°C | 12 kt 329° +9°C | 12 kt 340° +9°C | 14 kt 354° +9°C | **13 kt 003° +8°C** (inversion) | **16 kt 018° +8°C** (inversion) |
| Surface 452' | 8 kt 304° G15 +14°C | 8 kt 319° G13 +14°C | 6 kt 322° G10 +13°C | 4 kt 325° G8 +11°C | 2 kt 331° G6 +9°C | 2 kt 341° G7 +6°C | 3 kt 351° G7 +6°C |
Flags: 20:00 1500 ft: inversion; 21:00 1500 ft: inversion
Method: ncep_hrrr_conus pressure-level profile at 6J0 (Open-Meteo), u/v/T linearly interpolated in height (geopotential, MSL); at 3000–9000 ft and 12000 ft wind is a 50/50 vector average with CAE FB winds for the valid period (FB interpolated between 3000/6000/9000 ft; 10500 ft model only). Flags: arrow yellow ≥25 kt, red ≥35 kt; shear = vector difference ≥20 kt vs the level below, ≥35 kt vs the surface, or direction change ≥60° with both ≥10 kt; inversion = ≥2 °C warmer than the level/surface below; anomaly = layer lapse >3.5 °C/1000 ft between aloft levels or ≥20 °C from ISA.

## Method & sources
- Wind = ½ NWS gridpoint (6J0) + ½ mean of NBM/LAMP sustained wind at KCAE, KCUB, KAIK, KAGS. Gust = mean of NWS grid gust, the 4-station gust fit, and (17:00–21:00) 4.7+0.61·KCAE; ≥ wind+3. Decay column = sunset wind-decay model (sanity check only, ⚠ = differs >3 kt).
- Components (table and 6J0 Runway winds panel): true runway headings 171°/351° with true winds (≡ 178°/358° magnetic). XW R/L = wind from the right/left of the landing aircraft. DA uses forecast T/Td and current KCAE/KCUB altimeter 30.07 held constant (moist-air density: station pressure from the altimeter, Buck vapour pressure from Td; winds-aloft cells use the model level pressure and T/Td; surface cell = this DA).
- KCAE webcam (EarthCam live stream): ok (VM): 1920x1080, captured 15:09 EST
- WPC Day 1 national forecast chart: ok; details from map.php
- FAA SEAMS stadium TFRs (NOTAM 0/0367): ok: 5 events within 90 nm; venues: FAA AIS Stadiums (live, cached 2026-11-14T00:06Z)
- GOES-19 GLM FED+GeoColor (STAR CDN): ok: 20263181951 2400x2400 crop (910, 318, 1772, 866)
- METAR (aviationweather.gov): ok: KAGS, KAIK, KCAE, KCUB
- KCAE METAR today (hi/lo so far): ok: 15 reports since midnight
- TAF KCAE/KAGS: ok
- TAF KCAE cloud layers (json): ok
- FB winds aloft (CAE): FAILED: 400 Client Error: Bad Request for url: https://aviationweather.gov/api/data/windtemp?region=all&level=low&fcst=06
- KCAE NEXRAD L2 + GLM (radar_panel.py): KCAE KCAE20261114_200038_V06 0.5deg, GLM 46 files, 0 flashes, 12.1s
- FB winds aloft CAE (06/12/24 products): FAILED: none parsed
- Open-Meteo pressure levels: ok: model ncep_hrrr_conus
- NWS gridpoint raw: ok: https://api.weather.gov/gridpoints/CAE/58,51 (updated 2026-11-14T18:21:21+00:00)
- GFS LAMP (NOMADS lavtxt): ok: 2026-11-14 1930Z cycle
- NBM NBH text (NOMADS): ok: 2026-11-14 18Z cycle
- RC Winds Lexington County Airport 5-min: ok: 34 rows, latest 15:00 EST (speeds converted from mph to kt)
- AWC G-AIRMET Tango LLWS/TURB-LO: ok
- WeatherNext 3 PoP (6J0, derived from 1 h precip percentiles): ok: 7 hour bins from 6J0_wn_20261113_00Z_full.csv, 6J0_wn_20261114_00Z_full.csv

```
TAF KAGS 141720Z 1418/1518 33007KT P6SM SKC 
  FM150000 00000KT P6SM SKC
TAF KCAE 141720Z 1418/1518 31009KT P6SM SKC 
  FM150000 VRB03KT P6SM SKC
```
