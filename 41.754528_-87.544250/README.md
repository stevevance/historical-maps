# Historical maps: 41.754528, -87.544250 (South Works, Chicago)

Historical maps and aerial imagery covering a single point on the Chicago lakefront at the former US Steel South Works site, near Steelworkers Park (approximately 8700 S at the shoreline).

- **Input:** 41°45'16.3"N 87°32'39.3"W (bare coordinates)
- **Decimal (WGS84):** 41.754528, -87.544250
- **EPSG:3435:** 1199556, 1854128
- **Retrieved:** 2026-07-08

The point sits at the water's edge and falls exactly on the seam of several map-sheet grid cells, so some sheets are edge cases (noted below).

## Files (oldest first)

| Year | Preview | Source | File | Notes |
|---|---|---|---|---|
| various | [<img src="thumbnails/0000_80acres_wsw293815.jpg" width="120">](0000_80acres_wsw293815.pdf) | 80 Acres map | [`0000_80acres_wsw293815.pdf`](0000_80acres_wsw293815.pdf) | Sheet wsw293815; point is on the sheet edge (grid cell ~2 ft away) |
| 1938 | [<img src="thumbnails/1938_ilhap_0bwq09054.jpg" width="120">](1938_ilhap_0bwq09054.jpg) | ISGS Illinois Historical Aerial Photography (ILHAP) | [`1938_ilhap_0bwq09054.jpg`](1938_ilhap_0bwq09054.jpg) | Flown 1938-11-29; frame center ~662 m from target (nearest scanned frame; the closer 677 m frame was never scanned) |
| 1970 | [<img src="thumbnails/1970_cmap_3815_07.jpg" width="120">](1970_cmap_3815_07.jpg) | CMAP/NIPC aerial | [`1970_cmap_3815_07.jpg`](1970_cmap_3815_07.jpg) | Tile 3815 photo 07; georeferenced via `.jgw` alongside |
| 1975 | [<img src="thumbnails/1975_cmap_3814_09.jpg" width="120">](1975_cmap_3814_09.jpg) | CMAP/NIPC aerial | [`1975_cmap_3814_09.jpg`](1975_cmap_3814_09.jpg) | Tile 3815_07 404'd for 1975; used neighbor tile 3814 photo 09 (point is near the tile seam — target may be at the frame edge) |
| 1980 | [<img src="thumbnails/1980_cmap_3815_07.jpg" width="120">](1980_cmap_3815_07.jpg) | CMAP/NIPC aerial | [`1980_cmap_3815_07.jpg`](1980_cmap_3815_07.jpg) | Tile 3815 photo 07 |
| 1985 | [<img src="thumbnails/1985_cmap_3815_07.jpg" width="120">](1985_cmap_3815_07.jpg) | CMAP/NIPC aerial | [`1985_cmap_3815_07.jpg`](1985_cmap_3815_07.jpg) | Tile 3815 photo 07 |
| 1989 | [<img src="thumbnails/1989_sanborn_v27xxxp106c.jpg" width="120">](1989_sanborn_v27xxxp106c.pdf) | Sanborn fire insurance map | [`1989_sanborn_v27xxxp106c.pdf`](1989_sanborn_v27xxxp106c.pdf) | Nearest sheet, ~402 ft west of the point — no Sanborn sheet contains the point (lakefill/industrial edge) |
| 1990 | [<img src="thumbnails/1990_cmap_3815_07.jpg" width="120">](1990_cmap_3815_07.jpg) | CMAP/NIPC aerial | [`1990_cmap_3815_07.jpg`](1990_cmap_3815_07.jpg) | Tile 3815 photo 07 |
| 1995 | [<img src="thumbnails/1995_cmap_3815_07.jpg" width="120">](1995_cmap_3815_07.jpg) | CMAP/NIPC aerial | [`1995_cmap_3815_07.jpg`](1995_cmap_3815_07.jpg) | Tile 3815 photo 07 |
| 1998 | [<img src="thumbnails/1998_cookortho.jpg" width="120">](1998_cookortho.jpg) | Cook County ortho (CookOrthoPan1998) | [`1998_cookortho.jpg`](1998_cookortho.jpg) | Earliest county ortho, black & white (panchromatic); 600 ft square clip centered on the point |
| 2017 (survey 2017-06-05) | [<img src="thumbnails/2017_nearmap_vertical.jpg" width="120">](2017_nearmap_vertical.png) | Cook County Nearmap | [`2017_nearmap_vertical.png`](2017_nearmap_vertical.png) | Earliest Nearmap survey at this location |
| 2021 tax year | [<img src="thumbnails/2021_sidwell_2129E.jpg" width="120">](2021_sidwell_2129E.pdf) | Sidwell tax map | [`2021_sidwell_2129E.pdf`](2021_sidwell_2129E.pdf) | Page 2129E; point is on the page edge (grid cell ~2 ft away) |
| 2025 | [<img src="thumbnails/2025_cookortho.jpg" width="120">](2025_cookortho.jpg) | Cook County ortho (CookOrtho2025) | [`2025_cookortho.jpg`](2025_cookortho.jpg) | Latest county ortho; 600 ft square clip centered on the point |
| 2026 (survey 2026-03-08) | [<img src="thumbnails/2026_nearmap_north.jpg" width="120">](2026_nearmap_north.png) | Cook County Nearmap | [`2026_nearmap_north.png`](2026_nearmap_north.png) | "North" oblique view requested, but the rendered view appears vertical — flat parkland/shoreline shows little oblique difference |
| 2026 (survey 2026-03-08) | [<img src="thumbnails/2026_nearmap_vertical.jpg" width="120">](2026_nearmap_vertical.png) | Cook County Nearmap | [`2026_nearmap_vertical.png`](2026_nearmap_vertical.png) | Latest Nearmap survey, vertical view |

The `.jgw` world files alongside the CMAP aerials georeference each JPG (EPSG:3435) for use in GIS software.

## Not available / failed

- **1975 CMAP tile 3815_07** — 404 on CMAP's blob storage (also tried 3815_04, also 404); substituted neighbor tile 3814_09.
- **Sanborn / 80 Acres / Sidwell coverage caveat** — the point sits on Lake Michigan's edge at South Works; the 80 Acres and Sidwell sheets nearest the point (2 ft) were downloaded and treated as covering, but the Sanborn 1989 set has no sheet over the point itself (nearest sheet ~402 ft, included).
- **ILHAP nearest photo center (677 m)** — exists in the index but was never scanned (blank JPG_URL); next-nearest scanned frame used instead.

## Attribution

Sources: City of Chicago (Sanborn mirror, 80 Acres, Sidwell), Cook County (ortho, Nearmap viewer), CMAP/NIPC (1970-1995 aerials), Illinois State Geological Survey (ILHAP 1938).
