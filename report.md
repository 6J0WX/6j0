# 6J0 Aviation Weather
*Experimental - Verify official sources*
Base time 11:00 EST Sat Nov 21.
Generated 11:07 EST. Winds kt, directions TRUE (magnetic = true + 7°). Sunset 17:18.

## Now
- **Wind (est.)** NNE 30° at **7 kt**, gust/peak est. **11 kt** — speed = mean of KCAE/KCUB/KAIK/KAGS obs (estimate); direction = KCAE METAR distance-weighted vector average.
- **RC Winds Lexington County Airport (observed; converted from mph to kt):** N 8.0 kt, peak 9.6 kt at 10:55 EST. Last-hour mean 7.8, max peak 12.2; 3-h range 6.8–9.9.
- Feels-like next 6 h: no heat index/wind chill (wind chill only below 50 °F, heat index from 80 °F)
- Rwy 18: headwind -6, crosswind 5 L · Rwy 36: headwind 6, crosswind 5 R (sustained).
- Temp/dew **61/46 °F** (KCAE/KCUB obs; 6J0 sensor broken) · Altimeter 30.16 · **DA 520 ft** · KCAE sky SCT035 OVC055

## Next 6 h

| Time | Wind | Gust | Rwy 36 HW / XW | Temp/Dew °F | DA ft | Mix ft AGL | Sky % | Ceiling | Decay chk |
|---|---|---|---|---|---|---|---|---|---|
| 11:00 (obs/est) | 30° 7 | 11 | 6 / 5 R (g 7 R) | 61/46 | 520 | 1410 | 91 | 5,500 ft |  |
| 12:00 | 40° 12 | 22 | 8 / 9 R (g 16 R) | 60/51 | 520 | 1450 | 91 | 3,500 ft |  |
| 13:00 | 41° 13 | 21 | 8 / 10 R (g 16 R) | 61/53 | 600 | 1520 | 92 | 4,500 ft |  |
| 14:00 | 39° 13 | 22 | 8 / 9 R (g 17 R) | 62/54 | 670 | 1410 | 92 | 3,500 ft |  |
| 15:00 | 39° 12 | 22 | 8 / 9 R (g 16 R) | 62/55 | 680 | 1250 | 94 | 3,500 ft |  |
| 16:00 | 40° 12 | 21 | 8 / 9 R (g 16 R) | 62/58 | 700 | 1420 | 89 | 2,700 ft | 12 |
| 17:00 | 39° 14 | 19 | 9 / 10 R (g 14 R) | 62/57 | 690 | 1050 | 89 | 2,700 ft | 9 ⚠ |

**Outlook:** wind NE–NE 12–14 kt, peak gust ~22 kt around 14:00. Max 36 crosswind 10 kt sustained / 17 kt gust. DA up to 700 ft.

## Winds aloft (ft MSL) — speed kt, true dir, temp °C; **bold** = flagged
| ft MSL | 11:00 | 12:00 | 13:00 | 14:00 | 15:00 | 16:00 | 17:00 |
|---|---|---|---|---|---|---|---|
| 12000 | 13 kt 135° +0°C | 13 kt 152° +0°C | 11 kt 156° +1°C | 10 kt 159° +1°C | 7 kt 155° +1°C | 5 kt 160° +0°C | 4 kt 143° +0°C |
| 10500 | 18 kt 138° +3°C | 17 kt 148° +3°C | 15 kt 148° +3°C | 14 kt 153° +3°C | 11 kt 151° +3°C | 9 kt 150° +3°C | 8 kt 136° +3°C |
| 9000 | 21 kt 133° +5°C | 18 kt 136° +5°C | 18 kt 131° +5°C | 17 kt 135° +5°C | 15 kt 134° +5°C | 13 kt 133° +5°C | 12 kt 122° +5°C |
| 7500 | 24 kt 123° +7°C | 20 kt 116° +7°C | 20 kt 115° +7°C | 21 kt 117° +7°C | 20 kt 118° +7°C | 20 kt 116° +7°C | 20 kt 112° +7°C |
| 6000 | 25 kt 111° +9°C | 25 kt 102° +9°C | 25 kt 103° +9°C | 27 kt 105° +9°C | 27 kt 108° +9°C | 30 kt 107° +9°C | 30 kt 108° +9°C |
| 4500 | 28 kt 098° +11°C | 31 kt 097° +11°C | 31 kt 096° +11°C | 33 kt 098° +11°C | 33 kt 102° +11°C | 35 kt 101° +11°C | **36 kt 103° +11°C** (speed) |
| 3000 | 32 kt 086° +13°C | 33 kt 087° +13°C | 31 kt 086° +12°C | 30 kt 083° +12°C | 31 kt 086° +12°C | 31 kt 087° +12°C | **35 kt 088° +13°C** (speed) |
| 1500 | 25 kt 067° +14°C | 23 kt 067° +14°C | 23 kt 062° +15°C | 24 kt 061° +15°C | 22 kt 060° +14°C | 23 kt 062° +14°C | 26 kt 059° +14°C |
| Surface 452' | 7 kt 030° G11 +16°C | 12 kt 040° G22 +16°C | 13 kt 041° G21 +16°C | 13 kt 039° G22 +17°C | 12 kt 039° G22 +17°C | 12 kt 040° G21 +17°C | 14 kt 039° G19 +17°C |
Flags: 17:00 4500 ft: speed; 17:00 3000 ft: speed
Method: noaa_hrrr pressure-level profile at 6J0 (NOAA HRRR GRIB2 direct from NOAA, bilinear to 6J0), u/v/T linearly interpolated in height (geopotential, MSL); model only (CAE FB winds aloft retired 2026-11-03). Flags: arrow yellow ≥25 kt, red ≥35 kt; shear = vector difference ≥20 kt vs the level below, ≥35 kt vs the surface, or direction change ≥60° with both ≥10 kt; inversion = ≥2 °C warmer than the level/surface below; anomaly = layer lapse >3.5 °C/1000 ft between aloft levels or ≥20 °C from ISA.

