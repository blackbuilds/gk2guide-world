# GK2 Guide — Steam store media sources

All images downloaded from official Steam store assets for **Graveyard Keeper 2** (app **4358690**).
Site is unaffiliated with Lazy Bear Games, tinyBuild, or Valve/Steam.

Images © Lazy Bear Games / tinyBuild via Steam store media.

Steam API (`store.steampowered.com/api/appdetails`) returns **8 screenshots** + header key art for this app — the full official store set as of 2026-09-26. No additional store screenshots available beyond the files below.

| File | Steam URL | Used on |
|------|-----------|---------|
| `header-keyart.jpg` | https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/4358690/77b3cff49c45431ec507e6da5e41383050362c35/header_alt_assets_1.jpg?t=1790169326 | Brand mark (nav); **02 Autopsy** figure + card; **09 Red Skull** figure + card (skull motif) |
| `ss-graveyard-rain.jpg` | https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/4358690/b3d62f77a0c9fa2f59c6baaba11a9af5eada2927/ss_b3d62f77a0c9fa2f59c6baaba11a9af5eada2927.1920x1080.jpg?t=1790169326 | **Home** hero (graveyard overview) |
| `ss-yard-management.jpg` | https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/4358690/d4e05aa7d5ec3e9cd9648dbe2006482a886328de/ss_d4e05aa7d5ec3e9cd9648dbe2006482a886328de.1920x1080.jpg?t=1790169326 | **01 Beginner** figure + cards; **06 Energy/Bread** figure + card (early yard/garden loop) |
| `ss-zombie-workshop.jpg` | https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/4358690/e6649cbfa91e2297be1c7fb472a2ce35ede14df8/ss_e6649cbfa91e2297be1c7fb472a2ce35ede14df8.1920x1080.jpg?t=1790169326 | **03 Zombies** figure + home card |
| `ss-tech-tree.jpg` | https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/4358690/746f158d975b126bdceffb01b3e502174e18def1/ss_746f158d975b126bdceffb01b3e502174e18def1.1920x1080.jpg?t=1790169326 | **04 Tech** figure + home card |
| `ss-town-square.jpg` | https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/4358690/b240604158abbb1a96cfd52965b55ed407c9c66e/ss_b240604158abbb1a96cfd52965b55ed407c9c66e.1920x1080.jpg?t=1790169326 | **05 Faith** figure + home card (town altar/ritual circle; no church shot in set) |
| `ss-build-workspace.jpg` | https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/4358690/cf0d67bbebd1c9ee73dd90d0d9cc0a87ee3b35ba/ss_cf0d67bbebd1c9ee73dd90d0d9cc0a87ee3b35ba.1920x1080.jpg?t=1790169326 | **08 Automation** figure + home card (build-mode station layout) |
| `ss-astrologer-tower.jpg` | https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/4358690/f8a775d558c7d9201486ea83e1f672fee1e9aed7/ss_f8a775d558c7d9201486ea83e1f672fee1e9aed7.1920x1080.jpg?t=1790169326 | **07 Dream Dust** figure + home card (Astrologer's Tower ritual/study) |
| `ss-port-night.jpg` | https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/4358690/331865c3f11463c146679d11a837cb5030925543/ss_331865c3f11463c146679d11a837cb5030925543.1920x1080.jpg?t=1790169326 | **10 Alchemy** figure + home card (Port Area glowing jars) |

## Gaps (honest — do not invent shots)

- No official Steam screenshot shows a **morgue / autopsy table / corpse dissection UI**. Autopsy + Red Skull use key art (skull in hand).
- No dedicated **church / sermon / Faith UI** shot. Faith uses town square (altar/ritual circle + gothic roofs).
- No dedicated **bakery / kitchen / bread craft** shot. Energy/Bread reuses early yard/garden management.
- No dedicated **alchemy bench / formula UI** or **red-skull worker UI** close-up. Alchemy uses Port glowing jars; Red Skull reuses key art.
- Large capsule URL probes previously failed; header key art covers brand mark.

## Rebuild note

Scene figures + home card thumbs are driven by `scene_img` / `card_img` in `report/_build_site_gk2.py`. Rebuild:

```bash
/tmp/mdvenv/bin/python /workspace/seo-research-2026-09-26/report/_build_site_gk2.py
```