## Method & sources
- Wind = ½ NWS gridpoint (6J0) + ½ mean of NBM/LAMP sustained wind at KCAE, KCUB, KAIK, KAGS. Gust = mean of NWS grid gust, the 4-station gust fit, and (17:00–21:00) 4.7+0.61·KCAE; ≥ wind+3. Decay column = sunset wind-decay model (sanity check only, ⚠ = differs >3 kt).
- Components (table and 6J0 Runway winds panel): true runway headings 171°/351° with true winds (≡ 178°/358° magnetic). XW R/L = wind from the right/left of the landing aircraft. DA uses forecast T/Td and current KCAE/KCUB altimeter 30.16 held constant (moist-air density: station pressure from the altimeter, Buck vapour pressure from Td; winds-aloft cells use the model level pressure and T/Td; surface cell = this DA).
- KCAE webcam (EarthCam live stream): ok (VM): 1920x1080, captured 11:04 EST
- WPC Day 1 national forecast chart: ok; details from map.php
- FAA SEAMS stadium TFRs (NOTAM 0/0367): ok: 5 events within 90 nm; venues: FAA AIS Stadiums (live, cached 2026-11-21T03:10Z)
- GOES-19 GLM FED+GeoColor (STAR CDN): ok: 20263251551 2400x2400 crop (910, 318, 1772, 866)
- METAR (aviationweather.gov): ok: KAGS, KAIK, KCAE, KCUB
- KCAE METAR today (hi/lo so far): ok: 11 reports since midnight
- TAF KCAE/KAGS: ok
- TAF KCAE cloud layers (json): ok
- NOAA HRRR pressure levels: ok: model noaa_hrrr cycle 2026-11-21T14:00Z f01-f10 (noaa-hrrr-bdp-pds.s3.amazonaws.com; 38 MB, 6.4 s, cache hits 9)
- NWS gridpoint raw: ok: https://api.weather.gov/gridpoints/CAE/58,51 (updated 2026-11-21T11:26:32+00:00)
- GFS LAMP (NOMADS lavtxt): ok: 2026-11-21 1530Z cycle
- NBM NBH text (NOMADS): ok: 2026-11-21 15Z cycle
- RC Winds Lexington County Airport 5-min: ok: 34 rows, latest 10:55 EST (speeds converted from mph to kt)
- KCAE NEXRAD L2 + GLM (radar_panel.py): KCAE KCAE20261121_155936_V06 0.5deg, GLM 46 files, 0 flashes, 13.2s
- AWC G-AIRMET Tango LLWS/TURB-LO: ok
- WeatherNext 3 PoP (6J0, derived from 1 h precip percentiles): ok: 8 hour bins from 6J0_wn_20261120_00Z_full.csv, 6J0_wn_20261120_12Z_full.csv, 6J0_wn_20261121_00Z_full.csv

```
TAF KAGS 211132Z 2112/2212 02006KT 6SM -RA BKN060 OVC100 
  FM211400 04012G18KT 6SM -RA SCT025 OVC045 
  FM211600 04014G20KT 5SM -RA SCT020 OVC035 
  FM211900 05013G24KT 4SM -RA BR OVC015 
  FM220300 03010G18KT 6SM -RA BR OVC008
TAF KCAE 211132Z 2112/2212 04008KT P6SM SCT060 OVC100 
  FM211400 04008G16KT P6SM VCSH SCT025 OVC045 
  FM211700 04012G20KT 5SM -RA OVC035 
  FM212200 04014G24KT 4SM -RA BR OVC025 
  FM220700 03010G18KT 6SM -RA BR OVC008
```
